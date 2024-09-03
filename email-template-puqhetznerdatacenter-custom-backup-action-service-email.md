# Email Template (puqHetznerDatacenter Custom backup action service Email)

### Hetzner Datacenter module **[WHMCS](https://puqcloud.com/link.php?id=77)**

#####  [Order now](https://puqcloud.com/whmcs-module-hetznerdatacenter.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-HetznerDatacenter/) | [FAQ](https://faq.puqcloud.com/)

##### Create an email template for customer notifications.

```
System Settings->Email Templates->Create New Email Template
```

- **Email Type:** Product/service

**Unique Name:** puqHetznerDatacenter Custom backup action service Email

[![image-1725200731607.png](https://doc.puq.info/uploads/images/gallery/2024-09/scaled-1680-/image-1725200731607.png)](https://doc.puq.info/uploads/images/gallery/2024-09/image-1725200731607.png)

 **Subject:**

```
{if $backup_action eq "enable"}Backup Enabled Successfully{/if}{if $backup_action eq "disable"}Backup Disabled Successfully{/if}{if $backup_action eq "create"}Backup Creation Initiated Successfully{/if}{if $backup_action eq "remove"}Backup Removed Successfully{/if}{if $backup_action eq "restore"}Backup Restoration Initiated Successfully{/if}
```

**Body:**

```
Dear {$client_name},

{if $backup_action eq "enable"}Your backup has been successfully enabled.{/if}{if $backup_action eq "disable"}Your backup has been successfully disabled.{/if}{if $backup_action eq "create"}The creation of your backup has been successfully initiated.{/if}{if $backup_action eq "remove"}Your backup has been successfully removed.{/if}{if $backup_action eq "restore"}The restoration of your backup has been successfully initiated.{/if}

{if $backup_id}Backup ID: {$backup_id}{/if}
{if $backup_description}Backup Description: {$backup_description}{/if}

If you have any questions or need further assistance, do not hesitate to contact our support team.

Thank you for choosing us.

{$signature}
```

[![image-1725200882832.png](https://doc.puq.info/uploads/images/gallery/2024-09/scaled-1680-/image-1725200882832.png)](https://doc.puq.info/uploads/images/gallery/2024-09/image-1725200882832.png)