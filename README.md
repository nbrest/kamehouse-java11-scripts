KameHouse scripts to build old java 11 kamehouse releases docker images

From the root of this repo run:

```sh
cp -rfv bin/functions/docker/release/* ${HOME}/programs/kamehouse-shell/bin/functions/docker/release/
cp -rfv bin/docker/release/* ${HOME}/programs/kamehouse-shell/bin/docker/release/
```

Then run the scripts to build and run the kamehouse docker image

