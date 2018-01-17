
## Synopsis

This file shows the status of public cen.ai tracked projects as of Tue Jan 16 21:33:40 EST 2018.

## Modules 

| MODULE & Logfile | Status | Detail | Test Pass | Test Fail| Build | Attempt|
| --- | --- | --- | --- | ---  | --- | --- | 
| [OpenCOG_DebOld_AtomSpace](jobs/OpenCOG_DebOld_AtomSpace.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 2018-01-15 |
| [OpenCOG_DebOld_CogUtil](jobs/OpenCOG_DebOld_CogUtil.log) | ![Status](/images/TESTFAIL.svg) |  |  | 2018-01-15 | 2018-01-15  | 2018-01-15 |
| [OpenCOG_DebOld__Core_Build](jobs/OpenCOG_DebOld__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-15  | 2018-01-15 |
| [OpenCOG_DebOld_Moses](jobs/OpenCOG_DebOld_Moses.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-15  | 2018-01-15 |
| [OpenCOG_DebOld_Opencog](jobs/OpenCOG_DebOld_Opencog.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 2018-01-15 |
| [OpenCOG_DebStab_AtomSpace](jobs/OpenCOG_DebStab_AtomSpace.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 21:19 |
| [OpenCOG_DebStab_CogUtil](jobs/OpenCOG_DebStab_CogUtil.log) | ![Status](/images/INSTALLFAIL.svg) |  |  | 20:59 |   | 21:19 |
| [OpenCOG_DebStab__Core_Build](jobs/OpenCOG_DebStab__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 21:19  | 21:19 |
| [OpenCOG_DebStab_Moses](jobs/OpenCOG_DebStab_Moses.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 21:19 |
| [OpenCOG_DebStab_Opencog](jobs/OpenCOG_DebStab_Opencog.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 21:19 |
| [OpenCOG_U1404_AtomSpace](jobs/OpenCOG_U1404_AtomSpace.log) | ![Status](/images/TESTFAIL.svg) | 98% tests passed, 2 tests failed out of 111 |  | 21:27 | 21:13  | 21:27 |
| [OpenCOG_U1404_CogUtil](jobs/OpenCOG_U1404_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 20:47 |  | 21:12  | 21:12 |
| [OpenCOG_U1404__Core_Build](jobs/OpenCOG_U1404__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 21:16  | 21:16 |
| [OpenCOG_U1404_Moses](jobs/OpenCOG_U1404_Moses.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 35 | 21:33 |  | 21:15  | 21:33 |
| [OpenCOG_U1404_Opencog](jobs/OpenCOG_U1404_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 20:50 | 21:16  | 21:16 |
| [OpenCOG_U1604_AtomSpace](jobs/OpenCOG_U1604_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  |  | 21:08 | 21:22  | 21:22 |
| [OpenCOG_U1604_CogUtil](jobs/OpenCOG_U1604_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 21:06 |  | 21:21  | 21:21 |
| [OpenCOG_U1604__Core_Build](jobs/OpenCOG_U1604__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 21:25  | 21:25 |
| [OpenCOG_U1604_Moses](jobs/OpenCOG_U1604_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 21:06 |  | 21:24  | 21:24 |
| [OpenCOG_U1604_Opencog](jobs/OpenCOG_U1604_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 21:11 | 21:25  | 21:25 |
| [OpenCOG_U1704_AtomSpace](jobs/OpenCOG_U1704_AtomSpace.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 21:18 |
| [OpenCOG_U1704_CogUtil](jobs/OpenCOG_U1704_CogUtil.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 21:18 |
| [OpenCOG_U1704__Core_Build](jobs/OpenCOG_U1704__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 21:18  | 21:18 |
| [OpenCOG_U1704_Moses](jobs/OpenCOG_U1704_Moses.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 21:18 |
| [OpenCOG_U1704_Opencog](jobs/OpenCOG_U1704_Opencog.log) | ![Status](/images/INSTALLFAIL.svg) |  |  | 20:59 |   | 21:18 |

( Times are currently EST/EDT GMT-5/-4) 

## Error Detail

[ 88%] Generating NoExceptionUTest.cpp

Scanning dependencies of target NoExceptionUTest

[ 88%] Building CXX object tests/query/CMakeFiles/NoExceptionUTest.dir/NoExceptionUTest.cpp.o

Linking CXX executable NoExceptionUTest

[ 97%] Built target NoExceptionUTest

 41/111 Test  #41: BasicSCMUTest ....................***Failed    0.19 sec

/home/opencog/opencog/dependencies/atomspace/tests/scm/BasicSCMUTest.cxxtest:150: Error: Test failed: Failed to eval a UTF-8 string

/home/opencog/opencog/dependencies/atomspace/tests/scm/BasicSCMUTest.cxxtest:155: Error: Test failed: Failed to eval a UTF-8 string

/home/opencog/opencog/dependencies/atomspace/tests/scm/BasicSCMUTest.cxxtest:169: Error: Test failed: Failed to create a node

/home/opencog/opencog/dependencies/atomspace/tests/scm/BasicSCMUTest.cxxtest:173: Error: Test failed: Failed to find handle

/home/opencog/opencog/dependencies/atomspace/tests/scm/BasicSCMUTest.cxxtest:176: Error: Test failed: Failed to find node

Failed 2 and Skipped 0 of 15 tests

        Start  95: NoExceptionUTest

 95/111 Test  #95: NoExceptionUTest .................   Passed    0.07 sec

111/111 Test #111: CythonGuile ......................***Exception: SegFault  0.17 sec

	 41 - BasicSCMUTest (Failed)


## Contributors

Ed Guy.

## License

MIT license. 

