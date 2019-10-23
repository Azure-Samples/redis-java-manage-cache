---
page_type: sample
languages:
- java
products:
- azure
- azure-redis-cache
description: "Azure Redis sample for managing Redis Cache."
urlFragment: redis-java-manage-cache
---

# Manage Redis Cache (Java)

Azure Redis sample for managing Redis Cache.

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
 

## Running this sample

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

```bash
git clone https://github.com/Azure-Samples/redis-java-manage-cache.git
cd redis-java-manage-cache
mvn clean compile exec:java
```

## More information

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
