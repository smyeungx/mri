SMCS Internet Connection drop very often
- Make sure in Device Manager -> Network adapters for internet sharing -> Properties -> Power Management -> DO NOT select "Allow the computer to turn off this device to save power"
- [Internet Connection Sharing on Prodiva Console](https://learn.microsoft.com/en-gb/troubleshoot/windows-client/networking/ics-not-work-after-computer-or-service-restart).

What's the Network Configuration for Prodiva and SMCS
- Prodiva:
  - IP 10.0.0.1
  - Subnet Mask: 255.255.255.0
  - Gateway: Do not fill
  - DNS: Do not fill
- SMCS:
  - IP 10.0.0.5
  - Subnet Mask: 255.255.255.0
  - Gateway: 10.0.0.1
  - DNS: 10.0.0.1
