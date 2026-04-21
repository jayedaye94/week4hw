<img width="962" height="1157" alt="image" src="https://github.com/user-attachments/assets/91a44599-4f67-45ab-a6f0-c78657f1d451" />
Create a Bucket with a simple sample name. Choose and name and click create. Without any additional changes.

<img width="755" height="467" alt="image" src="https://github.com/user-attachments/assets/e482392b-d2c3-4637-a60e-c841ffef3146" />

Once you create the bucket, go ahead and make you way across the directory to week4HW then open up VScode with Code .

Make sure to rename the project tab to your project ID in GCP

<img width="1018" height="566" alt="image" src="https://github.com/user-attachments/assets/accb9796-bbd6-4717-9a9f-ddd5dd7d50a3" />

Create an 0-Auth.tf folder and C/P code from the repo
<img width="1659" height="1346" alt="image" src="https://github.com/user-attachments/assets/e155c92e-56eb-448d-b362-292895a72584" />
Terraform Init-validate-plan-apply for 0-Authentication

Create a 1-backend.tf folder and copy the code from the repo and change the bucket tab to your bucket name created on the console.
<img width="1435" height="507" alt="image" src="https://github.com/user-attachments/assets/e68b2f16-b492-4014-9157-39b740552e8d" />

Terraform init, validate, plan, apply for the 1-backend.tf
<img width="1768" height="1341" alt="image" src="https://github.com/user-attachments/assets/f521cc21-9ced-406d-a8ef-1364dafa1ace" />
<img width="1347" height="1171" alt="image" src="https://github.com/user-attachments/assets/ebe38c63-1416-433d-840b-353486d13ea4" />


Once that's done, create a 2-vpc.tf folder next. Then copy the code from the repo. You "can" change the "name" of the VPC from the code away from "main" to something else to help identify what it is that you need. For example.... I changed mine to "week4hw-vpc"

<img width="1006" height="894" alt="image" src="https://github.com/user-attachments/assets/b43e6423-72e9-47cb-8576-205c9a2cff34" />

Terraform *validate* this time around, plan, apply for the vpc.tf folder.
<img width="1067" height="1276" alt="image" src="https://github.com/user-attachments/assets/99598aa4-a748-4560-8ddc-7120db77d9a2" />

After that, it should create a VPC named either main as default, or whatever you named it.
<img width="1061" height="334" alt="image" src="https://github.com/user-attachments/assets/b9b33da0-320b-4b09-b67d-4f78ff1cf8c2" />

If you want to change the name after the fact, you can, and then just run apply and it'll be done when you refresh.

When you want to destroy everything, just type in terraform destroy to delete everything ran in that code.

<img width="1748" height="1363" alt="image" src="https://github.com/user-attachments/assets/b87ab11d-1892-46ba-b299-7de9f9af78e1" />
<img width="838" height="188" alt="image" src="https://github.com/user-attachments/assets/efa49287-5b3a-40c4-ae22-7c1b50763a26" />

