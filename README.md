# [PhantomJS](http://phantomjs.org) - Scriptable Headless WebKit

PhantomJS ([www.phantomjs.org](http://phantomjs.org)) is a headless WebKit scriptable with JavaScript or CoffeeScript. It is used by hundreds of [developers](https://github.com/ariya/phantomjs/wiki/Buzz) and dozens of [organizations](https://github.com/ariya/phantomjs/wiki/Users) for web-related development workflow.

# This is a specific, custom build of PhantomJS 

PhantomJS 1.9.7 has a bug in the webserver module where headers are treated as case sensitive.  This was causing issues.  The bug has been fixed, but the fix has not been included in 1.9x, so the bug will remain until 2.0.  This build is the 1.9.7 branch with the fix on top.  In theory this should not need maintanance, because when it (hopefully quickly) gets out of date, the new version (>=2.0) will already include the bugfix.

Without further ado, there are binaries for
- [Linux](https://raw.githubusercontent.com/jaredp/phantomjs/master/bin/phantomjs-1.9.8.custom-linux)
- [Mac OS](https://raw.githubusercontent.com/jaredp/phantomjs/master/bin/phantomjs-1.9.8.custom-mac)


## PhantomJS Questions?

- Explore the complete [documentation](https://github.com/ariya/phantomjs/wiki)
- Read tons of [user articles](https://github.com/ariya/phantomjs/wiki/Buzz) on using PhantomJS.
- Join the [mailing-list](http://groups.google.com/group/phantomjs) and discuss with other PhantomJS fans.

PhantomJS is free software/open source, and is distributed under the [BSD license](http://opensource.org/licenses/BSD-3-Clause). It contains third-party code, see the included `third-party.txt` file for the license information on third-party code.

PhantomJS is created and maintained by [Ariya Hidayat](http://ariya.ofilabs.com/about) (Twitter: [@ariyahidayat](http://twitter.com/ariyahidayat)), with the help of [many contributors](https://github.com/ariya/phantomjs/contributors).

