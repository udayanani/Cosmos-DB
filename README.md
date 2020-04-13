## Getting Started

### Prerequisites

* Before you can run this sample, you must have the following prerequisites:

   * An active Azure account. If you don't have one, you can sign up for a [free account](https://azure.microsoft.com/free/). Alternatively, you can use the [Azure Cosmos DB Emulator](https://azure.microsoft.com/documentation/articles/documentdb-nosql-local-emulator) for this tutorial. As the emulator https certificate is self signed, you need to import its certificate to the java trusted certificate store as [explained here](https://docs.microsoft.com/azure/cosmos-db/local-emulator-export-ssl-certificates).

   * JDK 1.8+
   * Maven
###

* This demo has both sync and async modes.
* From a command prompt or shell, run the following command to run the SYNC application.

```bash
mvn exec:java@sync -DACCOUNT_HOST=YOUR_COSMOS_DB_HOSTNAME -DACCOUNT_KEY=YOUR_COSMOS_DB_MASTER_KEY
```

* From a command prompt or shell, run the following command to run the ASYNC application.

```bash
mvn exec:java@async -DACCOUNT_HOST=YOUR_COSMOS_DB_HOSTNAME -DACCOUNT_KEY=YOUR_COSMOS_DB_MASTER_KEY
```

