# Publishing This Project on GitHub

## 1. Review the Project

Check the documentation and make sure it reflects the actual lab work.

## 2. Add Screenshots

Place genuine lab screenshots in:

`evidence/screenshots/`

## 3. Review Sensitive Information

Remove passwords, private addresses where unnecessary, authentication
tokens, and other confidential information before publishing.

## 4. Create a GitHub Repository

Create a new repository named:

`Suricata-IDS-Lab`

## 5. Upload

Upload the project folder contents to the repository.

Alternatively, use Git from the project directory:

```bash
git init
git add .
git commit -m "Initial Suricata IDS lab documentation"
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with the URL of your own
GitHub repository.

Do not upload fabricated evidence or sensitive log data.
