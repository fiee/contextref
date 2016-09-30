# contextref

ConTeXt command reference (JS interface to xml interface files)

## Setup

* Install current ConTeXt minimals (see http://wiki.contextgarden.net)
* Get Webix library (GPL version) from http://webix.com/download-webix-gpl/
* Unzip `webix.zip`
* Symlink ConTeXt interface files:

    ln -s $TEXROOT/texmf-context/tex/context/interface/ interface

Run `index.html` with any webserver, 
e.g. the server script included in the ConTeXt distribution:

    mtxrun --script server --port 8080 --start

Now you can open `http://localhost:8080` in your browser.

