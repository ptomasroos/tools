###tools
====
**Install.sh** - [golang](http://golang.org) compiler and [liteide](https://github.com/visualfc/liteide) simple installer for Ubuntu.

* **Features**
    * Get and install last versions of go compiler and ide
    * Create a more practical layout for ide (liteide.ini.mini)
    * Lot of gophers use Monaco font so add in ide
    * Also create a GOPATH to the go-programs directory and add a HelloWorld project
    * Add launcher to Unity with some useful functions on right-click. Other DE users have a shortcut on desktop
    * Add git support in ide on `` ctrl+` ``. Be sure you have configured [git](https://help.github.com/articles/set-up-git) before and proper [ssh keys](https://help.github.com/articles/generating-ssh-keys)
* **Using**

    Download anywhere, make it executable and run. If you want to watch the installation process run it in Terminal.

        chmod +x Install.sh
        ./Install.sh

    Run periodicaly or if compiler/ide versions change to update the sistem.
    Projects are not affected if you overinstall.

* **Using git from liteide**

    `` ctrl+` `` will provide a list of git commands

        git add
        git commit -m "-" -a
        git push

    Remember to use commands only if a file from project is open in editor, otherwise will fail.

====

