# Microsoft Office 2021

# Table of Contents
   * [Download and install Office 2021](#download-and-install-office-2021)
      * [Install Office 2021 using Office Deployment Tool](#install-office-2021-using-office-deployment-tool)
   * [Activate Microsoft Office 2021](#activate-microsoft-office-2021)
      * [Method 1: Activate Microsoft Office 2021 Commands](#method-1-activate-microsoft-office-2021-using-command-prompt)
      * [Method 2: Activate Microsoft Office 2021 Batch File](#method-2-activate-microsoft-office-2021-using-batch-file)

# Download and install Office 2021
## Install Office 2021 using Office Deployment Tool

Before you get started, Make sure that the operating system version you’re running is Windows 10 or later. There is no way to install Office 2021 on Windows 8.1 or earlier.

**Step 1:** Download the zip file, right-click and then Extract the downloaded file to your computer.

[Download Office 2021](https://raw.githubusercontent.com/21Z/Microsoft-Office-2021/main/Office2021.zip)

**Step 2:** Open **Install-x32.bat** or **Install-x64.bat** to install Microsoft Office 2021 64-bit or 32-bit as you need.

Installing **Microsoft Office 2021,** it’ll take several minutes depending on your internet speed.

![Installing Office](https://raw.githubusercontent.com/21Z/Microsoft-Office-2021/main/assets/Installing-Office.jpg)

Once the installation is completed, let's open any Office apps. As you can see, you need to activate Office 2021 license, the trial license will expire in 7 days.

![Activation Required](https://raw.githubusercontent.com/21Z/Microsoft-Office-2021/main/assets/Activation-Required.jpg)

# Activate Microsoft Office 2021
## Method 1: Activate Microsoft Office 2021 using Command Prompt
**Step 1:** Type **cmd** in search box, right click on **Command Prompt** then select **Run as administrator**.

![Command-Prompt](https://raw.githubusercontent.com/21Z/Microsoft-Office-2021/main/assets/Command-Prompt.jpg)

**Step 2:** Copy all below commands, **right click to paste into cmd window** at once then hit Enter.

```
if exist "C:\Program Files\Microsoft Office\Office16\ospp.vbs" cd /d "C:\Program Files\Microsoft Office\Office16"
if exist "C:\Program Files (x86)\Microsoft Office\Office16\ospp.vbs" cd /d "C:\Program Files (x86)\Microsoft Office\Office16"
cscript ospp.vbs /inpkey:FXYTK-NJJ8C-GB6DW-3DYQT-6F7TH
cscript ospp.vbs /sethst:kms.msgang.com
cscript ospp.vbs /act
pause
```
**Microsoft Office 2021** was activated, and you can start using the applications without any restrictions or limitations.

![Command-Prompt-Window](https://raw.githubusercontent.com/21Z/Microsoft-Office-2021/main/assets/Command-Prompt-Activate.jpg)

## Method 2: Activate Microsoft Office 2021 using Batch File
**Step 1:** Right-click the Activator.bat file then select Run as administrator (You can find it in the Office2021 zip file).

![Run Batch file](https://raw.githubusercontent.com/21Z/Microsoft-Office-2021/main/assets/Activator-Batch.jpg)

Finally, check the activation status of **Microsoft Office 2021**. Congratulations! The activation was completed successfully.

![Activation Complete](https://raw.githubusercontent.com/21Z/Microsoft-Office-2021/main/assets/Activated.jpg)

Credits: https://msgang.com
