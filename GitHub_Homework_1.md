# GitHub Homework 1
## JSON

1. Create a remote repository named JSON
```
1. Go to your GitHub Profile
2. Click on Repositories > New
3. Type a name JSON and select Initialize this repository with a README.
4. Click Create repository
```
2. Clone JSON repository to your local computer
```
1. Go to created repository page
2. Click on Code button
3. Copy HTTPS link
4. Launch Git Bash from your computer
5. Write
git clone https://github.com/tori-cane/JSON.git
```
3. In your local JSON repository create a new file named "new.json"
```bash
cd JSON
```
```bash
touch new.json
```
4. Add file to the Git staging area
```bash
git add new.json
```
5. Save changes (commit) to the local repository
```bash 
git commit -m "new file added"
```
6. Upload (push) local repository content to a remote repository
```bash
git push
```
7. Edit the contents of "new.json" by adding information about yourself (full name, age, number of pets, desired salary etc.)
```
vim new.json
i (edit)
 ```
 ```json
 {
		"Name" : 
			{
				"First Name" :  "Victoria",
				"Last Name" : "Vasylieva"
			},
		"Age" :  27,
		"Languages" :  
			{
				"Ukrainian" : "Native",
				"English" : "Fluent",
				"Ukrainian" : "Beginner"
			},
		"Nationality" : "Ukrainian",
		"Phone Number" : 2893985466,
		"City" : "Kyiv",
		"Sex" : "Female",
		"Driving License" : "Yes",
		"Height (cm)" : 182,
		"Children": "No",
		"Pets" : "No"
}
```
```
:wq - save and close the editor
```
8. Update the remote branch with local commits
```bash
git add new.json
```
```bash
git commit -am "updated info in new.json"
```
```bash
git push
```
9. Create a new file named "preferences.json"
```bash
touch preferences.json
```
OR
```bash
cat > preferences.json
```
10. Edit the contents of "preferences.json" by adding info about your preferences (favorite movie, favorite tv series, favorite food, favorite season, favorite travel destination etc.)
```
vim preferences.json
i (edit)
```
```json
{
	"Favorite Movie" : "Forrest Gump",
	"Favorite Flower" : "Protea",
	"Favorite Beverage" : 
		{
		"Hot" : "Green Tea",
		"Cold" : "Lemonade"
		},
	"Favorite Music" : "Mozart",
	"Favorite Book" : "Faust",
	"Favorite Season" : "Spring",
	"Favorite Cities" :
		{
		"USA" : "New York",
		"Great Britain" : "Bristol",
		"Italy" : "Rome",
		"Spain" : "Barcelona"
		}
}
```
```
:wq - save and close the editor
```
11. Create a new file named "skills.json" and add information about a skill set obtained on this course
```
vim skills.json
i (edit)
```
```json
{
	"Testing Fundamentals" : "SDLC", "STLC", "Bug Lifecycle", "Requirements Analysis", "Test Design Techniques", "Scrum development process", "Testing Methods", "Network Principles",
	"Tools" :
		{
			"Bug Tracking Systems" : "Jira",
			"Test Management Tools" : "TestRails",
			"QA Automation Tools" : "Selenium WebDriver",
			"API Testing" : "Postman"
		},
	"Languages" : "Python", "SQL"
}
```
```
:wq - save and close the editor
```
12. Push "preferences.json" and "skills.json" to the remote repository in a single commit
```bash
git add
```
```bash
git commit -m "added skills.json amd preferences.json"
```
```
git push
```
13. Create a new file named "bug_report.json" using Git web interface
```
1. Go to remote repository using web interface and click on "Add file" > "Create new file"
2. Type a name "bug_report.json"
```
14. Commit changes using web interface
```
Click on "Commit new file"
```
15. Modify "bug_report.json" using web interface by adding bug report info in JSON format.
```json
{
	"ID" : 456,
	"Severity" : "Trivial",
	"Priority" : "Medium",
	"Title" : "The Sign in button is misaligned in Firefox",
	"Steps To Reproduce" :
		{
			"First" : "Open the app in any browser",
			"Second" : "Click on Sign in"
		},
	"Expected Result" : "The Sign in button is center-aligned with the Username and Password input fields",
	"Actual Result" : "The Sign in button is displayed on the left side of the form"
}
```
16. Commit changes using web interface
```
Click on "Commit changes"
```
17. Synchronize your remote JSON repository with the local one.
```bash
git pull
```

