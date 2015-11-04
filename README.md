# Cards
> Table extension with cards as cells, developed for product top lists. Responsive design and selection enabled, both click and swipes.

## Purpose and Description

## Screenshots
Compact and full view of Cards extensions
![Alt text](https://github.com/KFredberg/kf-cards/blob/master/img/screenshot_compact_and_full.png?raw=true "Screenshot compact & full view")

## Installation

1. Download the latest version
2. Qlik Sense Desktop
	* To install, copy all files in the .zip file to folder "C:\Users\[%Username%]\Documents\Qlik\Sense\Extensions\Cards"
3. Qlik Sense Server
	* See instructions [how to import an extension on Qlik Sense Server](http://help.qlik.com/sense/en-us/developer/#../Subsystems/Workbench/Content/BuildingExtensions/HowTos/deploy-extensions.htm)

## Configuration
![Alt text](https://github.com/KFredberg/kf-cards/blob/master/img/screenshot_dimensions.png?raw=true "Screenshot compact & full view")

* 1st dimension is the uniqie identifier that will be selected if a card is selected. The identifier won't show up on the card. 
* 2nd dimension is the image and needs a url for source. 
** Example url string: 'http://ia.media-imdb.com/images/M/MV5BMjEyMjcyNDI4MF5BMl5BanBnXkFtZTcwMDA5Mzg3OA@@._V1_UX34_CR0,0,34,50_AL_.jpg'
**Example reference an image from Qlik Sense default repository: '../content/Default/Qlik_default_flower.png'
* 3rd dimension is the title of the card. 
* 4th dimension is optional and will show up under the titel. 

## Contributing
Contributing to this project is welcome. The process to do so is outlined below:

1. Create a fork of the project
2. Work on whatever bug or feature you wish
3. Create a pull request (PR)

I cannot guarantee that I will merge all PRs.

## Author

**Karl Fredberg**
* http://github.com/KFredberg


## Change Log

See [CHANGELOG](CHANGELOG.yml)

## License & Copyright
The software is made available "AS IS" without any warranty of any kind under the MIT License (MIT).

See [Additional license information for this solution.](LICENSE.md)