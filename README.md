# Cisco AnyConnect Auto

A MacOS desktop application created for the purpose of being lazy to key in password every time connecting to VPN via Cisco Anyconnect Secure Mobility Client application.



# Prerequisite

Some requirements are needed in order to make it work:

- You should have already installed Cisco Annyconnect Secure Mobility Client application.
- You should have entered the VPN host you want to connect during the last use of Cisco Annyconnect Secure Mobility Client application.

# Installation

Download the `.dmg` file from [this](https://github.com/kz-sher/cisco-anyconnect-auto/releases).

# Setup

**[STEP 1]** Before you run the application, please do:

- Go to Security & Privacy:
  - Click the Privacy tab
  - Unlock for changes
  - Tick this app

**[STEP 2]** Run it now:

- A pop-up window will ask you to allow the application as trusted

**[STEP 3]** Enter VPN host name and password (just for your first time only):

- The first dialog pop-up will ask you to enter your VPN host
- The second one will then ask you to enter your password



# FAQ

1. How can I change my password/VPN host if I have already entered once?

   - Go to `Applications/Cisco AnyConnect Auto.app`

   - Right click it and choose `Show Package Content`

   - Go to `Contents/Resources/Config.plist` and open it

   - Change the value of the string field under the key field `password`

     (Note: You will notice that your password is shown here, so just replace it)



# Got Question?

> kzsherdev@gmail.com
