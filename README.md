# incubator-openwhisk-test

[![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0)
[![Build Status](https://travis-ci.org/apache/incubator-openwhisk-test.svg?branch=master)](https://travis-ci.org/apache/incubator-openwhisk-test)

This repository is used for integration testing of OpenWhisk tooling with GitHub itself.

Currently, it is being used to test GitHub (event) integration for the following sub-projects:
- [https://github.com/apache/incubator-openwhisk-wskdeploy](https://github.com/apache/incubator-openwhisk-wskdeploy).
   Used to test GitHub as an Event Provider using the OpenWhisk GitHub webhook:
  * [Test -> Integration -> Dependency](https://github.com/apache/incubator-openwhisk-wskdeploy/tree/master/tests/src/integration/dependency)
  * [Test -> Use Cases -> GitHub](https://github.com/apache/incubator-openwhisk-wskdeploy/tree/master/tests/usecases/github)
  * [Test -> Use Cases -> Dependency](https://github.com/apache/incubator-openwhisk-wskdeploy/tree/master/tests/usecases/dependency)
