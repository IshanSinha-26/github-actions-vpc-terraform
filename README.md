
---

## ⚙️ Tasks Completed
- [x] Set up a Terraform project with reusable **modules** (VPC, EC2, S3)  
- [x] Configured **S3 backend** for remote state management  
- [x] Implemented **GitHub Actions workflow** for automated `terraform plan` & `apply`  
- [x] Secured AWS credentials using **GitHub Secrets**  
- [x] Successfully deployed AWS resources (VPC, EC2, S3)  

---

## 🚀 CI/CD Workflow
The GitHub Actions pipeline includes:
1. **Terraform Init** → Initialize Terraform & backend  
2. **Terraform Validate** → Validate configurations  
3. **Terraform Plan** → Generate execution plan  
4. **Terraform Apply** → Apply changes automatically  

📍 Workflow file: `.github/workflows/terraform.yml`

---

## 🔒 Security
- AWS credentials (`AWS_ACCESS_KEY_ID`, `AWS_SECRET_ACCESS_KEY`) are stored securely in **GitHub Secrets**.  
- Terraform state is stored in **AWS S3** with state locking enabled via **DynamoDB** (optional).  

---

## 📸 Screenshots
> Replace placeholders with actual screenshots once deployed.

- ![Terraform Init Screenshot](./screenshots/terraform-init.png)  
- ![Terraform Plan Screenshot](./screenshots/terraform-plan.png)  
- ![AWS Deployed Resources](./screenshots/aws-deployed.png)  



---

## 📚 References
- [Terraform Documentation](https://developer.hashicorp.com/terraform/docs)  
- [GitHub Actions Docs](https://docs.github.com/en/actions)  
- [AWS Free Tier](https://aws.amazon.com/free/)  

---

## 👨‍💻 Author
- **Ishan Sinha**  
- Cloud Automation | DevOps | Infrastructure as Code
