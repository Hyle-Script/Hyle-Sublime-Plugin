# [Hyle](http://hyle.io) Sublime Text Package

This package is designed to help reading and writing `.hyle` files. It’s really basic for the moment as it is only a fork of the YAML package.

## Installation

### via Package Control

> This is the recommended installation method.

If you have Sublime Package Control, you know what to do. If not, well: it's a package manager for Sublime Text 2; it's awesome and you can [read about it here](http://wbond.net/sublime_packages/package_control).

To install Package Control, open the Python Console (`ctrl+'` or ``cmd+` ``) and paste the following into it:

    import urllib2,os; pf='Package Control.sublime-package'; ipp=sublime.installed_packages_path(); os.makedirs(ipp) if not os.path.exists(ipp) else None; urllib2.install_opener(urllib2.build_opener(urllib2.ProxyHandler())); open(os.path.join(ipp,pf),'wb').write(urllib2.urlopen('http://sublime.wbond.net/'+pf.replace(' ','%20')).read()); print 'Please restart Sublime Text to finish installation'

After installing the package and restarting the editor:

- Open the Command Pallete (`ctrl+shift+P` or `cmd+shift+P`).
- Type "Install Package" and hit return.
- Type "Hyle" and hit return.

### via Source Control

> If you plan to contribute, then you should install via this method. Otherwise it is recommended that you install the package via Package Control, see above.

Sublime stores packages in the following locations:

  - Nix: ~/.config/sublime-text-2/packages
  - Mac: ~/Library/Application\ Support/Sublime\ Text\ 2/Packages
  - Win: %APPDATA%\Sublime Text 2\Packages

Open a Terminal/Console and run the following commands, replacing `PACKAGE_PATH` with the path corresponding to your OS above.

    cd PACKAGE_PATH
    git clone https://github.com/Hyle-Script/Hyle-Sublime-Plugin.git Hyle

## Todos
 
- [ ] Autocompletions à la CSS
- [ ] Specific highlighting specific to Hyle and After Effects keywords
