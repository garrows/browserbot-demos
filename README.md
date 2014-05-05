Browser Bot Demos
=================

Demos of Johnny-Five running in a Chrome App

More docs and demos to come...


Getting Started
---------------

```sh
cd maindemo
npm install
browserify --ignore-missing demo.js -o bundle.js
google-chrome --load-and-launch-app=`pwd`

```

If the _google-chrome_ command doesn't work, try the following

1. Open up a new tab
2. Type chrome://extensions/ in the address bar
3. Click 'Load unpacked extension...'
4. Find the maindemo folder and select it
5. Click the launch link under the new app
