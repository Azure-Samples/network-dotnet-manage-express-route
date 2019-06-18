---
services: virtual-network
platforms: dotnet
author: yaohaizh
---

# Create and configure Express Route circuit #

         Azure Network sample for managing express route circuits.
           - Create Express Route circuit
           - Create Express Route circuit peering. Please note: express route circuit should be provisioned by connectivity provider before this step.
           - Adding authorization to express route circuit
           - Create virtual network to be associated with virtual network gateway
           - Create virtual network gateway
           - Create virtual network gateway connection


## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-net/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/network-dotnet-manage-express-route.git

    cd network-dotnet-manage-express-route

    dotnet restore

    dotnet run

## More information ##

[Azure Management Libraries for C#](https://github.com/Azure/azure-sdk-for-net/tree/Fluent)
[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)
If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.