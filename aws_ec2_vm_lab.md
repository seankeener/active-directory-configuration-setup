## Watch me do the lab HERE
https://www.loom.com/share/0c421230e9394dbeb698c7a4f2fd23ea


# Active Directory Domain Services Configuration Setup

## Lab Overview
This lab demonstrates the setup and configuration of Windows Active Directory Domain Services (AD DS) on an AWS EC2 virtual machine running Windows Server.

## Steps Performed

1. **Accessed Windows Server Manager**
   - Logged into the AWS EC2 instance running Windows Server.
   - Opened **Server Manager** from the Start Menu.

2. **Configured Active Directory Domain Services (AD DS)**
   - Selected **Manage → Add Roles and Features**.
   - Chose **Active Directory Domain Services** as the role to install.
   - Completed the setup wizard and began the installation process.

3. **Installed AD DS and Promoted the Server to a Domain Controller**
   - After installation, promoted the server to a **Domain Controller**.
   - Configured the domain name and administrative credentials.

4. **Automatic System Restart**
   - The VM automatically shut down and restarted to apply configuration changes.

## Result
The EC2 Windows Server instance was successfully configured with Active Directory Domain Services and restarted as part of the setup process.

## Notes
- Ensure that necessary inbound security group rules (e.g., RDP 3389) are configured for administrative access.
- Always take a snapshot or AMI backup before major configuration changes.
