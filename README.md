# Quasar App (test-project)

## How We Got Here

This shows the steps taken to create this project

```
     DevenMacBook.phillipsredhat.com/tmp    🎩sudo npm install -g @quasar/cli
npm WARN deprecated coffee-script@1.12.7: CoffeeScript on NPM has moved to "coffeescript" (no hyphen)
/usr/local/bin/quasar -> /usr/local/lib/node_modules/@quasar/cli/bin/quasar
+ @quasar/cli@1.0.5
added 294 packages from 226 contributors in 84.202s
     DevenMacBook.phillipsredhat.com/tmp    🎩quasar create test-project

  ___                             
 / _ \ _   _  __ _ ___  __ _ _ __ 
| | | | | | |/ _` / __|/ _` | '__|
| |_| | |_| | (_| \__ \ (_| | |   
 \__\_\\__,_|\__,_|___/\__,_|_|   
 


? Project name (internal usage for dev) test-project
? Project product name (must start with letter if building mobile apps) Quasar App
? Project description A Quasar Framework app
? Author Deven Phillips <deven.phillips@redhat.com>
? Pick your favorite CSS preprocessor: (can be changed later) Sass
? Pick a Quasar components & directives import strategy: (can be changed later) Auto import
? Check the features needed for your project: ESLint
? Pick an ESLint preset: Airbnb
? Cordova/Capacitor id (disregard if not building mobile apps) org.cordova.quasar.app
? Should we run `npm install` for you after the project has been created? (recommended) NPM

  Quasar CLI · Generated "test-project".


 [*] Installing project dependencies ...

npm WARN deprecated core-js@2.6.11: core-js@<3 is no longer maintained and not recommended for usage due to the number of issues. Please, upgrade your dependencies to the actual version of core-js@3.

> fsevents@1.2.11 install /Users/deven.phillipsredhat.com/tmp/test-project/node_modules/watchpack/node_modules/fsevents
> node-gyp rebuild

  SOLINK_MODULE(target) Release/.node
  CXX(target) Release/obj.target/fse/fsevents.o
  SOLINK_MODULE(target) Release/fse.node

> fsevents@1.2.11 install /Users/deven.phillipsredhat.com/tmp/test-project/node_modules/webpack-dev-server/node_modules/fsevents
> node-gyp rebuild

  SOLINK_MODULE(target) Release/.node
  CXX(target) Release/obj.target/fse/fsevents.o
  SOLINK_MODULE(target) Release/fse.node

> node-sass@4.13.0 install /Users/deven.phillipsredhat.com/tmp/test-project/node_modules/node-sass
> node scripts/install.js

Cached binary found at /Users/deven.phillipsredhat.com/.npm/node-sass/4.13.0/darwin-x64-64_binding.node

> core-js@2.6.11 postinstall /Users/deven.phillipsredhat.com/tmp/test-project/node_modules/core-js
> node -e "try{require('./postinstall')}catch(e){}"

Thank you for using core-js ( https://github.com/zloirock/core-js ) for polyfilling JavaScript standard library!

The project needs your help! Please consider supporting of core-js on Open Collective or Patreon: 
> https://opencollective.com/core-js 
> https://www.patreon.com/zloirock 

Also, the author of core-js ( https://github.com/zloirock ) is looking for a good job -)


> core-js-pure@3.6.4 postinstall /Users/deven.phillipsredhat.com/tmp/test-project/node_modules/core-js-pure
> node -e "try{require('./postinstall')}catch(e){}"


> ejs@2.7.4 postinstall /Users/deven.phillipsredhat.com/tmp/test-project/node_modules/ejs
> node ./postinstall.js

Thank you for installing EJS: built with the Jake JavaScript build tool (https://jakejs.com/)


> node-sass@4.13.0 postinstall /Users/deven.phillipsredhat.com/tmp/test-project/node_modules/node-sass
> node scripts/build.js

Binary found at /Users/deven.phillipsredhat.com/tmp/test-project/node_modules/node-sass/vendor/darwin-x64-64/binding.node
Testing binary
Binary is fine
npm notice created a lockfile as package-lock.json. You should commit this file.
added 1597 packages from 628 contributors in 96.542s

45 packages are looking for funding
  run `npm fund` for details



 [*] Running eslint --fix to comply with chosen preset rules...



> test-project@0.0.1 lint /Users/deven.phillipsredhat.com/tmp/test-project
> eslint --ext .js,.vue src "--fix"


 [*] Quasar Project initialization finished!

To get started:

  cd test-project
  quasar dev

Documentation can be found at: https://quasar.dev

Quasar is relying on donations to evolve. We'd be very grateful if you can
read our manifest on "Why donations are important": https://quasar.dev/why-donate
Donation campaign: https://donate.quasar.dev
Any amount is very welcomed.
If invoices are required, please first contact razvan@quasar.dev

Please give us a star on Github if you appreciate our work:
https://github.com/quasarframework/quasar

Enjoy! - Quasar Team


     DevenMacBook.phillipsredhat.com/tmp    🎩cd test-project/
     DevenMacBookcom/tmp/test-project    🎩quasar ext add @quasar/testing
 app:extension Installing "@quasar/testing" Quasar App Extension +0ms

 app:extension Retrieving "@quasar/quasar-app-extension-testing"... +3ms
 app:spawn [sync] Running "npm install --save-dev @quasar/quasar-app-extension-testing" +0ms

+ @quasar/quasar-app-extension-testing@1.0.0
added 4 packages from 2 contributors in 9.282s

45 packages are looking for funding
  run `npm fund` for details

? Please choose which testing harnesses to install: Jest Unit Testing

 app:extension-manager Updating /quasar.extensions.json for "@quasar/testing" extension ... +15s
 app:extension Running App Extension install script... +2ms
 app:extension Installing "@quasar/testing-unit-jest" Quasar App Extension +0ms

 app:extension Retrieving "@quasar/quasar-app-extension-testing-unit-jest"... +2ms
 app:spawn [sync] Running "npm install --save-dev @quasar/quasar-app-extension-testing-unit-jest" +0ms

npm WARN deprecated left-pad@1.3.0: use String.prototype.padStart()

> fsevents@1.2.11 install /Users/deven.phillipsredhat.com/tmp/test-project/node_modules/jest-haste-map/node_modules/fsevents
> node-gyp rebuild

  SOLINK_MODULE(target) Release/.node
  CXX(target) Release/obj.target/fse/fsevents.o
  SOLINK_MODULE(target) Release/fse.node
+ @quasar/quasar-app-extension-testing-unit-jest@1.0.0
added 400 packages from 334 contributors in 142.064s

45 packages are looking for funding
  run `npm fund` for details

? Please choose how to install required babel rules: Overwrite babel.config.js and use additional .babelrc
? Jest Unit testing will now be installed. Please choose additional options: extra "scripts" in your package.json, SFC webpack <test> loader

 app:extension-manager Updating /quasar.extensions.json for "@quasar/testing-unit-jest" extension ... +4m
 app:extension Running App Extension install script... +2ms
? Overwrite "babel.config.js"? Overwrite all
 app:extension Quasar App Extension "@quasar/testing-unit-jest" successfully installed. +2s

 app:extension Quasar App Extension "@quasar/testing" successfully installed. +4m

     DevenMacBookcom/tmp/test-project    🎩npm run test:unit

> test-project@0.0.1 test:unit /Users/deven.phillipsredhat.com/tmp/test-project
> jest --updateSnapshot

 PASS  test/jest/__tests__/App.spec.js
  Mount Quasar
    ✓ passes the sanity check and creates a wrapper (2ms)
    ✓ has a created hook (1ms)
    ✓ accesses the shallowMount (2ms)
    ✓ sets the correct default data
    ✓ correctly updates data when button is pressed (4ms)
    ✓ formats a date without throwing exception (25ms)

  console.log test/jest/__tests__/App.spec.js:59
    formattedString 2020 February Feb 03

-----------------|----------|----------|----------|----------|-------------------|
File             |  % Stmts | % Branch |  % Funcs |  % Lines | Uncovered Line #s |
-----------------|----------|----------|----------|----------|-------------------|
All files        |        0 |        0 |        0 |        0 |                   |
 layouts         |        0 |      100 |        0 |        0 |                   |
  MainLayout.vue |        0 |      100 |        0 |        0 |             45,55 |
 router          |        0 |        0 |        0 |        0 |                   |
  index.js       |        0 |      100 |        0 |        0 |        6,18,19,29 |
  routes.js      |        0 |        0 |        0 |        0 |    2,5,7,13,14,16 |
-----------------|----------|----------|----------|----------|-------------------|
Test Suites: 1 passed, 1 total
Tests:       6 passed, 6 total
Snapshots:   0 total
Time:        3.852s
Ran all test suites.
     DevenMacBookcom/tmp/test-project    🎩stryker init
Stryker is currently not installed.
? Do you want to install Stryker locally? npm

             |STRYKER|              
       ~control the mutants~        

           ..####@####..            
        .########@########.         
      .#####################.       
     #########################      
    ###########################     
    ###########################     
    @@@#####################@@@     
    ###########################     
    ###########################     
     #########################      
      '######################'      
        '########@#########'        
           ''####@####''            

Installing: npm install --save-dev @stryker-mutator/core
+ @stryker-mutator/core@2.5.0
added 24 packages from 66 contributors in 15.253s

47 packages are looking for funding
  run `npm fund` for details

Stryker installation done.
? Are you using one of these frameworks? Then select a preset configuration. vueJs
? Which test runner do you want to use? jest
? Which language does your project use? javascript
Writing & formatting stryker.conf.js...
? Which package manager do you want to use? npm
Installing NPM dependencies...
npm i --save-dev @stryker-mutator/core @stryker-mutator/vue-mutator @stryker-mutator/html-reporter @stryker-mutator/jest-runner @stryker-mutator/javascript-mutator
+ @stryker-mutator/html-reporter@2.5.0
+ @stryker-mutator/javascript-mutator@2.5.0
+ @stryker-mutator/jest-runner@2.5.0
+ @stryker-mutator/vue-mutator@2.5.0
+ @stryker-mutator/core@2.5.0
added 11 packages from 13 contributors and updated 1 package in 15.637s

45 packages are looking for funding
  run `npm fund` for details

Note: Your .gitignore file has been updated to include recommended git ignore patterns for Stryker
Done configuring stryker. Please review `stryker.conf.js`, you might need to configure transpilers or your test runner correctly.
Let's kill some mutants with this command: `stryker run`
```

A Quasar Framework app

## Install the dependencies
```bash
npm install
```

### Start the app in development mode (hot-code reloading, error reporting, etc.)
```bash
quasar dev
```

### Lint the files
```bash
npm run lint
```

### Build the app for production
```bash
quasar build
```

### Customize the configuration
See [Configuring quasar.conf.js](https://quasar.dev/quasar-cli/quasar-conf-js).
