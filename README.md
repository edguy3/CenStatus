
## Synopsis

This file shows the status of public cen.ai tracked projects as of Mon Jan 22 01:03:45 EST 2018.

## Modules 

| MODULE & Logfile | Status | Detail | Test Pass | Test Fail| Build | Attempt|
| --- | --- | --- | --- | ---  | --- | --- | 
| [OpenCOG_DebOld__Core_Build](jobs/OpenCOG_DebOld__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-15  | 2018-01-15 |
| [OpenCOG_DebStab__Core_Build](jobs/OpenCOG_DebStab__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-16  | 2018-01-16 |
| [OpenCOG_U1404_AtomSpace](jobs/OpenCOG_U1404_AtomSpace.log) | ![Status](/images/TESTFAIL.svg) | [99% tests passed, 1 tests failed out of 111](#opencog_u1404_atomspace) |  | 00:57 | 00:51  | 00:57 |
| [OpenCOG_U1404_CogUtil](jobs/OpenCOG_U1404_CogUtil.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 12 | 00:54 | 2018-01-21 | 00:50  | 00:54 |
| [OpenCOG_U1404__Core_Build](jobs/OpenCOG_U1404__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 00:54  | 00:54 |
| [OpenCOG_U1404_Guile](jobs/OpenCOG_U1404_Guile.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 00:50  | 00:50 |
| [OpenCOG_U1404_Moses](jobs/OpenCOG_U1404_Moses.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 35 | 01:03 | 2018-01-21 | 00:53  | 01:03 |
| [OpenCOG_U1404_Opencog](jobs/OpenCOG_U1404_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 2018-01-21 | 00:54  | 00:54 |
| [OpenCOG_U1604_AtomSpace](jobs/OpenCOG_U1604_AtomSpace.log) | ![Status](/images/TESTFAIL.svg) | [98% tests passed, 2 tests failed out of 111](#opencog_u1604_atomspace) |  | 2018-01-21 | 2018-01-21  | 2018-01-21 |
| [OpenCOG_U1604_CogUtil](jobs/OpenCOG_U1604_CogUtil.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 12 | 2018-01-21 | 2018-01-21 | 2018-01-21  | 2018-01-21 |
| [OpenCOG_U1604__Core_Build](jobs/OpenCOG_U1604__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-21  | 2018-01-21 |
| [OpenCOG_U1604_Moses](jobs/OpenCOG_U1604_Moses.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 35 | 2018-01-21 | 2018-01-21 | 2018-01-21  | 2018-01-21 |
| [OpenCOG_U1604_Opencog](jobs/OpenCOG_U1604_Opencog.log) | ![Status](/images/TESTFAIL.svg) | [80% tests passed, 5 tests failed out of 25](#opencog_u1604_opencog) |  | 2018-01-21 | 2018-01-21  | 2018-01-21 |
| [OpenCOG_U1704_AtomSpace](jobs/OpenCOG_U1704_AtomSpace.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 2018-01-16 |
| [OpenCOG_U1704_CogUtil](jobs/OpenCOG_U1704_CogUtil.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 2018-01-16 |
| [OpenCOG_U1704__Core_Build](jobs/OpenCOG_U1704__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-16  | 2018-01-16 |
| [OpenCOG_U1704_Moses](jobs/OpenCOG_U1704_Moses.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 2018-01-16 |
| [OpenCOG_U1704_Opencog](jobs/OpenCOG_U1704_Opencog.log) | ![Status](/images/TESTFAIL.svg) |  |  | 2018-01-16 |   | 2018-01-16 |

( Times are currently EST/EDT GMT-5/-4) 

## Error Detail


###  OpenCOG_U1404_AtomSpace
```
111/111 Test #111: CythonGuile ......................***Exception: SegFault  0.43 sec
```


###  OpenCOG_U1604_AtomSpace
```
 41/111 Test  #41: BasicSCMUTest ....................***Failed    0.16 sec
111/111 Test #111: CythonGuile ......................***Exception: SegFault  0.20 sec
```


###  OpenCOG_U1604_Opencog
```
 2/25 Test  #2: AtomSpacePublisherModuleUTest ....***Exception: Other  5.14 sec
 6/25 Test  #6: AtomOcTreeUTest ..................***Exception: SegFault  0.07 sec
 7/25 Test  #7: TimeSpaceAtomUTest ...............***Exception: SegFault  0.07 sec
 8/25 Test  #8: AnaphoraTest .....................***Failed    1.39 sec
19/25 Test #19: RestApiTest ......................***Failed    0.21 sec
```


## Contributors

Ed Guy.

## License

MIT license. 

