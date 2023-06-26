# gtm-list-orphaned-variables
List orphaned variables in a Google Tag Manager container

## Installation
This notebook uses some Google-specific Google Colab functions so it only runs in Colab.

To install this on Google Colab,

1. Create an empty notebook
2. In the main menu, select File > Upload Notebook to open the upload dialog
3. In the upload dialog, switch to the GitHub tab
4. In the search box, paste the URL for this repository (https://github.com/CaretJuice/gtm-list-orphaned-variables) and click on the search icon to populate matching notebook files
5. Click on the matching notebook and the code should load into your Colab notebook

## Usage
The main instructions for this notebook are written inline in the notebook.

You'll need to export your GTM container, run all of the cells in the Jupyter notebook, upload the JSON file that you exported from GTM in the file upload dialog, and authorize this script to access and edit Google Sheets.

It will create a new sheet with the title of GTM Variables for GTM-XXXXXXXX (substituting your container ID at the end).

That container file lists variables with the Match column indicated whether the JSON export has that variable name enclosed in curly braces with a "True" value indicating that the variable is in use.
