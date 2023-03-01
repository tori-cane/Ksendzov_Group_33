# GitHub Branches Homework

1. In your local repository create multiple branches: Postman, JMeter, CheckLists, Bug_Reports, SQL, Charles, Mobile_Testing
```bash
1. Go to your GitHub Profile and click on Repositories
2. Click on New and type a name "branches" (select Initialize this repository with a README and "Create repository")
3. Click on "Code" button and cope HTTP link
4. Run GitBash on your computer
```
Write
```bash
git clone https://github.com/tori-cane/branches.git
```
```bash
cd branches
```
```bash
git branch Postman | git branch JMeter | git branch CheckLists | git branch Bug_Reports | git branch SQL | git branch Charles | git branch Mobile_Testing 
```

2. Push all created branches to the remote repository
```bash
git push -u origin Postman JMeter CheckLists Bug_Reports SQL Charles Mobile_Testing
```

3. In Bug_Reports branch create a new TXT file with bug report structure
```bash
git checkout Bug_Reports
```
```
vim bug_report_structure.txt
i (edit)
Required fields for the bug report:
- ID
- Environment
- Summary
- Steps To Reproduce
- Expected Result
- Actual Result
- Severity
- Priority
- Reported By
- Assigned To
- Reproducibility
- Preconditions
```
```
:wq - save and close the editor
```
4. Push created txt file to the remote repository
```bash
git add bug_report_structure.txt
```
```bash
git commit -m "added bug_report_structure.txt"
```
```bash
git push
```

5. Merge Bug_Reports branch into Main (branch)
```bash
git checkout main
```
```bash
git merge Bug_Reports
```

6. Push local Main branch to remote
```bash
git push
```

7. In CheckLists branch create a new TXT file with a checklist structure
```bash
git checkout CheckLists
```
```bash
vim checklist.txt
i (edit)
Checklist Fields:
- ID
- Title
- Input Data
- Expected Result
- Status
```
```bash
:wq - save and close the editor
```

8. Push checklist.txt to the remote repository
```bash
git add checklist.txt
```
```bash
git commit -m "added checklist.txt"
```
```bash
git push
```

9. In the remote repository create a Pull Request of the CheckLists branch into Main
```bash
1. Go to branches repository
2. Click on "Compare & pull request"
3. Click on "Create pull request"
4. Click on "Merge pull request" > "Confirm Request"
```

10. Synchronize remote and local Main branches
1. Run GitBash on your computer

```bash
git checkout main
```
```bash
git pull
```
