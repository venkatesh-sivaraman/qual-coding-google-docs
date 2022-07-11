# Transfer Google Docs Comments to CSV for Analysis

This Jupyter notebook helps you perform qualitative analysis by transferring your comments (codes) into a CSV file, which can be imported into a spreadsheet application for analysis. The overall analysis pipeline using this script looks like this:

1. Import your transcripts into a Google Drive folder
2. Open the scripts as Google Docs (important - make sure they are not still in Word document format) and make comments to represent qualitative codes. The comments "+1" and anything beginning with "MEMO" will be filtered out.
3. Create a Google Cloud Platform account and input credentials in this notebook
4. Obtain the Google Drive folder ID for the folder containing your transcripts and enter it in the notebook
5. Run the extraction pipeline to obtain the CSV file containing all codes
6. Perform analysis on the resulting spreadsheet, or import the codes into a whiteboard app such as Mural or Miro

Further instructions and possible modifications can be found in the notebook.
