# Direct-Link-to-Drive

This is an easy way to transfer files to your Google Drive.

## Disclaimer

**Warning:** This method violates Google Colab's policies. Use it at your own risk.

## Features

- Works with various file types and sources.
- This might be useful if you experience slow download speeds in your browser; using Colab, you can transfer files to Drive faster and then download them from Drive.
- Sometimes, the file will be uploaded to Drive but may not detect the file extension. Simply rename it as needed (e.g., `.txt`, `.mkv`, `.mp3`) and open it.

## Usage

### Step 1: Upload Notebook to Google Colab

1. Download the `direct_link.ipynb` file from this repository.
2. Upload it to Google Colab.
3. Open the notebook and run all cells sequentially.

### Step 2: Run Commands Manually (Alternative Method)

You can also execute the following commands directly in a Colab notebook:

```python
from google.colab import drive
drive.mount('/content/drive')
```

```bash
wget -P /content/drive/My\ Drive/ "paste_your_direct_link_here"
```

## How to Obtain Direct Download Links

### Desktop

1. Add the file to your downloads in Firefox/Chrome.
2. Right-click on the file and select **Copy Link**.

### Android

- Use the **[1DM](https://play.google.com/store/apps/details?id=idm.internet.download.manager)** app.
- Before adding the file for download, choose the **Copy Link** option.

## Notes

- Ensure you have sufficient storage space in Google Drive before downloading files.
- This method may not work with all file-sharing websites due to restrictions.

## License

This repository is open-source and provided for educational purposes only. The author is not responsible for any misuse.
