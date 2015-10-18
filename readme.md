#Skeleton for simple HTML/CSS development ( Compass project )

##Prerequisites

* Node installed
* Gulp installed globally : **npm install gulp -g**
* Homebrew installed
* SASS installed : **sudo gem install sass**
* Compass installed

###Note installing compass

* First install ruby with homebrew to update ruby on Mac OSX to version 2
* Then Execute 
    
     gem update --system
     gem install compass


##Use

* Clone the repo
* Run : **npm install**
* Add your .scss files in the **sass directory**

Init compass project with:

     compass create --bare --sass-dir "sass" --css-dir "css" --javascripts-dir "js" --images-dir "img"

Start gulp on the command line. Pages are served with express middleware. Every time changes are made with *.html 
files or *.scss files, the browser is reloaded automatically.

To view the files on the node express server point the browser to [http://localhost:4000/](http://localhost:4000/)
