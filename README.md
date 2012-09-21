CPGuides
========

### For lib authors

* Don’t require header editing for configuration. Instead use properties at runtime or a var like CocoaLumberjack does.
* Don’t use prefix headers.


### For CP users

* If your project is kept in SVN and you want to check-in the `Pods` directory (because you don’t want to force others to use CP), you will run into issues with the header dirs being removed and thus the `.svn` dirs being removed too. As a workaround use git-svn. See https://github.com/CocoaPods/CocoaPods/issues/247.