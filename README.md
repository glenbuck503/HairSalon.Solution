# Hair Salon

<div align="center">
<img src="https://github.com/glenbuck503.png" width="200px" height="auto" >
</div>
<br>
<br>
<br>

#### 

#### By Glen Buck

## Description
This application will let users add stylists to the salon and also let stylists add clients. Users can also add themselves as a client to a certain stylist as long as they are in the list to begin with. Otherwise, they will have to add the stylist.Users will also be able to see a list of clients that belong to that certain stylist.

## Setup/Installation Requirements

- Go to https://github.com/glenbuck503/HairSalon.Solution
- Go to the middle upper right corner where the green box that says "Code" and click it.
- Copy the HTTPs site to your clipboard.
- Open terminal or bash and get to the directory you want to download the repo to.
- Type into the terminal "git clone command + v if using Mac or control + v is using a PC" and press enter.
- You will need to download and install .NET Core. Here is a link for you to do that : https://dotnet.microsoft.com/download
- After installing, open your terminal and navigate to the project folder (HairSalon.Solution).
- To Run tests:
  - Navigate (from the Root directory of the project) to the Bakery.Tests direcytory by typing in " cd Bakery.Tests ". Then in your terminal you will type in "dotnet restore" to restore any of th .csproj files in there, and then type in "dotnet test".
- To run the program in your terminal, navigate back to the root directory (HairSalon.Solution).
- Navigate to the VendorAndOrder directory by typing in " cd VendorAndOrder ". Now in the terminal type in "dotnet restore" to restore any .csproj files in there. Now type in "dotnet run" and the program will run.
- You will have to create a seperate JSON file in your production folder (HairSalon.Solution/HairSalon) and name it appsettings.json, by navigating to the root directory of the Hair Salon project and then type in the terminal "touch appsettings.json". After doing so, you will navigate to VS code and find the appsettings.json file in the file tree and copy and paste this info into the file :

{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=glen_buck;uid=root;pwd=[password-here];"
  }
}

* note that you will need to replace the "password-here" with your own password.

- You will then need to import hte scehma in MySQL WorkBench. First open WorkBench


## No known bugs as of 3/14/2021

## Support and contact details

For contact support, please email Glen Buck <a href = "mailto: glenbuck@gamil.com">Send Email</a>

## Technologies Used

- VS Code
- Git
- MS Tests
- MS Build
- CSS
- ASP.NET MVC
- Razor
- Entity Framework


### License

232323.44.988.

Copyright (c) 2021 Glen Buck Inc.
