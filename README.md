# Bear-like CSS for Roam (Chrome)

A custom hack Roam theme (for Chrome) inspired by the Bear note-taking app.

There are only 13 lines that have changed - see numbered comments in css. You may want to adjust "changed" lines based on your screen size, font, and font size preferences.


Installation notes below.

![roam bear theme screenshot](https://raw.githubusercontent.com/apg-dev/roam-theme-bear/master/roam-bear-theme.png)


## Installation

* Create new folder on your machine (e.g. Roam-css) and download site.css into that folder
* Open Roam in Chrome, display developer tools (F12)
* Select Sources > Overrides
* Select folder for overrides > Choose the new folder (e.g. Roam-css)
* Allow (when prompted "DevTools requests full access to ...")
* Go into Elements tab and change any item (e.g. body > font-size: 15px)
* Page may flicker - just refresh the page
* You now have a new folder in Roam-css
* Go into that new folder: roamresearch.com/assets/css/less-compile
* Replace the site.css file with the site.css file you downloaded from git
* Refresh Roam page 

## Usage

* Changes will persist through browser refresh
* When opening a new tab, F12 > Refresh page will load up styling
* To make any additional css changes, simply edit site.css, save, then refresh Roam page
* To remove this custom hack (and go back to Roam default), F12 > Sources > Overrides > Right-click folder > Remove folder form workspace > Refresh page



## Other Notes

* Obviously whenever Roam makes an update to their site.css, my hacked site.css file would need to be updated accordingly.
* Likewise if Roam changes the directory structure of their CSS
* If you don't have Avenir Next fonts local on your machine, you'll need to add an import line or change the two Avenir Next references to a local font you prefer.


---


Enhancements to this theme welcomed and appreciated.
