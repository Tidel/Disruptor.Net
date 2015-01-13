# .NET port of LMAX Disruptor

This project aims to provide the full functionality of the Disruptor to CLR projects.

## What's new?

1/14/2015 Added the Disruptor.RingQueueTest for mutil producers and multi comsumers, by shines77. And change the project to use .Net Framework 4.5 in Visual Studio 2013 update 2.

11/7/2013 (v2.10.0):

* All features available in Java Disruptor **2.10.0** have been ported 

## Getting Started

The quickest way to get started with the disruptor is by using the [NuGet package]

## Build from source and run tests

You may also build disruptor directly from the source:
* you need Visual Studio 2010
* run build.bat, it will compile, run the tests and output binaries and results into Target folder

You can then run the performance tests: runPerfTest.bat

[NuGet package]: http://nuget.org/packages/Disruptor

## License

Copyright Olivier Deheurles

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this project except in compliance with the License.

You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
