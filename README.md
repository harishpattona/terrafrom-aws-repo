# terrafrom-aws-repo
[site](https://registry.terraform.io/)

###Install terraform in Windows powershell

[Install terraform](https://docs.microsoft.com/en-us/azure/developer/terraform/get-started-windows-powershell?
tabs=bash)

####Download 
[link](https://www.terraform.io/downloads.html)
Download for windows 64 bit Unzip the file set the path in the system environment variable

####set path
1. Download the terraform ZIP file from Terraform site.
2. Extract the .exe from the ZIP file to a folder eg C:\Apps\Terraform copy this path location like C:\Apps\terraform\
3. Add the folder location to your PATH variable, eg: Control Panel -> System -> System settings -> Environment Variables
4. In System Variables, select Path > edit > new > Enter the location of the Terraform .exe, eg C:\Apps\Terraform then click OK


terraform state list
terraform destroy -target <an resoruce from the list>


destroy -> to destroy all or destroy specific resource with -target option
terraform import -> To manage the existing resoruce on the cloud using terraform
terraform taint -> to forcefully destry and recreate the resource

