# angular-meteor-whatsapp


An ionic boiler-plate for angular-meteor users designed to allow mobile functionality. (meteor mobile deploy commands don't work on windows)
Default deploy is to fhackenb-angular-meteor.meteor.com, you can change that in meteor-runtime-config.js

Modified from angular-meteor whatsapp tutorial and uses dawiong's hotfix for angular-meteor with meteor-clientside
https://github.com/dawiong/report-a-cab/commit/6fb6f06b52a28ee7aaaa9d0a4d8ca4a099271cbb

Instructions:

1)git clone https://github.com/fhackenb/angular-meteor-whatsapp

2)npm install

3)bower install

4)cordova plugin add cordova-plugin-whitelist

To run on mobile:

5)cordova platform add android

6)ionic run android
