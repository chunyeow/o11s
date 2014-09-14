802.11s MAC
===========

Non Upstream Features Added for 802.11s or o11s

Hidden mesh ID:
---------------
Patch for supporting the hidden mesh ID in 802.11s. This is non standard compliance feature, so use this only if you know what you are doing. Few points to consider when you use hidden mesh id for your mesh deployment. For open mesh, ordinary use may not easily find your network just by doing background scanning. But once they found out your network, they still can connect to your mesh network. Also, for nodes that have connected to your mesh network before, if they do active scanning, they can leak your mesh ID to others. 
