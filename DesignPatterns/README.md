<img src="assets/" alt="Design Patterns" style="width: 215px;" align="right">

# Design Patterns | Go | Quickstarts

## Common Folders

- **cmd** - Main entry point of the application
- **pkg** - Has code that might be used by external applications
- **internal** - Private code and libraries that cannot be accessible by external applications
- **vendor** - App dependencies. Created by `go mod vendor` command. Usually not commited to a repo but some keep it as a backup
- **api** - Typically contains the of the application's REST API.
  - Swagger speficiations
  - Schema
  - Protocol definition files
- **web** - Contains specific web assets and application components
- **configs** 
  - Config files
  - or `confd`
  - or `consul-template`
- **init** 
  - System initiation (start)
  - Process management (stop/start) scripts
  - With supervisor configurations
- **scripts** - For performing various activities (helps with keeping *makefile* small and tidy): 
  - Builds
  - Installations
  - Analyses
  - Operations
- **build** - For packaging and continuous integration
- **deployments** (or **deploy**) - For configurations and templates related to the system and container orchestration
- **test** - This is another way to store your tests. This way is putting all the tests in the same directory and the second is to keep the test files alongside the code files.

> **Note:** Name directories that clearly indicate what is contained inside.
>
> Avoid `snake_case` and `camelCase`.
>
> 
