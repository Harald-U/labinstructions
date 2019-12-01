# Workshop Preparation

## 1. Create an IBM Cloud Account

Register here [https://ibm.biz/developer-dach](https://ibm.biz/developer-dach) for a free Cloud Account

## 2. Add the feature code you received from your lab instructors

Instructions are here: [https://ibm.biz/cloudcodes](https://ibm.biz/cloudcodes)

## 3. Create a "lite" Kubernetes cluster

Instructions [here](https://github.com/IBM/cloud-native-starter/blob/master/workshop-one-service/0-create-kubernetes-cluster.md#3-create-a-free-kubernetes-cluster-)

## 4. Required tools

We need:

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) 
- [curl](https://curl.haxx.se/download.html)
- [IBM Cloud CLI](https://cloud.ibm.com/docs/home/tools)
  [IBM Cloud CLI releases](https://github.com/IBM-Cloud/ibm-cloud-cli-release/releases)
- [Docker](https://docs.docker.com/v17.12/install/)
- [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)

Since this takes some time to install and can be quite complicated on Windows, we created a Docker Image that contains all of those. In order to use it you need to have Docker installed, Docker Desktop for Mac and Windows, and Docker CE for Linux.

### Instructions for Mac and Linux: 

https://github.com/IBM/cloud-native-starter/blob/master/workshop-one-service/1-prereqs.md#tools---option-1-prefered-for-mac-or-linux-prebuilt-image-with-local-code

1. Download the Git Repo locally
2. Start the Docker Container with a mount option

This means that the Code is outside of the Container but can be accessed from within the Container.

### Instructions for Windows

https://github.com/IBM/cloud-native-starter/blob/master/workshop-one-service/1-prereqs.md#tools---option-2-prefered-for-windows-prebuilt-image-with-code-in-container

Mounting a "volume" with Docker on Windows is ... complicated. 

Instead we:

1. Start the Docker Container
2. Download the Git repo within the Container

This means that the Code is only accessible while you work in the Container.

### Undocumented option: Cloud Shell

Don't install anything, instead use "Cloud Shell", web-based shell will all relevant tools installed.

URL is https://workshop.shell.cloud.ibm.com/ with password of `ikslab` and login with your IBM ID (the same you use for IBM Cloud).

Although Docker is installed in the Cloud Shell you don't need to start the Docker Container with tools, all tools are already installed and immediately available in the Shell!


## Continue with the Workshop 

https://github.com/IBM/cloud-native-starter/blob/master/workshop-one-service/1-prereqs.md#verify-access-to-kubernetes-on-the-ibm-cloud


## Workshop 2 

In the Prerequisites section skip the instructions to create a cluster,

Perform Step "3. Verfiy the major prerequisites on your machine"  

Then continue with Step "4.4 Get an IBM platform key" and follow the instructions from there on.



