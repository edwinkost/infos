# How to generate a new ssh key using mobxterm (windows)

**Note:** Linux and macOS users should proceed directly to Step 3.

## Step 1: Install mobaxterm
Download and install the free edition from https://mobaxterm.mobatek.net/

## Step 2: Open a terminal
Start a terminal in mobaxterm

## Step 3: Generate Your SSH Key
Run this command on your terminal.
```
ssh-keygen -t ed25519 -C "mobaxterm@my_laptop"
```

When you're prompted to "Enter a file in which to save the key", you can press Enter to accept the default file location. Please note that if you created SSH keys previously, ssh-keygen may ask you to rewrite another key (in which case a custom-named SSH key file name is recommended). 

At the next prompts (regarding passphrase), you can also just press Enter (for simply using no passphrase).

## Step 4: Display/copy your public ssh key
To display, your public ssh key, you can run this command on your terminal.
```
cat ~/.ssh/id_rsa.pub
```

Example output:
```
ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIKf8vN2pL9mK3qR5sT7uW9xY2aB4cD6eF8gH1iJ3kL5m mobaxterm@my_laptop
```

## Step 5: Send the copied public key to your admin via email or designated form.
Important: Never share your private key (id_rsa). Only share the public key (id_rsa.pub).
