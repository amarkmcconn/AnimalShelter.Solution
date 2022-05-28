# Animal Shelter 🐶😺

## By _Mark McConnell and Evgeniya Meshuris_ 

### _This is an MVC application for an animal shelter to track the animals in their facility based on animal type (such as cat or dog)._

## Technologies Used 🖥️

* _C#_
* _.Net 5.0_
* _HTML_
* _CSS_
* _Git_
* _VsCode_
* _EntityFrameWork_
* _REPL_
* _MySQL WorkBench_

## Description ✅

_This is an MVC application an animal shelter to track the animals in their facility based on animal type (such as cat or dog). Included features that let a shelter worker: Add types of animals to the system. type should be a column on the animals table. A type could be a cat, dog, bunny or any other animal. Add an animal to the system. An animal should have a name, gender, date of admittance, and breed. When it gets added to the system, it should be added as a particular type.
List animals type alphabetically._

## Setup/Installation Requirements 🖊️

* _Clone this repo: <https://github.com/amarkmcconn/AnimalShelter.Solution>_
* _Enter the new directory using the command ```cd AnimalShelter.Solution```_
* _In the root directory, confirm there is a .gitignore file_
* _add: 
```
*/obj,
*/bin
*.vscode
*/appsettings.json
```
 to the .gitignore file. It will keep your repository clean of unnecessary files and protect your database from unauthorized access_
* _Create an appsetting.json file at the root directory_*
* Open the appsetting.json file and enter:
```
{ 
  "ConnectionStrings": { 
    "DefaultConnection": "Server=localhost;Port=3306;database=[Database-Name];uid=root;pwd=[Your-Password;" 
  } 
}
```

* _run ```git add .gitignore```
* _commit your changes_
* _To ensure the project will run correctly,_
* _Download MySQL WorkBench_
* _Open MySQL WorkBench and In the Navigator > Administration window, select Data Import/Restore_
* _In Import Options select Import from Self-Contained File_
* _You will use .sql file type that is located the root directory ```AnimalShelter.Solution```._
* _Navigate to the tab called Import Progress and click Start Import at the bottom right corner of the window._
* _After you are finished with the above steps, reopen the Navigator > Schemas tab. Right click and select Refresh All._
* _run ```dotnet restore``` and ```dotnet build``` from the AnimalShelter directory_
* _run ```dotnet add package Microsoft.EntityFrameworkCore -v 5.0.0```_
* _run ```dotnet add package Pomelo.EntityFrameworkCore.MySql -v 5.0.0-alpha.2```_
* _run ```dotnet add package Microsoft.EntityFrameworkCore.Proxies -v 5.0.0```_
* _To interact with the local host website navigate to the AnimalShelter directory and run ```dotnet run```_
* _click on  <http://localhost:5000>_

## Known Bugs 🐛

* _No Known Issues_

## License

[MIT](LICENSE) 👈

_If you run into any issues or have questions, ideas, or concerns;  please email me: at mark.programming1@gmail.com or make a contribution to the code._

Copyright (c) 2022 Mark McConnell
