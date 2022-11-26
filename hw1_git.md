### 👉 *S T A R T* 💙💛
##### *1. Создайте текстовый файл как в первом ДЗ по Terminal*
##### *2. Сценарий перенесите в этот файл*
##### *3. На против каждого действия - напишите команду в GitBash*
### *J S O N*
***
#### *4. Создать внешний репозиторий c названием JSON*
- **github.com --> section Repositories --> click on the NEW button --> write JSON in the Repository name field --> mark as Public --> click on the Create repository button**
***
### *5. Клонировать репозиторий JSON на локальный компьютер*
- **git clone** git@github.com:Lyubovneon/JSON.git
***
### *6. Внутри локального JSON создать файл “new.json”*
- **cd JSON**
- **touch new.json**
- **ls -la**  -  to see JSON content 
***
### *7. Добавить файл под гит*
- *git add new.json*
***
### *8. Закоммитить файл*
- **git status**
- **git commit -m "add new.json"**
***
### *9.Отправить файл на внешний GitHub репозиторий*
- **git push**
***
### *10.Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON*
- **vim new.json**
- **insert**
 {
    "person":"Lyubov Nekroyenko",
	"age": "30",
	"pets": "2",
	"salary":"3000"
    }
- **Esc:wq**
- *cat new.json*  - to see the new.json content in gitbash
***
### *11.Отправить изменения на внешний репозиторий*
- **git commit -m** "modify new.json"
- **git push**
***
### *12. Создать файл preferences.json*
- **touch preferences.json**
- **ls -la**  -  to see JSON content
***
### *13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON*
- **vim preferences.json**
- **insert**
{
 "Movie": "The Bodyguard",
 "Serial": "The Software Testing Manual Journey",
 "Food": "Apples",
 "Season": "Spring",
 "Country": "USA"
}
- **Esc:wq**
- *cat preferences.json*  - to see the preferences.json content in gitbash
***
### *14.  Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON*
- touch skills.json
- **vim preferences.json**
- **insert**
{
 "1.": "Bug Tracker JIRA, Mantis",
 "2.": "Test tracker TestLink",
 "3.": "Test documentations Test Plan, Test case, Test Suite, Check list, Bug report"
 "4.": "Testing Methods, Types of Testing, Software Test Design Techniques, SDLS(System Development Life Cycle), STLC"
 "5.": "Agile methodology SCRUM, KANBAN"
 "6.": "Client-Server Architecture Basics"	
 "7.": "SQL DML, DDL",
 "8.": "HTTP methods",
 "9.": "Response STATUS codes"	
 "10.": "API REST, SOAP",
 "11.":	"POSTMAN",
 "12.": "Devtools Chrome",
 "13.": "GITHUB, GITBASH", 
 "14.": "POSTMAN",
 "15.": "JSON, XML basic, structure"
 "16.": "Google Sheets"
 "17.": "Visual Studio code basics"
 "18.": "Mobile testing"
 "19.": "SNAGIT, Lightshot, Bandicam"	
 "20.": "html, css, JavaScript basics"
 "21.": "Taking, uploading and reading Logs"	
}
**Esc:wq**
- *cat skills.json*  - to see the skills.json content in gitbash
***
### *15. Отправить сразу 2 файла на внешний репозиторий*
- **git add preferences.json skills.json**
- **git commit -m** "add preferences.json skills.json"
- **git push**
***
### *16. На веб интерфейсе создать файл bug_report.json*
- **github.com --> drop down menu --> Your Repositories --> click on the JSON Repository --> click on add file dropbox --> Create new file --> write bug_report.json in the name field **
***
### *17. Сделать Commit changes (сохранить) изменения на веб интерфейсе*
- **--> write the title in the Commite new file field --> click on the Commit new file button**
***
### *18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON*
- **click on the dropbox--> edit this file -->**
{
 "ID": 110920221,
 "Date submited": "18.11.2022"
 "Date updated": "______"
 "Title": "Fields are shown without required identification",
 "Assigned to": "@ivanov222"
 "Resolution": "opened"
 "Status": "assigned" 
 "Invironment": "Microsoft EdgeVersion 105.0.1343.27 (64-bit) OS Windows OS Version 10x64",
 "Reporter": "@lyubovneon"
 "STR": {
    "STR1": "Open the http://itcareer.pythonanywhere.com",
    "STR2": "Pay attention to the browser tab."
         },
  "AR": "Fields are shown without required identification.",
  "ER": "Required fields are shown marked *(asterisk).",
  "Severity": "major",
  "Priority": "high",
  "Attachments": {
    "Attachment1": "link_video",
    "Attachment2": "link_screenshort"
                  }
}
***
### *19. Сделать Commit changes (сохранить) изменения на веб интерфейсе*
- **--> write the title in the Commite changes field --> click on the Commit changes button**
***
### *20. Синхронизировать внешний и локальный репозиторий JSON*
-**git pull**
###  *F I N I S H* 👈








