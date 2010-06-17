Palm webOS TextMate bundle
==========================


Installation
------------

Palm SDK path to binaries must be added to your system environment PATH. If not, add it to your ~/.profile:

    # Add PalmSDK bin path to PATH variable
    export PATH=/opt/PalmSDK/0.1/bin:$PATH

To install via Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/devilx/palm-webos-development-tmbundle.git "Palm webOS.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

To install without Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    wget http://github.com/devilx/palm-webos-development-tmbundle/tarball/master
    tar zxf devilx-palm-webos-development-tmbundle*.tar.gz
    rm devilx-palm-webos-development-tmbundle*.tar.gz
    mv devilx-palm-webos-development-tmbundle* "Palm webOS.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'
		
Source can be viewed or forked via GitHub: [http://github.com/devilx/palm-webos-development-tmbundle/tree/master](http://github.com/devilx/palm-webos-development-tmbundle/tree/master)