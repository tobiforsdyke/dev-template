# My Development Template

A sample template structure for my development projects.

## Contains:

- **.gitignore** contains a list of files to be ignored by git
- **Gruntfile.js** contains the grunt tasks to convert SASS, watch for changes and autoprefixer
- **package.json** contains the project information and NPM dependencies
- **README.md** contains this information to be edited according to the project
- **dev-template.zip** the contents of this folder as a zip file

## Instructions:

1. Edit the **package.json** file 'project name', 'description' and 'keywords'. Add git repository in 3 places or delete those parts. Uncomment the git references.

2. Either use this folder as the base folder for the project or copy the 4 files into the actual project folder.

3. Open **Terminal** and navigate to the project folder and type:
```
npm install
```
*This will install the dependencies that are listed in the package.json file and create the node_modules folder.*

4. Edit the **Gruntfile.js** file in 3 places under files and src to specify the correct locations and filename of the .scss and .css files to watch/convert.

5. To start the tasks in the Gruntfile.js file just type:
```
grunt
```
This will start the Grunt task which converts SASS to CSS, watches for changes and autoprefixes the css file.
