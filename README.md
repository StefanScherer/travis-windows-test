# travis-windows-test
[![Build Status](https://travis-ci.org/StefanScherer/travis-windows-test.svg?branch=master)](https://travis-ci.org/StefanScherer/travis-windows-test)

Test TravisCI with Windows builder


## Pros

- Windows Server, version 1803
- Docker EE 18.03 preinstalled, some older 1803 base images are already pulled

## Current issues

- hyperv isolation does not work https://travis-ci.community/t/docker-hyperv-isolation-support-to-run-older-windows-images/1767/1
- Problems using Node.js

## Related projects

- https://github.com/nuest/rocker-win
- official golang Docker image uses Travis for tests on 1803: https://github.com/docker-library/golang/blob/60879215d473711ae500cc43acbfa037cf808fb0/.travis.yml#L6-L8
