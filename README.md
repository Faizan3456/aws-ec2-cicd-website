## CI/CD Pipeline
This project uses GitHub Actions to automatically deploy changes to an AWS EC2 instance whenever `index.html` is updated on the main branch.

## Pipeline Flow
GitHub Commit → GitHub Actions → SSH to EC2 → Apache Restart → Live Deployment

## Screenshot
![GitHub Actions CI/CD pipeline success](https://github.com/user-attachments/assets/0ea25cd5-a022-454b-acc1-409e0983c784)

