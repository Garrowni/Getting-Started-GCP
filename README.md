# Getting-Started-GCP
 https://www.youtube.com/watch?v=JQYgFSYFi-o

 https://github.com/ned1313/terraform-tuesdays/tree/main/2021-07-20-Getting-Started-GCP 


# gcloud iniit
# --> 1 (yes)
# cancel everything
# gcloud project create taconet-626 --set-as-default
# gcloud auth application-default login
# this opens a web browser --> allow
# enable the api
# enable compute services --> gcloud services enable compute.googleapis.com

# all the terraform file stuff

# terraform init
# terraform fmt
# terraform validate
# terraform plan -var gcp_project=taconet-626 -out ex1.tfplan
# terraform apply ex1.tfplan

# Outputs:
# public_ip_address = "35.225.26.215"