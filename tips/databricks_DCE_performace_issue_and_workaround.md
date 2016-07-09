
## Potential Databricks Community Edition (DCE) Performance Issue and Workaround

*By Agustine Ng*

There were reports on edX and Databricks forums of DCE user experiencing sluggish responses and occasional lost of the DCE cluster. One potential cause of the problem is that since the DCE is a free service, it is provisioned on the spot pricing tier of the AWS to keep the cost low. 

As you may already know when the computational resources of the AWS Availability Zone in which the DCE is under pressure, priority would be given to non spot pricing tier. Hence the performance degradation and in the most severe cases dropping of the DCE cluster.

One possible workaround is to create the cluster manually on a different AWS Availability Zone that has less computational load. Here is how to do that.

1.    In the left navigation pane of the DCE, click on the “Clusters” icon.
2.    In the Cluster page, click the “+ Create Cluster” button.
3.    In the bottom of Create Cluster page, click the “Show advanced settings” link.
4.    In the AWS tab, Availability Zone, click on the dropdown box to select a different Availability Zone then the current selected one.
Note: There are there options (us-west-2a, us-west-2b and us-west-2c) to choose from.
5.    Then click the “Create Cluster” button at the top of the page to create your cluster.
6.    If the new cluster was still sluggish, repeat step 1 to 5 to choose another Availability Zone.

