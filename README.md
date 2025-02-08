# ITELEC 2 - Python Programming
Laboratory Activity # 01 - Introduction to Git and a Python Hello World Program

# **Hello World Assignment**

Welcome to your first GitHub Classroom assignment! Follow the instructions carefully to complete and submit your work.

---

## **Instructions**

### **Step 1.1: Accept the Assignment**

1. Click on the assignment link provided by your instructor.
2. GitHub Classroom will create a **private repository** under your GitHub account.
3. After the repository is created, click **"Go to Repository"** to view your assignment.

---

### **Step 1.2: Setup your Git Environment**
1. Create a GitHub Account:
```bash
https://github.com/signup?source=login
```
   
2. Download and Install Git on your Laptop/Desktop:
```bash
https://git-scm.com/downloads
```

3. Create a Folder in your Laptop/Desktop
4. Right-click anywhere in the created folder and select "Open Git Bash Here".
5. In the Git Bash Terminal, set your git name, perform command:
```bash
git config --global user.name "Your Name"
```

6. In the Git Bash Terminal, set your git email, perform command:
```bash
git config --global user.email "your.email@example.com"
```

7. Create your SSH Key, just follow the instructions, no need to provide filename and passphrase. In the Git Bash Terminal, perform command:
```bash
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```

8. Copy your SSH Keys into clipboard. In the Git Bash Terminal, perform command:
```bash
clip < ~/.ssh/id_rsa.pub
```

9. Log in to your GitHub account.
10. In the upper-right corner of GitHub, click your profile picture and select Settings.
11. In the left sidebar, click on SSH and GPG keys.
12. Click the New SSH key button.
13. In the Title field, give the key a recognizable name (e.g., "My Windows Laptop").
14. In the Key field, CTRL + V or paste the keys copied into your clipboard. Save the key.
15. Go Back to terminal, use command:
```bash
ssh -T git@github.com
```

### **Step 2: Clone the Repository to Your Local Machine**

1. On your repository page, click the green **"Code"** button.
2. Copy the repository URL (choose HTTPS for simplicity).
3. Open your terminal (or Git Bash, Command Prompt, or PowerShell) and run:

```bash
git clone <remote_repo_folder>
```

4. Navigate into the cloned folder:

```bash
cd <local_repo_folder>
```

### **Step 3: Complete the Assignment**

1. Write a "Hello World" Program
Create a simple program in any programming language you are comfortable with. Save the file inside the repository folder.

Example (Python - hello.py):

1. `hello.py` (Python)
```python
print("Hello world!")
```

2. Create the intro.txt file
Open the intro.txt file in a text editor and provide the following details:
```txt
Name: [Your Full Name]
Course: [Your Course Name]
Interests in programming: [Your Interests]
```
Also, print the same information in your hello.py

### **Step 4: Push Changes to GitHub**
Once you've completed your changes, follow these steps to upload your work to your GitHub repository.

1. Check the status of your changes:
Open the terminal and run:

```bash
git status
```
This command shows any modified or new files.

2. Stage the changes:
Add all modified files to staging:

```bash
git add .
```

3. Commit your changes:
Write a meaningful commit message:

```bash
git commit -m "My first Python program"
```

4. Push your changes to GitHub:
Upload your changes to your remote repository:

```bash
git push origin main
```

### **Step 5: Submit Your Repository Link**
Once your changes have been pushed:
1. Visit your GitHub repository online.
2. Copy the repository URL from your browser (e.g., https://github.com/PLMUN-CITCS/your-repo.git).
3. Submit the repository link to your instructor via the classroom portal or as instructed.

