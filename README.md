# lerna sample

npm install -g lerna lerna-changelog

lerna init

cd package/core

npm init

cd package/sub-a

npm init

lerna bootstrap

lerna add _package_

```
~/Desktop/opensource/lerna-starter/packages/sub-a lerna add axios
lerna notice cli v3.21.0
lerna info versioning independent
lerna info Adding axios in 2 packages
lerna info Bootstrapping 2 packages
lerna info Installing external dependencies
lerna info Symlinking packages and binaries
lerna success Bootstrapped 2 packages
~/Desktop/opensource/lerna-starter/packages/sub-a lerna add rxjs --scope=sub-a
lerna notice cli v3.21.0
lerna info versioning independent
lerna notice filter including "sub-a"
lerna info filter [ 'sub-a' ]
lerna info Adding rxjs in 1 package
lerna info Bootstrapping 2 packages
lerna info Installing external dependencies
lerna info Symlinking packages and binaries
lerna success Bootstrapped 2 packages
```
