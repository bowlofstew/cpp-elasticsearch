# cpp-elasticsearch


## C++ Client for Elasticsearch


cpp-elasticsearch is a small C++ API to elasticsearch, it aims at becomming the official one. 

For this purpose, contributors must respect the following rules:
- Master branch must be in line with latest Elasticsearch release
- Be in line with https://github.com/elasticsearch/elasticsearch/tree/master/rest-api-spec
- Document the code
- Included in travis CI

Once the required features will be added, new features will come like:
- Load balancing
- Connection pooling
- Library package
- Performance monitoring

A documentation is stil to come as well as a "get started" page and continous intragration project with Travis.


## Warning

- Actual version is minimal and has been developped for the needs of Q-Hedge Technologies.
- Features of C++11 are used in this code.



## Buildinng

In order to build locally,

  ```
  mkdir build
  cd build
  cmake ..
  make
  ```
  
The build is also automated via Travis.  You can see the results of it [here](https://travis-ci.org/bowlofstew/cpp-elasticsearch)


## Present Build Status

[![Build Status](https://travis-ci.org/bowlofstew/cpp-elasticsearch.svg?branch=master)](https://travis-ci.org/bowlofstew/cpp-elasticsearch)


## Dependencies

  * OSX or Linux distributions

  * CMake

  * GCC/Clang
