# Stellar Charts

This is the frontend for charts.stellar.org data visualization using angular.js and D3

##Installation Instructions:

1. Install [node.js and npm](http://nodejs.org/).
2. Install [bower](http://bower.io/)

        $ sudo npm install -g bower
        
2. Install [Grunt](http://gruntjs.com/).

        $ sudo npm install -g grunt-cli
    
3. Install the Stellar Charts frontend.
    
        $ git clone https://github.com/stellar/stellar-charts-frontend
        $ cd stellar-charts-frontend
        $ npm install
        $ bower install
        
4. Copy 'deployment.environments.json.example' into 'deployment.environments.json'
5. Copy 'src/example.config.js' into 'src/config.js' and fill in the options as desired. A URL for the api is required.
6. Change back to the stellar-charts-frontend directory

## Build

1. Run the following command to build the client.    

        $ grunt

2. Navigate your browser to the /build directory for the development version, or to the /bin directory for the compiled version