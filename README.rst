My Sublime Text 3 Preferences
-----------------------------

* Install Sublime Text 3 - http://www.sublimetext.com/3

    sudo add-apt-repository ppa:webupd8team/sublime-text-3 -y
    sudo apt-get update -y
    sudo apt-get install sublime-text-installer -y

* Install Sublime Package Control - https://sublime.wbond.net/installation

* Clone this repo::

    $ cd ~/.config/sublime-text-3/Packages
    $ rm -Rf User
    $ git clone git@github.com:ipedrazas/sublimetext-settings.git User

* Install these packages using ``Sublime Package Control``:
 * ``Theme - Spacegray`` Quite more appealing theme
 * ``GitGutter`` Show +- close to each line number
 * ``Gist`` Create gists form the editor
 * ``SideBarEnhancements`` File/Folder actions in the sidebar
 * ``LESS`` Less highlighting
 * ``Hex​Viewer`` Hex​ view/edits
 * ``INI`` INI syntax highlighting
 * ``GitHubinator`` Github helpers (blame, compare..)
 * ``SublimeLinter`` Lint your code!
 * ``SublimeLinter-pep8`` Use pep8 as lint
 * ``SublimeCodeIntel`` Code autocomplete

TODO: script that installs all the plugins
