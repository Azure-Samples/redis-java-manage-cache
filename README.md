---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Rediscache
  platforms: java
---

# Getting Started with Rediscache - Manage Redis Cache - in Java #


  Azure Redis sample for managing Redis Cache:
   - Create a Redis Cache and print out hostname.
   - Get access keys.
   - Regenerate access keys.
   - Create another 2 Redis Caches with Premium Sku.
   - List all Redis Caches in a resource group – for each cache with Premium Sku:
      - set Redis patch schedule to Monday at 5 am.
      - update shard count.
      - enable non-SSL port.
      - modify max memory policy and reserved settings.
      - restart it.
   - Clean up all resources.
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/main/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/main/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/redis-java-manage-cache.git

    cd redis-java-manage-cache

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

If you find bug in the sample, please create an issue [here](https://github.com/Azure/azure-sdk-for-java/issues).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
