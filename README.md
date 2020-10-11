# parcel-build-glitch
Reproducible demo of parcel build glitch where the serve command continuously builds 

Environment:
* Yarn 2
* Node v14.6.0
* Npm v6.14.8

To run:
* yarn yarn:set:version
* yarn build:parcel
* yarn build:parcel # if you get the error "@parcel/transformer-babel: Invalid array length"
* yarn start

You should see the build continuously run, filling up the ./dist directory.


