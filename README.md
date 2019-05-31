<!--
#
# Licensed to the Apache Software Foundation (ASF) under one or more
# contributor license agreements.  See the NOTICE file distributed with
# this work for additional information regarding copyright ownership.
# The ASF licenses this file to You under the Apache License, Version 2.0
# (the "License"); you may not use this file except in compliance with
# the License.  You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#
-->

# incubator-openwhisk-test

[![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0)
[![Build Status](https://travis-ci.org/apache/incubator-openwhisk-test.svg?branch=master)](https://travis-ci.org/apache/incubator-openwhisk-test)

This repository is used for hosting packages used in the integration testing of OpenWhisk tooling.

Currently, it is being used to test GitHub (event) integration for the following sub-projects:
- [https://github.com/apache/incubator-openwhisk-wskdeploy](https://github.com/apache/incubator-openwhisk-wskdeploy).
   Used to test GitHub as an Event Provider using the OpenWhisk GitHub webhook:
  * [Test -> Integration -> Dependency](https://github.com/apache/incubator-openwhisk-wskdeploy/tree/master/tests/src/integration/dependency)
  * [Test -> Use Cases -> GitHub](https://github.com/apache/incubator-openwhisk-wskdeploy/tree/master/tests/usecases/github)
  * [Test -> Use Cases -> Dependency](https://github.com/apache/incubator-openwhisk-wskdeploy/tree/master/tests/usecases/dependency)
