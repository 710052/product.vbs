# Windows Product Key Reader Script

### Overview
This script is designed to read and display the Windows Product Name, Product ID, and Product Key from the system registry. It can also save this information to a text file on the user's desktop upon confirmation. This tool is useful for backing up your Windows activation details, especially before a system reinstallation or transfer to a new machine.

### Features
* Reads the Product Name, Product ID, and Product Key from the Windows registry.
* Converts the binary DigitalProductId into a readable product key format.
* Optionally saves the retrieved information to a file on the desktop.

### Usage
Steps:
1. Open Command Prompt or PowerShell.
2. Navigate to the directory containing the script.
3. Execute the script:

'''
product_key.vbs
'''

4. A message box will display the Windows Product Name, Product ID, and Product Key.
5. You will be prompted to save this information to a file. Click 'Yes' to save or 'No' to dismiss.

### Security and Privacy
This script reads sensitive information from your system. The product key is unique to your Windows installation and should be kept confidential. If you choose to save this information to a file, ensure that the file is stored securely and deleted if no longer needed.

### Disclaimer
This script is provided "as is", without warranty of any kind. Use it at your own risk. The author is not responsible for any misuse or damage arising from the use of this script.
