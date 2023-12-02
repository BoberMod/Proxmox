<div align="center">
<img src="https://raw.githubusercontent.com/tteck/Proxmox/main/misc/images/logo.png" height="100px" />
</div>
<h1 align="center">Proxmox VE Helper-Scripts</h1>

<p align="center">
  <a href="https://helper-scripts.com/">Website</a> | 
  <a href="https://github.com/tteck/Proxmox/blob/main/.github/CONTRIBUTING.md">Contribute</a> |
  <a href="https://github.com/tteck/Proxmox/blob/main/USER_SUBMITTED_GUIDES.md">Guides</a> |
  <a href="https://github.com/tteck/Proxmox/blob/main/CHANGELOG.md">Changelog</a> |
  <a href="https://ko-fi.com/D1D7EP4GF">Support</a>
</p>

---

These scripts empower users to create a Linux container or virtual machine interactively, providing choices for both simple and advanced configurations. The basic setup adheres to default settings, while the advanced setup gives users the ability to customize these defaults. 

Options are displayed to users in a dialog box format. Once the user makes their selections, the script collects and validates their input to generate the final configuration for the container or virtual machine.
<p align="center">
Be cautious and thoroughly evaluate scripts and automation tasks obtained from external sources. <a href="https://github.com/tteck/Proxmox/blob/main/CODE-AUDIT.md">Read more</a>
</p>
<sub><div align="center"> Proxmox® is a registered trademark of Proxmox Server Solutions GmbH. </div></sub>

---

<h1 align="center">Changes in fork</h1>

This fork contains updated installation scripts for some services to make process of <a href="https://itsembedded.com/sysadmin/proxmox_bind_unprivileged_lxc/#method-2-changing-the-default-lxc-uidgid-mapping">binding mount points</a> to unprivileged LXC containers easier. Fork is automatically synchronized with upstream. All scripts, except for installations, are loaded from the original repository.

<h3>Changelog: </h1>

<b> radarr </b>
<ul>
  <li>New user <code>radarr</code> with UID 1000 is added</li>
  <li>New group <code>radarr</code> with GID 1000 is added</li>
</ul>
