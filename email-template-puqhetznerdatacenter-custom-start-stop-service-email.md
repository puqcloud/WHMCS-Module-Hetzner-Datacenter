# Email Template (puqHetznerDatacenter Custom start stop service Email)

### Hetzner Datacenter module **[WHMCS](https://puqcloud.com/link.php?id=77)**

#####  [Order now](https://puqcloud.com/whmcs-module-hetznerdatacenter.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-HetznerDatacenter/) | [FAQ](https://faq.puqcloud.com/)

##### Create an email template for customer notifications.

```
System Settings->Email Templates->Create New Email Template
```

- **Email Type:** Product/service

**Unique Name:** puqHetznerDatacenter Custom start stop service Email

[![image-1725014717960.png](https://doc.puq.info/uploads/images/gallery/2024-08/scaled-1680-/image-1725014717960.png)](https://doc.puq.info/uploads/images/gallery/2024-08/image-1725014717960.png)

 **Subject:**

```
{if $server_action eq "start"}Your Server Has Been Successfully Started{/if}{if $server_action eq "stop"}Important: Your Server Has Been Stopped{/if}
```

**Body:**

```
Dear {$client_name},

{if $server_action eq "start"}Your server has been successfully started.{/if}{if $server_action eq "stop"}Your server has been stopped.{/if}

Product/Service: {$service_product_name}

If you have any questions or need further assistance, do not hesitate to contact our support team.

Thank you for choosing us.

{$signature}
```

[![image-1725016539213.png](https://doc.puq.info/uploads/images/gallery/2024-08/scaled-1680-/image-1725016539213.png)](https://doc.puq.info/uploads/images/gallery/2024-08/image-1725016539213.png)