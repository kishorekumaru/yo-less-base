##Steps to install and run Yeoman based app


###Check and Install the default packages###

1. NodeJS and NPM 
  https://nodejs.org/en/download/ 
  
  This will install Node and NPM in your machine
  to verify its installed run the following command 
  
  `$ node -v`  
  `$ npm -v`

2. Install grunt globally

  `$ npm install -g grunt-cli`
  
3. Install bower globally

  `$ npm install -g bower`
  
4. Install yomean globally

  `$ npm install -g yo`
  
  
###Clone the repository into a new folder###

  `$ git clone https://github.com/kishorekumaru/yo-less-base.git`

###Get into the folder and run the following commands###

  `$ cd yo-less-base`
  
  `$ npm install --save`
  
  `$ bower install --save`
  
###Run the application###
  
  `$ grunt serve`
  
###Build the application###
  
  `$ grunt build`
