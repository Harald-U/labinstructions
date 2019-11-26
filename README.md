# Access a preconfigured OpenShift cluster

1. If you haven't already done so:
    * Register for a free IBM Cloud Account at [https://ibm.biz/developer-dach](https://ibm.biz/developer-dach)
    * Check your emails for a verification mail and click the link 

2. Go to [https://ibmdeveloperberlin.mybluemix.net/](https://ibmdeveloperberlin.mybluemix.net/)

    * Lab key for this lab is "oslab"
    * Enter the IBM ID (the one you registered on IBM Cloud)  
    * Accept the T&Cs
    * Click submit

    ![granttool1](images/granttool1.png)

    If everything works you will see a confirmation like this one:

    ![granttool2](images/granttool2.png)

3. Access your OpenShift cluster

    * Logon to the IBM Cloud

    ![os cluster](images/os-cluster.png)

    * Select the `1840867 - IBM` account in the menu, right side
    * Open the Burger menu --> OpenShift --> Clusters
    * Click on the cluster assigned to you, it should be the same from the confirmation above
    * Then click on "OpenShift web console"

4. Your work environment

    * We need several tools: docker, git, oc, ibmcloud, to name a few
    * You can either install those, use a [Docker Tools image](https://github.com/IBM/openshift-on-ibm-cloud-workshops/blob/master/2-deploying-to-openshift/documentation/1-prereqs.md#tools) we created for this lab
    * If you haven't installed Docker or cannot install apps on your notebook, use a "Cloud Shell" in a Browser
    * To access a Cloud Shell go to [https://workshop.shell.cloud.ibm.com/](https://workshop.shell.cloud.ibm.com/), password is `ikslab`. You may need to logon with your IBM ID and select your own account, not the `1840867 - IBM` where your cluster resides!
    * 


