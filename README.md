# Direct-link-to-drive

**Disclaimer:** This method is against Google Colab's policies. Use it at your own discretion.




### Direct Link to Drive (`direct_link.ipynb`)  
This notebook enables transferring files from direct download links to Google Drive.  

#### Usage:  
1. Download and upload `direct_link.ipynb` to Google Colab or copy and paste the below code.
2. Run all cells sequentially.  
3. Alternatively, use the following command to save a file directly to Google Drive:  
   ```bash
  from google.colab import drive
  drive.mount('/content/drive')

   ```bash
   !wget -P /content/drive/My\ Drive/ "paste your direct link here"

### How to Get Direct Download Links  
- **Desktop:** Add the file to your downloads in Firefox/Chrome, then right-click on it and select **Copy Link**.  
- **Android:** Use the [1DM](https://play.google.com/store/apps/details?id=idm.internet.download.manager) app. Before adding the file for download, an option to **Copy Link** will be available.  


Direct-Link-to-Drive

Disclaimer

Warning: This method violates Google Colab's policies. Use it at your own risk.

Overview

This repository provides a Jupyter Notebook (direct_link.ipynb) that facilitates transferring files from direct download links to Google Drive.

Features

Easily download files from direct URLs to Google Drive.

Works with various file types and sources.

Simple setup and execution.


Usage

Step 1: Upload Notebook to Google Colab

1. Download the direct_link.ipynb file from this repository.


2. Upload it to Google Colab.


3. Open the notebook and run all cells sequentially.



Step 2: Run Commands Manually (Alternative Method)

You can also execute the following commands directly in a Colab notebook:

from google.colab import drive
drive.mount('/content/drive')

!wget -P /content/drive/My\ Drive/ "paste_your_direct_link_here"

How to Obtain Direct Download Links

Desktop

1. Add the file to your downloads in Firefox/Chrome.


2. Right-click on the file and select Copy Link.



Android

Use the 1DM app.

Before adding the file for download, choose the Copy Link option.


Notes

Ensure you have sufficient storage space in Google Drive before downloading files.

This method may not work with all file-sharing websites due to restrictions.


License

This repository is open-source and provided for educational purposes only. The author is not responsible for any misuse.

