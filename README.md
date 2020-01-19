#### nh-pdf-downloader
# nhentai PDF Downloader
> Downloads and coverts any doujin/manga from nhentai to PDF

## Installation
#### Clone
- Clone this repo to your local machine using ```https://github.com/TacoAnime69/nh-pdf-downloader```
#### Setup
> update and install packages
```
$ pip3 install --upgrade pip
$ pip3 install -r requirements.txt
```
#### Build
> Use Pyinstaller to build
```
$ pip install pyinstaller
$ pyinstaller __main__.py
```

## Running the Script
> Navigate to the repo directory on your local machine. Then execute the following:
```
$ python3 __main__.py
```

## Running the build
_Windows_
> Navigate to the dist directory ```cd dist\__main__\```
```
$ __main__.exe
```
_MacOS or Linux_
> Navigate to the dist directory ```cd dist/__main__/```
```
$ __main__.out
```
> __This might not be accurate. I'll check this later__

## Usage
* Use the doujin ID number (which can be found in the URL; for instance, ```152969```).
* Enter that number when prompted.
* The program will download and covert all images into a pdf and save it in a subfolder where the python script is.
```
- nh-pdf-downloader/
    - hentai/
        - example1.pdf
        - example2.pdf
    - __main__.py
```
> _Note: as the images are being downloaded, a temporary folder is created to store the images. this folder will be deleted upon completion._
* When you are done, enter ```done``` to exit script

## Bug Reporting
When reporting a bug, please include the following information:
- Your OS and Python Version
- What did you enter (even if it's just the number, please provide that. Don't worry, I won't judge)
- How did you enter it (via typing, copy-paste, etc.)
- (_Optional_) A screenshot of your terminal/cmd
#### Known Bugs
> Currently, no bugs have been reported. 1/18/19

## Feature Request and Planned Features
Feel free to request features. 
#### Planned Features
- [x] Enter multiple numbers at once (and let the script download all)
- [ ] Create a config file that would allow the user to specify an output folder (and call it whatever they want)
- [ ] Add CBR/CBZ support
- [ ] Add config for automatically putting downloaded PDF into a subfolder named after its parody, author, or language.
#### Considering
> Features that will be added if enough people request them
- A simple user interface
- A Google Chrome / Firefox / Edge extension that would connect the script and direct download from the page

## Contributing
> I'm relatively new to GitHub, but please feel free to contribute. Something about fork and pull request... I'll figure it out eventually!

## Support
Feel free to reach out if you have any questions!
> If you want to report a bug, please read __Known Bugs__ and only use email.
- Email: hentai.boi@outlook.com
- Twitter at [@TacoAnime69](https://twitter.com/TacoAnime69)
