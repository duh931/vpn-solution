# vpn-solution

This is a record on how to solve the VPN connection problem on windows, specifically for CISCON vpn.
1. Enable the Cisco VPN connection in the Network and Sharing center.
2. Disable the option "allow other users to connect through this computer's internet" in the share tab of the property of Cisco VPN.
3. Run service.mac and run (or restart) the Cisco VPN service.
4. Disable ISC (internet sharing) in service. 
