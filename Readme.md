# Brainwallet Private Key Image based Keyboard / Input Generator

### Run this repo

    python -m SimpleHTTPServer 3000

connect:

<http://localhost:3000>


### Install

    npm i -g bower gulp browserify


    bower install
    npm install

    cd node_modules/bitcore-mnemonic && gulp browser

If it fails, from the same dir, execute:

    npm i --save-dev gulp browserify bitcore-build
    gulp browser

To check, `ls | grep bitcore-mnemonic.min.js` should return 2 files, one of which is `bitcore-mnemonic.min.js`.

### Infos


This is a repo that contains just a private key, image based tool, not a keyboard:


        ---------------------------------------------------------------------
                                    BrainWallet Keyboard
        ---------------------------------------------------------------------
        ||     ||  q  ||  w  ||  e  || ...  ||     ||     ||     ||     |     |
        ---------------------------------------------------------------------
            |     ||     ||     ||     ||     ||     ||     ||     ||     ||
        ---------------------------------------------------------------------
        ||     ||     ||     ||     ||     ||     ||     ||     ||     |     |
        ---------------------------------------------------------------------
            |     ||     ||     ||     ||     ||     ||     ||     ||     ||
        ---------------------------------------------------------------------
        ||     ||     ||     ||     ||     ||     ||     ||     ||     |     |
        ---------------------------------------------------------------------

        ---------------------------------------------------------------------



hmmm.... no :D


### LICENSE

See License for images used
