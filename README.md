# ClairesSalon.Solution
#### A webpace to keep track of stylists and clients at a hair salon. 

#### By: Sandra Tena

## Technologies Used

* _C#_
* _.NET_
* _HTML_
* _CSS_
* _SQL Workbench_
* _Entity Framework_
* _MVC_

## Description
####  This is a webpage that will allow a user to input stylists and clients then view those inputs. The user cannot add a client unlessx there is a stylist to assiciate them to and the client list is viewed when the user selects a stylist from the stylist list. Stylists and clients can both be edited and deleted in addition to being created and viewed. 


## Setup/Installation Requirements

<details>
<summary><strong>Initial Setup</strong></summary>
<ol>
<li>Clone the git repository byusing the "git clone" command and including the copied URL. url: https://github.com/SandraT22/ClairesSalon.Solution.git
<li>run $ dotnet restore in the directory: HairSalon
<li>run $ dotnet add package Microsoft.EntityFrameworkCore.Proxies -v 5.0.0
<li>run $ dotnet add package Microsoft.EntityFrameworkCore -v 5.0.0
<li>run $ dotnet add package Pomelo.EntityFrameworkCore.MySql -v 5.0.0-alpha.2
<li>run $ dotnet remove package MySqlConnector
<li>Move onto "SQL Workbench" instructions below to re-create database necessary to run this project.
<br>
</details>

<details>
<summary><strong>SQL Workbench Configuration</strong></summary>
<ol>
<li>Create an appsetting.json file in the "HairSalon" directory of the project.
<li> Insert the following code** : <br>

<pre>{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=best_restaurants;uid=[YOUR-USERID-HERE];pwd=[YOUR-PASSWORD-HERE];"
  }
}</pre>
<small>**note: if you plan to push this cloned project to a public-facing repository, remember to add the appsettings.json file to your .gitignore before doing so.</small>

<li>Once "appsettings.json" file has been created, navigate back to SQL Workbench.
<li>Import the database named "hair_salon" from the root directory of the project.<br><br>
How to Import a Database:
<ol> 
  <li>Open SQL Workbench.
  <li>Navigate to "Administration" tab in SQL Workbench.
  <li>Click "Data Import/Restore".
  <li>Select the radio button "Import from Self-Contained File" and include file path to the sql file of this project you cloned to your machine.
  <li>In "Default Schema to be Imported to" click "New".
  <li>Name the schema "best_restaurants" then click "OK".
  <li>Once named, switch to "Import Progress" tab and click "Start Import".
  <li>If you need further support refer to these resourses: https://www.learnhowtoprogram.com/c-and-net/getting-started-with-c/installing-and-configuring-mysql & https://www.learnhowtoprogram.com/c-and-net/getting-started-with-c/installing-and-configuring-mysql
  
</details>

<details>
<summary><strong>To Run</strong></summary>
Navigate to:  
   <pre>ClairesSalon.Solution
   └── <strong>HaireSalon</strong></pre>

Run ```$ dotnet restore``` in the console.<br>
Run ```$ dotnet run``` in the console
</details>
<br>

## Known Bugs

* No known bugs

## License
MIT
<br>
Copyright (c) 2022 Sandra Tena
## Contact Information
_If you have any questions or concerns, please feel free to reach out to me [via email at: sandratena06@gmail.com](mailto:sandratena06@gmail.com) or request to make a contribution. Thank you!_ 