## XML
1. Create a remote repository named XML
```
1. Go to your GitHub Profile
2. Click on Repositories > New
3. Type a name XML and select Initialize this repository with a README.
4. Click Create repository
```
2. Clone XML repository to your local computer
```
1. Go to created repository page
2. Click on Code button
3. Copy HTTPS link
4. Launch Git Bash from your computer
5. Write
git clone https://github.com/tori-cane/XML.git
```
3. In your local XML repository create a new file named "new.xml"
```bash
cd XML
```
```bash
touch new.xml
```
4. Add file to the Git staging area
```bash
git add new.xml
```
5. Save changes (commit) to the local repository
```bash 
git commit -m "new file added"
```
6. Upload (push) local repository content to a remote repository
```bash
git push
```
7. Edit the contents of "new.xml" by adding information about yourself (full name, age, number of pets, desired salary etc.)
```
vim new.xml
i (edit)
 ```
 ```xml
<shortBio>
		<name> 
			<firstName> Victoria</firstName>
			<lastName> Vasylieva</lastName>
		</name>
		<age>27</age>
		<languages>  
			<ukrainian>native</ukrainian>
			<english>fluent</english>
			<ukrainian>beginner</ukrainian>
		</languages>
		<nationality>Ukrainian</nationality>
		<phoneNumber>2893985466</phoneNumber>
		<city>Kyiv</city>
		<gender>female</gender>
		<drivingLicense>Yes</drivingLicense>
		<height>182</height>
		<children>no</children>
		<pets>no</pets>
</shortBio>
```
```
:wq - save and close the editor
```
8. Update the remote branch with local commits
```bash
git add new.xml
```
```bash
git commit -am "updated info in new.xml"
```
```bash
git push
```
9. Create a new file named "preferences.xml"
```bash
touch preferences.xml
```
OR
```bash
cat > preferences.xml
```
10. Edit the contnents of "preferences.xml" by adding info about your preferences (favorite movie, favorite tv series, favorite food, favorite season, favorite travel destination etc.)
```
vim preferences.xml
i (edit)
```
```xml
<preferences>
	<favoriteMovie>Forrest Gump</favoriteMovie>
	<favoriteFlower>Protea</favoriteFlower>
	<favoriteBeverage> 
		<hot>Green Tea</hot>
		<cold>Lemonade</cold>
	</favoriteBeverage>
	<favoriteMusic>Mozart</favoriteMusic>
	<favoriteBook>Faust</favoriteBook>
	<favoriteSeason>Spring</favoriteSeason>
	<favoriteCities>
		<USA>New York</USA>
		<GreatBritain>Bristol</GreatBritain>
		<Italy>Rome</Italy>
		<Spain>Barcelona</Spain>
	</favoriteCities>
</preferences>
```
```
:wq - save and close the editor
```
11. Create a new file named "skills.xml" and add information about a skill set obtained on this course
```
vim skills.xml
i (edit)
```
```xml
<skills>
	<testingFundamentals>
		<topic>SDLC</topic>
		<topic>STLC</topic>
		<topic>Bug Lifecycle</topic>
		<topic>Requirements Analysis</topic>
		<topic>Test Design Techniques</topic>
		<topic>Scrum development process</topic>
		<topic>Testing Methods</topic>
		<topic>Network Principles</topic>
	</testingFundamentals>
	<tools>
		<bugTrackingSystem>Jira</bugTrackingSystem>
		<testManagementTool>TestRails</testManagementTool>
		<QAAutomationTool>Selenium WebDriver</QAAutomationTool>
		<APITesting>Postman</APITesting>
	</tools>
	<languages>
		<language>Python</language>
		<language>SQL</language>
	</languages>
</skills>
```
```
:wq - save and close the editor
```
12. Push "preferences.xml" and "skills.xml" to the remote repository in a single commit
```bash
git add
```
```bash
git commit -m "added skills.xml amd preferences.xml"
```
```
git push
```
13. Create a new file named "bug_report.xml" using Git web interface
```
1. Go to remote repository using web interface and click on "Add file" > "Create new file"
2. Type a name "bug_report.xml"
```
14. Commit changes using web interface
```
Click on "Commit new file"
```
15. Modify "bug_report.xml" using web interface by adding bug report info in XML format.
```xml
<bugReport>
	<id>456</id>
	<severity>Trivial</severity>
	<priority>Medium</priority>
	<title>The Sign in button is misaligned in Firefox</title>
	<stepsToReproduce>
		<first>Open the app in any browser</first>
		<second>Click on Sign in</second>
	</stepsToReproduce>
	<expectedResult>The Sign in button is center-aligned with the Username and Password input fields</expectedResult>
	<actualResult>The Sign in button is displayed on the left side of the form</actualResult>
</bugReport>

```
16. Commit changes using web interface
```
Click on "Commit changes"
```
17. Synchronize your remote XML repository with the local one.
```bash
git pull
```

