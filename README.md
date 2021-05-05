# Chromebook

## Factory Reset

- Sign out of your Chromebook.
- Press and hold `Ctrl` + `Alt` + `Shift` + `r`.
- Select Restart.
- In the box that appears, select Powerwash and then Continue.
- Follow the steps that appear and sign in with your Google Account.
- Note: The account that you sign in with after you reset your Chromebook will be the owner account.
- Once you've reset your Chromebook:
- Follow the onscreen instructions to set up your Chromebook
- Check if the problem is fixed

## Setup

- Click Get Started
- Connect to WiFi network
- Accept and continue Google Terms of Service
  - If the device has already been enrolled to an Enterprise, this is confirmed at this step
- Click Done
- Signin with email
  - Look to have 2FA setup at this stage
- Click Accept and continue
- Click I agree to Google Assistant
- Click I agree toAccess your assistant

## Setup Pixel Bubs

- Go to Settings > Bluetooth
- Click the button on the Pixel Bubs case
- Select the Pixel Bubs from the Bluetooth menu

## Chrome Setup

- Log into 1password in Chrome

## Setup Terminal

- Search for Linux
- Click install terminal
- Install tmux `sudo apt install tmux -y`
- Copy public key (`cat .ssh/id_rsa.pub) to:
  - [GitHub](https://github.com)
  - Any computers to connect onto (`vi ~/.ssh/.authorized_keys`)
- Setup ssh config on Chromebook (`vi ~/.ssh/config`)
  - Add anything you're going to ssh onto
- Setup git directory and pull repos
  - `mkdir git && cd git`
  - `git clone git@github.com:denhamparry/chromebook.git`

