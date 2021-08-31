# Sample android apps for testing purposes

[![CircleCI](https://circleci.com/gh/misterabdul/android-sample-app/tree/master.svg?style=svg)](https://circleci.com/gh/misterabdul/android-sample-app/tree/master)

This is for testing the [android build environment](https://github.com/misterabdul/android-build-environment) using the [circleci](https://github.com/misterabdul/android-build-environment) pipelines.

This project contains code related to sign the release build using sample.keystore and keystore.properties files. However, if you consider adopting this model, use your own private keystore file and adjust the keystore.properties files with your needs. Never put the keystore file into the source control. Store the keystore file separately and privately.
