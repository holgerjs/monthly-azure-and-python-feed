## February 2023

### Updates

- [February 2023 release of the Python and Jupyter extensions](https://devblogs.microsoft.com/python/python-in-visual-studio-code-february-2023-release/) for Visual Studio Code are now available.

### References

| # | Title | URL | Accessed-On |
| --- | --- | --- | --- | 
| 1 | Python in Visual Studio Code – February 2023 Release | https://devblogs.microsoft.com/python/python-in-visual-studio-code-february-2023-release/ | 2023-02-03 |

## January 2023

### Updates

- The Python Event Hubs client library using pure Python AMQP stack has been released. Highlights include:
    > The Event Hubs client library can now be integrated into a project like Home Assistant running on a Raspberry Pi.
    <br>&mdash; <cite>[Microsoft Developer Blogs](https://devblogs.microsoft.com/azure-sdk/announcing-the-stable-release-of-the-python-event-hubs-client-library-using-pure-python-amqp-stack/) </cite>[1]
    - [Announcement blog post including sample code](https://devblogs.microsoft.com/azure-sdk/announcing-the-stable-release-of-the-python-event-hubs-client-library-using-pure-python-amqp-stack/) [1]
    - [Event Hubs client library for Python](https://pypi.org/project/azure-eventhub/5.11.0/) [2]

- Various [library updates for the Azure SDK for Python](https://azure.github.io/azure-sdk/releases/2023-01/python.html) [3] have been released, one of which is [Azure Identity 1.13.0b1](https://pypi.org/project/azure-identity/1.13.0b1/) [4]. This library includes support for the [Windows Web Account Manager (WAM)](https://github.com/AzureAD/microsoft-authentication-library-for-dotnet/wiki/wam) through its `InteractiveBrowserCredential` class [5]. [More details here](https://dev.to/holger/azure-sdk-for-python-wam-support-in-betapre-release-34gj) [6].

- Terraform provider [azurerm v3.40.0](https://github.com/hashicorp/terraform-provider-azurerm/releases/tag/v3.40.0) [7] now supports Python 3.11 for `azurerm_linux_web_app` and `azurerm_linux_web_app_slot` resources. See [#20001](https://github.com/hashicorp/terraform-provider-azurerm/pull/20001) [8].

- [The Python Pulse has been anounced](https://devblogs.microsoft.com/python/announcing-python-pulse/), which is a new monthly livestream on the second Friday each month [9]. [The first episode](https://youtu.be/JTHTWp9DIZQ) includes demos of Dev Containers and GitHub Codespaces [10].

### References

| # | Title | URL | Accessed-On |
| --- | --- | --- | --- | 
| 1 | Announcing the stable release of the Python Event Hubs client library using pure Python AMQP stack | https://devblogs.microsoft.com/azure-sdk/announcing-the-stable-release-of-the-python-event-hubs-client-library-using-pure-python-amqp-stack/ | 2023-01-25 |
| 2 | Event Hubs client library for Python | https://pypi.org/project/azure-eventhub/5.11.0/ | 2023-01-25 |
| 3 | Azure SDK Release (January 2023) | https://azure.github.io/azure-sdk/releases/2023-01/python.html | 2023-01-25 |
| 4 | Azure Identity 1.13.0b1 | https://pypi.org/project/azure-identity/1.13.0b1/ | 2023-01-25 |
| 5 | WAM | https://github.com/AzureAD/microsoft-authentication-library-for-dotnet/wiki/wam | 2023-01-25 |
| 6 | Azure SDK for Python: WAM Support in Beta/Pre-Release | https://dev.to/holger/azure-sdk-for-python-wam-support-in-betapre-release-34gj | 2023-01-25 |
| 7 | azurerm v3.40.0 | https://github.com/hashicorp/terraform-provider-azurerm/releases/tag/v3.40.0 | 2023-01-25 |
| 8 | azurerm_linux_web_app and azurerm_linux_web_app_slot - Add Python 3.11 support #20001 | https://github.com/hashicorp/terraform-provider-azurerm/pull/20001 | 2023-01-25 |
| 9 | The Python Pulse: A Monthly Microsoft Stream | https://devblogs.microsoft.com/python/announcing-python-pulse/ | 2023-01-25 |
| 10 | Using PostgreSQL inside VS Code Dev Containers & GitHub Codespaces | https://youtu.be/JTHTWp9DIZQ | 2023-01-25 |