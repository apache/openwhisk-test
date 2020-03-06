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
# Single Entrypoint Proxy

This is a repo to store single entrypoint proxy example test cases, such as Knative Serving. All single entrypoint execution environments should follow the contract this defined in the single entrypoint documentation.

The action code for each example is defined in the is directory, and the input directory has JSON files where the filename corresponds to the input for a the action code of the same file name, but with an -init, -run, or -init-run postfix. The output directory similarly has the expected output for that file.
