# robocode-codenvy
Project to set up an environment on Codenvy that will run robocode.

### docker-builder

The docker-builder folder contains the files to build an image with robocode installed.  There are some manual steps needed since the robocode installer doesn't have an unattended install option.

1. cd docker-builder
2. sudo docker build --tag davegoopot/robocode .
3. sudo docker run davegoopot/robocode --ti /bin/bash