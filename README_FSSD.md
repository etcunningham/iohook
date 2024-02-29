# iohook

This package has been modified from the [original iohook package](https://github.com/wilix-team/iohook) to provide keyboard locking functionality.

Several files have been modified from the original package:

- libuiohook/include/uiohook.h
- libuiohook/src/windows/input_hook.c
- src/iohook.cc
- index.js
- package.json
- package-lock.json
- install.js

When the time comes to update this package:

1) Merge in the latest source from the original iohook package
2) Commit that to master
3) Checkout the 'built-version' branch
4) Merge master into the branch
5) Do npm run build
6) Commit that to the 'built-version' branch

This way the built files are always commited to the 'built-version' branch. This is the branch that @fssd/keyboard locker pulls from.
