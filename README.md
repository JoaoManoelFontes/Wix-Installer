# Wix Installer Project

## This project is a template for creating a Wix installer for a application

### Prerequisites

[DotNet tool (DotNet SDK)](https://dotnet.microsoft.com/download) - For building the project with msbuild

### Building the project

* Clone the repository
* Open the solution
* Modify the project to your needs (Add files, change the name of the application, etc.)
* Build the project:

```
dotnet tool msbuild restore
```

* The installer, by default, will be in the folder: `\bin\Debug\en-US\Package1.msi`

### Installing the msi

* Run the msi file
* The application,  by default, will be installed in the folder: `C:\Program Files (x86)\TestPackage\`
* By default, the application must contain a file called `Project.txt` and other called `Project1.txt` in the installation folder
