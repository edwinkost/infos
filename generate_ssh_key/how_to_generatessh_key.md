# How to Generate an SSH Key Using MobaXTerm (Windows)

**Note:** Linux and macOS users should proceed directly to Step 3.

## Step 1: Install MobaXTerm
Download and install the free edition from https://mobaxterm.mobatek.net/

## Step 2: Open a Terminal
Click **"Start local terminal"** in MobaXTerm's main window.

## Step 3: Generate Your SSH Key
Run this command:
```bash
ssh-keygen -t rsa -b 4096 -f ~/.ssh/id\_rsa


How to generate a ssh key using mobaxterm (for windows users; for linux/mac's, go to the step 3 directly):

1. To get the access to velocity from your windows, I recommend to install mobaxterm on your laptop.
Please install it from https://mobaxterm.mobatek.net/ (please just use the free edition version)

2. Then, start your mobaxterm and open a terminal on it. 

3. Please generate a ssh public key on the terminal, using the following command (provide example)

4. Then send this public key to the admin.

