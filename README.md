# travis-windows-test
[![Build Status](https://travis-ci.org/StefanScherer/travis-windows-test.svg?branch=master)](https://travis-ci.org/StefanScherer/travis-windows-test)

Test TravisCI with Windows builder


## Pros

- Windows Server, version 1803
- Docker EE 18.03 preinstalled, some older 1803 base images are already pulled

## Current issues

- hyperv isolation does not work https://travis-ci.community/t/docker-hyperv-isolation-support-to-run-older-windows-images/1767/1
- Problems using Node.js
