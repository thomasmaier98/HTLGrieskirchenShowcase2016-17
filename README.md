[![HTL-Grieskirchen](http://www.htl-grieskirchen.net/fileadmin/bilder/logo.png)](http://htl-grieskirchen.net)
# Showcase 2016-17

### [**List of projects**](https://alfreddoppler.github.io/HTLGrieskirchenShowcase2016-17/)

The projects in this repository are for demonstration purposes only. 
All copyrights and trademarks belong to their rightful owner.
If there is any problem with any demo just leave a short message.

@students:
After uploading your project to the `projects-folder` update the `projects.json`.

## `projects.json` properties
```
[
    {  
        "title": "project title",
        "folder": "name of the folder",
        "author": "my name",
        "year": "folder name of the year",
        "info": "info about your project",
        "status": "0"
    },
    ...
]
```
### title
Project title

### folder
Name of your project folder

### author
Author(s) of the project

### year
Name of the year (must be the same as the year folder directly in the `projects` folder)

### info
(optional) e.g. your project works in specific versions of a browser
### status
| status  | description        |
| ------: | ------------------ |
| -1      | not working        |
| 0       | partly working     |
| 1       | completley working |

## Create new repository (@AlfredDoppler)
Just copy the `index.html`, `app.json` and `projects.json` to the new repository. There create a new folder called `projects` with subfolders named by year (e.g. 2017_SS) and update the `app.json` with the new values.
### That´s it :)