# Steam Manifests Data Extractor

A simple nodejs script to get an inventory of installed games details by reading the Steam manifest files


### Prerequisites

you will need to install NodeJS https://nodejs.org
this has been tested on windows 10 and Ubunutu 18.04 linux
You may need to edit the your steam install path (line 3 of steammanifest.js) if you did not select the default.

### running
extract the file to your computer and in windows just click on the steammanifests.bat file

or open a command line and cd to the path
```bat
    node steammanifests.js
```

* this will generate two json files in the same folder
* open the table.html file in you browser
* clck on the Open File Button
* select the computername-smfdata.json
* you should see your sortable list of games populate
* click 'Format Steam Manifest Columns CheckBox' to allow addtional filtering
* you can also open the computername-smfpaths.json to show your full paths of steam folders


## Author

* **BitJunky** -  (https://github.com/gigajunky)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* http://tabulator.info/ - a great javascript table spreadsheet commponent

