Swift Browser
=============

JavaScript based UI for OpenStack Swift.

Deployment
----------

To deploy the Swift browser, you first need to pull in the
dependencies. These are managed using [Bower][], as client-side
dependency manager. You run Bower via [npm][]:

    $ npm install

This will install Bower and other tools needed in the `node_modules`
folder (everything is installed locally). It will then run `bower
install` for you to download AngularJS and other libraries needed.

When the command is done, the `app/` folder will be ready for upload.
Simply upload it to your Swift installation and load the `index.html`
page in your browser. Provided you have read access to Swift, you
should see a container listing and be able to browse the containers
and pseudo-directories.

Other Swift File Managers
-------------------------

* [Swift Explorer][]: implemented in Java.

* [django-swiftbrowser][]: implemented in Python using Django.

* [swift-ui][]: implemented in JavaScript using Backbone.js

[Bower]: http://bower.io/
[npm]: https://www.npmjs.org/
[Swift Explorer]: http://www.619.io/swift-explorer
[django-swiftbrowser]: https://github.com/cschwede/django-swiftbrowser
[swift-ui]: https://github.com/fanatic/swift-ui
