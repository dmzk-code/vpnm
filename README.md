# VPN
It is a VPN application developed based on OpenVPN3 using Python and Kivy and KivyMD frameworks

## Modification
The OpenVPN build has been modified, namely the file cli.cpp

Namely, a flag file search thread has been added to stop the Internet connection more correctly, as the OpenVPN developers intended, this approach will allow the hidden console to catch a signal to properly disconnect the VPN connection.

## Client
Building the client, the client itself is built in Python using the KIvy cross-platform framework and its complement KivyMD and the assembled layer ovpncli.exe and tap/tun drivers.
My project itself was built through PyInstaller and I offer you a working version of the custom OpenVPN client.
All this allows us to make the VPN service application more flexible, beautiful and easy to develop.

## Current goals

The Android version is currently being actively developed and then the iOS version. In this project, I don't want to involve a developer like @schwabe "I am just not willing to be the unpaid support for other people trying to make money out of my code for free anymore."

### Other
Of course, yes, it can be understood, but you, dear friend, can also assemble the file in the same way.so create autobindings for it and use only openvpn3.
