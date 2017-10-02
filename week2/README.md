# NetAutomation
Homework for the IPSpace Network Automation course

Playbook to check connectivity within the lab.

The playbook will:
1) Gather a list of interfaces from the core IOS routers (CSR100v-1 and
CSR100v-2)
2) Each NXOS device will ping all interfaces for each core router except the
VIRL management interface and gather packet loss stats
3) Write results to a new file
