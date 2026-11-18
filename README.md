# Windows IT Support Home Lab
A hands-on IT support lab simulating common Help Desk service requests and incidents using Windows Server, Active Directory, Windows 11, and Jira Service Management.

## Lab environment

| Component | Technology |
| --------- | ---------- |
Virtualization|	Oracle VirtualBox
Domain controller|	Windows Server 2022
Client workstation|	Windows 11 Pro
Domain|	lab.local
Services|	AD DS, DNS, Group Policy
Ticketing|	Jira Service Management

## Lab Architecture
<img width="100%" height="500" alt="Untitled1" src="https://github.com/user-attachments/assets/25c68f2b-ba14-43ea-b245-cc5b2da5a2f2" />

## Network Configuration

| Component | Configuration |
|---|---|
| Hypervisor | Oracle VirtualBox |
| Domain Controller | DC01 - Windows Server 2022 |
| Domain | lab.local |
| Domain Controller IP | 192.168.56.10 |
| Client Workstation | WIN1 - Windows 11 |
| Host-only Network | 192.168.56.0/24 |
| Host-only DHCP Server | 192.168.56.100 |
| NAT Network | 10.0.3.0/24 |
| NAT Gateway | 10.0.3.2 |
| Internal DNS | 192.168.56.10 |
| Ticketing System | Jira Service Management |

## Documented Tickets

| Ticket | Scenario |
|---|---|
| AD-001 | Removing a workstation from the domain |
| AD-002 | Joining a workstation to the domain |
| AD-003 | Creating a new domain user |
| AD-004 | Resetting a user's password |
| AD-005 | Unlocking an account |
| NET-001 | Troubleshooting incorrect DNS settings |
| NET-002 | Correcting a static IP misconfiguration |
