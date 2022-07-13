1. `yarn install`
2. `yarn ci:compile`
3. `yarn ci:prebuild` - do this for each platform, and copy the results together
4. bump package version
5. `npm publish`


### Windows

1. Need Visual Studio 2017 installed with C++ Desktop package
2. `npm config unset msvs_version`
3. Use the "git bash" prompt, since they use `sh` under the hood
