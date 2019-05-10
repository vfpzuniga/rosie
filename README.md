# <img src="rosie-jetsons.jpg" alt="drawing" height="50"/> ROSIE

> Rosie is the Jetsons' household robot. Rosie does all the housework

Script that manages your project CHANGELOG.
 
Changelog files created by Rosie (and those which she can deal with) are those which format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

As done with python, you can add Rosie's root directory to your PATH and used it as a CLI to manage any project's changelog


## Commands

To follow [Keep a Changelog](https://keepachangelog.com/en/1.0.0/) standard, Rosie understands the following commands:

 - **add** 
 - **change**
 - **deprecate**
 - **remove**
 - **fix**
 - **security**
 
 
 Each of the above includes in the current *Unreleased* section a line with the given message in the specific-change subsection
  
 
 She also understands : 
 
  - **init**: creates a new changelog file (optionally can provide base_tag)
  - **release**: closes the current *Unreleased* tag with the specified version and the current date
  - **diff**: prints all changes in *Unreleased* section
 
 
## Optional Parameters
By default Rosie tries to edit a CHANGELOG.md file in the current directory
 
If you want to change this, she offers the following optional parameters
 
 - `--dir <directory>`
 - `--file <filename>`
  
## Help
 For further help you can always ask her for help with `--help` or `-h`!
 
