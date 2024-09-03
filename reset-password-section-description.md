# Reset Password Section Description

### Hetzner Datacenter module **[WHMCS](https://puqcloud.com/link.php?id=77)**

#####  [Order now](https://puqcloud.com/whmcs-module-hetznerdatacenter.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-HetznerDatacenter/) | [FAQ](https://faq.puqcloud.com/)

The "Reset Password" section allows users to reset the password of their virtual machine through an automated process. This section is designed to be a quick and convenient way to regain access to the server if the password has been lost or needs to be changed.

#### Key Information:

1. **Important Warning:**
    
    
    - The section prominently displays a warning in red text, stating that the password reset procedure will only work if the packages responsible for the operation of `cloud-init` have not been removed from the virtual machine. `cloud-init` is a tool used to initialize cloud instances, and it must be present for the automated password reset to function correctly.
2. **Additional Instruction:**
    
    
    - Below the warning, there is an additional note in smaller text indicating that if the reset procedure was successful but the password was not changed, the user will need to manually connect to the virtual machine using the noVNC console, boot into safe mode, and change the password manually.
3. **Reset Password Button:**
    
    
    - A green **Reset password** button is provided for users to initiate the password reset process. This button triggers the automated procedure that attempts to reset the virtual machine's password.

[![image-1725262815813.png](https://doc.puq.info/uploads/images/gallery/2024-09/scaled-1680-/image-1725262815813.png)](https://doc.puq.info/uploads/images/gallery/2024-09/image-1725262815813.png)