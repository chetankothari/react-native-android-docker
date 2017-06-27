# react-native-android-docker
Docker image for React Native Android

This is a simple docker image for building react native android application in docker. You might have to build another image with project specifics.

The base image used is `ubuntu:16.04`

Below is a list of `ENV`s and the defaults.

| Environment Variable        | Default Values             |
|-----------------------------|----------------------------|
| Java JDK                    | 8u131-b11-0ubuntu1.16.04.2 |
| ANDROID_SDK_TOOLS_VERSION   | 25                         |
| ANDROID_BUILD_TOOLS_VERSION | 25.0.3                     |
| ANDROID_TARGET_SDK_VERSION  | 25                         |
| ANDROID_HOME                | /opt/android               |
| NODEJS_VERSION              | 6.10.0                     |
| NODE_PATH                   | /opt/node                  |
| REACT_NATIVE_CLI_VERSION    | 2.0.1                      |


TODO:

Set gradle path which could be used for caching.
