# unittestingangularjs

Install NodeJS, Bower, AngularJS, Karma, Jasmine, PhantomJS

1. Install NodeJS:
	https://nodejs.org/en/
	
2. Install bower with npm:
	$ npm install bower --save-dev

3. Install AngularJS with npm:
	$ npm install angular --save

4. Install and Config Karma, Jasmine, PhantomJS:
	Install Karma & Phantom with npm:
		$ npm install karma-cli phantomjs -g
		
	Check karma version
		$ karma --version
		
	Check PhantomJS version
		$ phantomjs --version
		
	Install Jasmine with npm
		$ bower install karma jasmine --save-dev
		
	Install angular-mocks
		$ bower install angular --save-dev
		
	Move to karma.conf.js to config some details:
		$ karma init
		
       To start karma:
		$ karma start karma.conf.js

