# WHMCS-Module-Hetzner-Datacenter
The Hetzner WHMCS module enables seamless integration with Hetzner Cloud services, enabling automated provisioning, management, and billing of cloud servers directly from the WHMCS platform

# Description

### Hetzner Datacenter module **[WHMCS](https://puqcloud.com/link.php?id=77)**

#####  [Order now](https://puqcloud.com/whmcs-module-hetzner-datacenter.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-HetznerDatacenter/) | [FAQ](https://faq.puqcloud.com/)

### The module, fully installed and correctly implemented in the system, offers the following functionalities.

### Module Functions:

- Auto create and deploy cloud servers
- Suspend / Unsuspend / Terminate / Change Package / Change Password
- Backup and snapshot management; reinstall from snapshot/backup
- ISO mount &amp; installation (if enabled)
- SSH key management
- Custom email notifications
- Multilingual support (English, Ukrainian, Polish, etc.)
- Client area controls for server lifecycle, console access and metrics
- **Automatic Pricing &amp; Rounding:** bulk price generation by currencies &amp; billing periods, Net/Gross base, percentage margin, live preview table, ISO-4217 round-up policy, unified UI/server logic
- **Daily Cron price sync:** uses saved bulk pricing config, Hetzner Cloud API currency, creates missing `tblpricing` rows, detailed Module Log with trace IDs
- **Admin stock tools:** “Clear and Reset” for `stockcontrol`/`qty`, `restore_saved_stockcontrol` (AJAX) with robust logging
- **Metric billing:** billing for Floating IPs, Bandwidth Usage (GB) and Snapshot Usage (GB)

### Available options in the admin panel:

- Create / Suspend / Unsuspend / Terminate servers
- Change Package and Change Password
- Select server type, location, image, placement group, SSH keys, networks and firewalls
- Allow/deny client features: console (VNC/NC), charts, reset password, ISO, reinstall, choose backup/snapshot on reinstall
- PTR visibility toggle; “Username as root”; hide inputs in client area; custom “Link to instruction”
- **Automatic Pricing UI:** set Base price (Net/Gross), Percentage margin, select currencies &amp; billing periods, view live Preview table, *Apply Bulk Pricing*
- **Automatically apply price daily:** cron-based price refresh using Hetzner base prices and WHMCS currency rates
- **Rounding policy:** always round *up* to ISO-4217 minor units; monthly → round → multiply by period → round
- **Admin stock tools:** “Clear and Reset” button and `restore_saved_stockcontrol` AJAX action
- Metric Billing configuration for Floating IPv4/IPv6, Bandwidth (GB), Snapshot Usage (GB)

### Available options in the client panel:

- Server lifecycle (start, stop, reboot) and access to remote console
- Backup and snapshot management
- ISO mount/unmount (if allowed)
- Reinstall from image, snapshot or backup (if allowed)
- Reset root password (if allowed)
- View server details, resources and usage charts (if enabled)
- PTR control (if not hidden) and quick link to instruction

- - - - - -

>WHMCS minimal version: 8+

[![product_hetzner.png](https://doc.puq.info/uploads/images/gallery/2025-10/scaled-1680-/7sBproduct-hetzner.png)](https://doc.puq.info/uploads/images/gallery/2025-10/7sBproduct-hetzner.png)

[ ![HomeHetznerDatacenter.png](https://doc.puq.info/uploads/images/gallery/2024-08/scaled-1680-/homehetznerdatacenter.png) ](https://doc.puq.info/uploads/images/gallery/2024-08/homehetznerdatacenter.png)

[ ![ReinstallHetznerDatacenter.png](https://doc.puq.info/uploads/images/gallery/2024-08/scaled-1680-/reinstallhetznerdatacenter.png) ](https://doc.puq.info/uploads/images/gallery/2024-08/reinstallhetznerdatacenter.png)

[ ![SnapshotHetznerDatacenter.png](https://doc.puq.info/uploads/images/gallery/2024-08/scaled-1680-/snapshothetznerdatacenter.png) ](https://doc.puq.info/uploads/images/gallery/2024-08/snapshothetznerdatacenter.png)

[ ![ISOmountHetznerDatacenter.png](https://doc.puq.info/uploads/images/gallery/2024-08/scaled-1680-/isomounthetznerdatacenter.png) ](https://doc.puq.info/uploads/images/gallery/2024-08/isomounthetznerdatacenter.png)

[ ![ChartsHetznerDatacenter.png](https://doc.puq.info/uploads/images/gallery/2024-08/scaled-1680-/chartshetznerdatacenter.png)](https://doc.puq.info/uploads/images/gallery/2024-08/chartshetznerdatacenter.png)
