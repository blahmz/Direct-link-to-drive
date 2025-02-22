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
