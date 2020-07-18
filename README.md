# ike

Also known as the Shrewsoft VPN Manager.

The Shrew Soft VPN Client for Linux and BSD is an IPsec Client for FreeBSD, NetBSD and many Linux based operating systems. This version is distributed under an OSI approved open source license and is hosted in a public subversion repository. It supports most of the features available in the Windows VPN Client version with the exception of those which are not cross platform compatible.

Website: https://www.shrew.net/home

# Notes

- 'unable to open /etc/iked.conf'. If you have received this type in error. Just create empty file and named 'iked.conf'.

# Local installation

`snapcraft`
`sudo snap install --devmode ./ike-qt_2.2.1_amd64.snap`
`sudo snap run ike-qt.iked` (Start the daemon)
`/snap/bin/ike-qt.qikea` (Run the GUI)

# Still in beta, some features may not work.
