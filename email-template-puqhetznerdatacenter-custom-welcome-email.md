# Email Template (puqHetznerDatacenter Custom Welcome Email)

### Hetzner Datacenter module **[WHMCS](https://puqcloud.com/link.php?id=77)**

#####  [Order now](https://puqcloud.com/whmcs-module-hetznerdatacenter.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-HetznerDatacenter/) | [FAQ](https://faq.puqcloud.com/)

##### Create an email template for customer notifications.

```
System Settings->Email Templates->Create New Email Template
```

- **Email Type:** Product/service

**Unique Name:** puqHetznerDatacenter Custom Welcome Email

[![image-1725014242260.png](https://doc.puq.info/uploads/images/gallery/2024-08/scaled-1680-/image-1725014242260.png)](https://doc.puq.info/uploads/images/gallery/2024-08/image-1725014242260.png)

 **Subject:**

```
Your Server is Now Ready for Use
```

**Body:**

```
Dear {$client_name},

Congratulations! Your server has been successfully deployed and is ready for you to begin configuring.

Server Details:
IPv4 DNS PTR: {$ipv4_dns_ptr}
IPv4 IP: {$ipv4_ip}
IPv6 IP: {$ipv6_ip}
Server Cores: {$server_cores}
Server Memory: {$server_memory}
Server Disk: {$server_disk}
Root Password: {$root_password}
Accessing Your Server

To begin managing your new server, you will need to connect via SSH (Secure Shell). Here’s how you can do that:

    Open an SSH client on your computer. For Windows, we recommend using PuTTY, while macOS and Linux users can use the built-in Terminal application.

    Connect to your server by executing the following command in your terminal or SSH client:
    ssh root@{$ipv4_ip}

    When prompted, enter the root password provided below:

    Root Password: {$root_password}

Once connected, you’ll have full access to your server’s console and can monitor the installation.
Need Assistance?

If you have any questions or encounter any issues during this process, please do not hesitate to reach out to our support team. We are here to help! You can submit a support ticket via the following link: Submit a Ticket.

Thank you for choosing us as your hosting provider. We’re excited to be part of your journey and are committed to ensuring your experience is successful.

Kind regards,
{$signature}
```

[![image-1725014459758.png](https://doc.puq.info/uploads/images/gallery/2024-08/scaled-1680-/image-1725014459758.png)](https://doc.puq.info/uploads/images/gallery/2024-08/image-1725014459758.png)