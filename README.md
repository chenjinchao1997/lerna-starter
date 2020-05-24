# lerna sample

lerna init

cd package/core

npm init

lerna bootstrap

lerna add _package_

```
(base)  chenjinchao@chenchaochaodeMacBook-Air  ~/Desktop/opensource/lerna-starter/packages/sub-a  lerna add axios
lerna notice cli v3.21.0
lerna info versioning independent
lerna info Adding axios in 2 packages
lerna info Bootstrapping 2 packages
lerna info Installing external dependencies
lerna info Symlinking packages and binaries
lerna success Bootstrapped 2 packages
(base)  chenjinchao@chenchaochaodeMacBook-Air  ~/Desktop/opensource/lerna-starter/packages/sub-a  lerna add rxjs --scope=sub-alerna notice cli v3.21.0
lerna info versioning independent
lerna notice filter including "sub-a"
lerna info filter [ 'sub-a' ]
lerna info Adding rxjs in 1 package
lerna info Bootstrapping 2 packages
lerna info Installing external dependencies
lerna info Symlinking packages and binaries
lerna success Bootstrapped 2 packages
```
