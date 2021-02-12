# AuthSystem
User Login and Registration Application. Built using ASP.Net Core MVC & Identity.

## The following technologies have been used in the project:

### ASP.NET MVC – Entity Framework – LocalDB
- Registration, login,
- Views, partial views

### Configuration:

- For correct configure of this application your need to download the source code, unzip it and open via Visual Studio.
- Please find the appsettings.json file and open it. after that please find the Connection String:
                                              "ConnectionStrings": {
                                              "AuthSystemDBContextConnection": "YOUR_SERVER_NAME";Database=AuthSystemDB;Trusted_Connection=True;MultipleActiveResultSets=true"
where "YOUR_SERVER_NAME" should be replaced by your local server name.

After that please, open Package Manager Console.
- Tools => Nuget Package Manager => Package Manager Console.

In Package Manager Console  window, please enter the command below.
- Add-Migration "Initial-Create"

When the console return the info "Build succeeded." then please enter command:
- Update-Database.

If Add migration return any error message please use command:
Remove-Migration" and start once again with "Add-Migration" command.

### Run application:
 
Please build the application via Visual Studio using combination of keys (Ctrl+Shift+B) or using VS menubar:
- Build => Bulid.

After that please run application in Debug mode using "Ctrl+F5" combination or just by clicking play.

### If you have any questions or suggestions please contact me via e-mail:
contact@maciejwolejszo.pl
