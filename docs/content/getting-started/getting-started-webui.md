---
title: Dovetail Studio
weight: 2020
pre: "<i class=\"fas fa-desktop\" aria-hidden=\"true\"></i> "
---

### Getting Started
For an overview of how to get started, check out the [Quickstart](../quickstart) guide

### Installing the Project Dovetail Studio
Installing the Project Dovetail Studio is quite simple just follow these steps:

1.- Go to the [releases](https://github.com/TIBCOSoftware/dovetail/releases) page and download the latest version for your os architecture.
2.- Unzip the downloaded release (for example on mac).
```cd /path/to/downloaded/file```
```unzip TIB_dovetail_0.1.1_macosx_x86_64.zip```

### Starting Dovetail Studio
To get started with your downloaded version of the Dovetail Studio in the previous step just do the following:

1.- Go to the bin directory on the unzipped folder
```cd /path/to/downloaded/file/dovetail/0.1/bin```
2.- Run studio
```./run-studio.sh eula-accept```

### Launching Dovetail Studio
To launch Dovetail Studio simply open your favorite web browser, and navigate to http://localhost:8090. You'll see the initial page to create your first smart contract!

![Web UI](../../images/labs/helloworld/step1b.png)

### Hyperledger Composer
Project Dovetail™ uses Hyperledger Composer Modeling Language to model assets, transactions and events, the resulted Business Network Archive(.bna) file is imported into Project Dovetail™ Studio to create common json schemas. 

You can use Visual Studio Code or Hyperledger Composer Playground for development

* [Visual Studio Code](https://code.visualstudio.com/docs/setup/setup-overview) 
* Visual Studio Code Hyperledger Composer Plugin
* [Hyperledger Composer Playground](https://composer-playground.mybluemix.net/editor)

After you're done launching dovetail studio , why not check out the other [labs](../../labs) we have for you!
