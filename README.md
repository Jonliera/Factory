# Dr. Sillystringz's Factory
 

#### By_** Jonathan Liera**_

## Technologies Used

* _C#_
* _Entity Framework Core_
* _Net 6.0 SDK_
* _MySQL
* _Visual Studio Code_
* _Github_
* _Markdown_

## Description

An app that allows the user to input as many engineers and machines as they want. The manager (user) of the factory can manage the relationship between the both. Using a joint table the manager can add as many machines to each engineer and can have as many engineers for a single machine.

## Setup/Installation Requirements

* Clone this repository to your desktop
* Navigate to the HairSalon main directory on your computer
* Install .Net 6 SDK follow the directions to have access to C# and its editor_
* CD into HairSalon file and run dotnet restore to install packages to be able to run the repo
* Add the following two packages to your project: 
  $dotnet add package Microsoft.EntityFrameworkCore -v 6.0.0
  $dotnet add package Pomelo.EntityFrameworkCore.MySql -v 6.0.0 _
* Add the following files to your .gitignore file:
  obj/
  bin/
  appsettings.json _
* Create a file in the project directory with the name appsettings.json _
* Navigate to the appsettings.json and enter the following in your file 
```json
{
    "ConnectionStrings": {
        "DefaultConnection": "Server=localhost;Port=3306;database=jonathan_newfactory;uid=root;pwd=[YOUR-PASSWORD-HERE];"
    }
}  
```
* Input your password for MySQL workbench where it says [YOUR-PASSWORD-HERE] 
* To open the database open your MySQL workbench and under administration select "Data Import" 
* Check the "Import from self contained" file and enter the file path of the datbase within HairSalon and start import.
* Run the program with $dotnet run 

## Known Bugs

* _No known bugs_

## License

_If you have any questions or concerns please contact me @jonliera1@gmail.com. You are also welcome to contribute if you feel you may so.

*_MIT License_

Copyright <Nov 2022> <Jonathan Liera>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE._
