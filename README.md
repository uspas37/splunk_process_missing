This SPL will search across host in Colgate's On-prem and Cloud Environments and will determine all processes and services running
using ps and WinHostMon modules.
Once it gets an actual list of hosts and processes running on them, it will compare it with a list of hosts and processes that we are monitoring as per our procedures.

If not found, specific alerts will be triggered based on specific conditions.
