# Installing-and-Configuring-DHCP

Summary
This hands-on project guided you through the installation and configuration of a DHCP server role on a Windows Server, enabling dynamic IP address allocation and effective IP address management in a LAN environment.

Key Objectives and Outcomes:
Installed the DHCP Server Role:

Accessed the Server Manager to install the DHCP server role.
Handled validation errors typical of educational environments (e.g., lacking a dedicated static IP).
Completed post-installation configuration by creating necessary security groups:
DHCP Administrators
DHCP Users
Configured the DHCP Server Scope:

Scope Details:
Assigned the name CompanyLAN.
Defined an IP address range: 192.168.1.2 to 192.168.1.254.
Ensured the range aligns with the network’s subnet.
Excluded IP Addresses for Static Devices:
Excluded the following static IP addresses for six printers:
192.168.1.30–192.168.1.32
192.168.1.40–192.168.1.41
192.168.1.56
Set IP Lease Duration:
Configured leases to expire every 24 hours (1 day, 0 hours, 0 minutes).
Activated the Scope:

Configured the default settings for DHCP options (gateway, DNS, WINS not configured in this lab).
Activated the scope to allow DHCP clients to obtain IP address leases.
Takeaways:
Efficiency and Automation:
The DHCP server reduces manual IP address configuration, saving time and minimizing errors.

Exclusions for Static Devices:
Excluding specific IPs ensures static devices (e.g., printers) retain their designated addresses, preventing conflicts.

Dynamic Network Management:
DHCP enables scalability and flexibility, allowing seamless addition of devices to the network without manual adjustments.

By following this guide, you will gainpractical experience in configuring DHCP, enabling you to manage IP addresses dynamically and improve network efficiency in a professional setting.

Everything is practically performed and stated in give pdf file
