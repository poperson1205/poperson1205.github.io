---
title: "Launch teamviewer through ssh"
categories:
 - Memo
tags:
 - remote work
 - ssh
 - teamviewer
---

I use teamviewer to remotely access my ubuntu machine.

* WSL (local) --> Ubuntu (remote)

Although ssh connection is way faster than teamviewer, I got following problems on ssh access:

- To access docker container in vscode
- To access full GUI of the remote machine

Teamviewer frees me out of those issues.

To use teamviewer, it must be running on my remote machine.

However, sometimes it dies.

This post explains the way to launch it from my local machine, through ssh access.

# References
- <http://www.tonisoto.com/2013/07/launching-teamviewer-remotely-throught-ssh/>