## TXT
1. Create a remote repository named TXT
```
1. Go to your GitHub Profile
2. Click on Repositories > New
3. Type a name TXT and select Initialize this repository with a README.
4. Click Create repository
```
2. Clone TXT repository to your local computer
```
1. Go to created repository page
2. Click on Code button
3. Copy HTTPS link
4. Launch Git Bash from your computer
5. Write
git clone https://github.com/tori-cane/TXT.git
```
3. In your local XML repository create a new file named "new.txt"
```bash
cd TXT
```
```bash
touch new.txt
```
4. Add file to the Git staging area
```bash
git add new.txt
```
5. Save changes (commit) to the local repository
```bash 
git commit -m "new file added"
```
6. Upload (push) local repository content to a remote repository
```bash
git push
```
7. Edit the contents of "new.txt" by adding information about yourself (full name, age, number of pets, desired salary etc.)
```
vim new.txt
i (edit)
 ```
 ```txt
Name: 
	First Name:  Victoria,
	Last Name: Vasylieva
Age:  27,
Languages:  
	Ukrainian: Native,
	English: Fluent,
	Ukrainian: Beginner
Nationality: Ukrainian,
Phone Number: 2893985466,
City: Kyiv,
Sex: Female,
Driving License: Yes,
Height (cm): 182,
Children: No,
Pets: No
```
```
:wq - save and close the editor
```
8. Update the remote branch with local commits
```bash
git add new.txt
```
```bash
git commit -am "updated info in new.txt"
```
```bash
git push
```
9. Create a new file named "preferences.txt"
```bash
touch preferences.txt
```
OR
```bash
cat > preferences.txt
```
10. Edit the contnents of "preferences.txt" by adding info about your preferences (favorite movie, favorite tv series, favorite food, favorite season, favorite travel destination etc.)
```
vim preferences.txt
i (edit)
```
```txt
Favorite Movie: "Forrest Gump",
Favorite Flower: Protea,
Favorite Beverage: 
	Hot: Green Tea,
	Cold: Lemonade
Favorite Music: Mozart,
Favorite Book: "Faust",
Favorite Season: Spring,
Favorite Cities:
	USA: New York,
	Great Britain: Bristol,
	Italy: Rome,
	Spain: Barcelona
```
```
:wq - save and close the editor
```
11. Create a new file named "skills.txt" and add information about a skill set obtained on this course
```
vim skills.txt
i (edit)
```
```txt
Testing Fundamentals: SDLC, STLC , Bug Lifecycle, Requirements Analysis, Test Design Techniques, Scrum development process, Testing Methods, Network Principles
Tools:
	Bug Tracking Systems: Jira,
	Test Management Tools: TestRails,
	QA Automation Tools: Selenium WebDriver,
	API Testing: Postman

```
```
:wq - save and close the editor
```
12. Push "preferences.txt" and "skills.txt" to the remote repository in a single commit
```bash
git add
```
```bash
git commit -m "added skills.txt amd preferences.txt"
```
```
git push
```
13. Create a new file named "bug_report.txt" using Git web interface
```
1. Go to remote repository using web interface and click on "Add file" > "Create new file"
2. Type a name "bug_report.txt"
```
14. Commit changes using web interface
```
Click on "Commit new file"
```
15. Modify "bug_report.txt" using web interface by adding bug report info in TXT format.
```txt
ID: 456
Severity: Trivial
Priority: Medium
Title: The Sign in button is misaligned in Firefox
Steps To Reproduce:
	First: Open the app in any browser
	Second: Click on Sign in
Expected Result: The Sign in button is center-aligned with the Username and Password input fields.
Actual Result: The Sign in button is displayed on the left side of the form.

```
16. Commit changes using web interface
```
Click on "Commit changes"
```
17. Synchronize your remote TXT repository with the local one.
```bash
git pull
```
