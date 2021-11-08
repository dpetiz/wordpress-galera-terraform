# Wordpress With Galera-Mysql Cluster

This zip can be used to deploy a wordpress instance with a mysql-galera cluster on kubernetes using terraform.

First of all install terraform on your computer, minikube and helm.

After that you can 

$ terrraform init

$ terraform plan

$ terraform apply


The zip containers the terraform.tf, and the values for wordpress and mysql-galera chart.

# The password is random generated and the output is printed on the end of deploy.

You can define your self password customizing and creating a kubernetes secret, or simply passing it in clear text on vars (no safe dude)
