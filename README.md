# netbeans-electron-support
A simple plugin for the NetBeans IDE to launch Electron apps. 

I started to develop this because I was not satisfied with the Node.js plugin and support for Electron apps in NetBeans 8.0.x. However with NetBeans 8.1 this is obsolete because the support for Node.js was enhanced and therefore also for Electron.

[![Build Status](https://travis-ci.org/travis-ci/travis-build.png?branch=master)](https://travis-ci.org/Mario-S/netbeans-electron-support/builds)

## Requirements ##
This plugin assumes you installed [Node.js](https://nodejs.org/en/) and [Electron](http://electron.atom.io/) already.

## Getting started ###
The plugin contains a very simple project template to help you build your first electron app.

The main.js file can be launched from the editor, or via the context menu. The plugin also supports debugging with node inspector.

### Project Layout ####
The directory structure of the enclosed template looks like this:
APP/<br/>
&nbsp;&nbsp;src/<br/>
&nbsp;&nbsp;&nbsp;&nbsp;index.html<br/>
&nbsp;&nbsp;&nbsp;&nbsp;main.js<br/>
&nbsp;&nbsp;&nbsp;&nbsp;package.json<br/>

At the moment the plugin can recognize your project as an Electron application only if it is in this directory structure.
