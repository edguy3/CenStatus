
## Synopsis

This file shows the status of public cen.ai tracked projects as of Sun Jan 21 22:11:35 EST 2018.

## Modules 

| MODULE & Logfile | Status | Detail | Test Pass | Test Fail| Build | Attempt|
| --- | --- | --- | --- | ---  | --- | --- | 
| [OpenCOG_DebOld__Core_Build](jobs/OpenCOG_DebOld__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-15  | 2018-01-15 |
| [OpenCOG_DebStab__Core_Build](jobs/OpenCOG_DebStab__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-16  | 2018-01-16 |
| [OpenCOG_U1404_AtomSpace](jobs/OpenCOG_U1404_AtomSpace.log) | ![Status](/images/BUILDFAIL.svg) |  |  | 2018-01-17 | 2018-01-16  | 21:52 |
| [OpenCOG_U1404_CogUtil](jobs/OpenCOG_U1404_CogUtil.log) | ![Status](/images/TESTFAIL.svg) |  | 2018-01-19 | 21:52 | 21:51  | 21:52 |
| [OpenCOG_U1404__Core_Build](jobs/OpenCOG_U1404__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-17  | 2018-01-17 |
| [OpenCOG_U1404_Guile](jobs/OpenCOG_U1404_Guile.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 2018-01-17 |
| [OpenCOG_U1404_Moses](jobs/OpenCOG_U1404_Moses.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 35 | 2018-01-17 |  | 2018-01-17  | 2018-01-17 |
| [OpenCOG_U1404_Opencog](jobs/OpenCOG_U1404_Opencog.log) | ![Status](/images/TESTFAIL.svg) |  |  | 2018-01-17 | 2018-01-16  | 2018-01-17 |
| [OpenCOG_U1604_AtomSpace](jobs/OpenCOG_U1604_AtomSpace.log) | ![Status](/images/TESTFAIL.svg) | [98% tests passed, 2 tests failed out of 111](#opencog_u1604_atomspace) |  | 2018-01-18 | 2018-01-18  | 2018-01-18 |
| [OpenCOG_U1604_CogUtil](jobs/OpenCOG_U1604_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 2018-01-18 |  | 22:11  | 22:11 |
| [OpenCOG_U1604__Core_Build](jobs/OpenCOG_U1604__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-18  | 2018-01-18 |
| [OpenCOG_U1604_Moses](jobs/OpenCOG_U1604_Moses.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 35 | 2018-01-18 |  | 2018-01-18  | 2018-01-18 |
| [OpenCOG_U1604_Opencog](jobs/OpenCOG_U1604_Opencog.log) | ![Status](/images/TESTFAIL.svg) | [80% tests passed, 5 tests failed out of 25](#opencog_u1604_opencog) |  | 2018-01-18 | 2018-01-18  | 2018-01-18 |
| [OpenCOG_U1704_AtomSpace](jobs/OpenCOG_U1704_AtomSpace.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 2018-01-16 |
| [OpenCOG_U1704_CogUtil](jobs/OpenCOG_U1704_CogUtil.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 2018-01-16 |
| [OpenCOG_U1704__Core_Build](jobs/OpenCOG_U1704__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-16  | 2018-01-16 |
| [OpenCOG_U1704_Moses](jobs/OpenCOG_U1704_Moses.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 2018-01-16 |
| [OpenCOG_U1704_Opencog](jobs/OpenCOG_U1704_Opencog.log) | ![Status](/images/TESTFAIL.svg) |  |  | 2018-01-16 |   | 2018-01-16 |

( Times are currently EST/EDT GMT-5/-4) 

## Error Detail


###  OpenCOG_U1604_AtomSpace
```
 41/111 Test  #41: BasicSCMUTest ....................***Failed    0.16 sec
111/111 Test #111: CythonGuile ......................***Exception: SegFault  0.21 sec
```


###  OpenCOG_U1604_Opencog
```
 2/25 Test  #2: AtomSpacePublisherModuleUTest ....***Exception: Other  5.14 sec
 6/25 Test  #6: AtomOcTreeUTest ..................***Exception: SegFault  0.07 sec
 7/25 Test  #7: TimeSpaceAtomUTest ...............***Exception: SegFault  0.07 sec
 8/25 Test  #8: AnaphoraTest .....................***Failed    1.41 sec
19/25 Test #19: RestApiTest ......................***Failed    0.27 sec
```


## Contributors

Ed Guy.

## License

MIT license. 

