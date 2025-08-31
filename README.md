# Using GitHub files like APIs

Every file on GitHub has a "raw" version accessible through a specific URL. You can use this URL to fetch the file's contents directly.

## Step-by-Step Guide

Upload Your JSON File:
  Create or upload your JSON file to a public GitHub repository. Let's say the file is named data.json.

Navigate to the File:
  Open the file in your repository on the GitHub website.

Get the Raw URL:
  In the top-right corner of the file view, click the Raw button.

Copy the URL:
  Your browser will now show just the plain text of the JSON file. Copy the URL from your browser's address bar. It will look something like this:

https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_REPO/main/path/to/your/data.json

Use the URL in Your Code: You can now use this URL in any application to fetch the JSON data, just like you would with a regular API endpoint.
