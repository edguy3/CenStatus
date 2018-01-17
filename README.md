
## Synopsis

This file shows the status of public cen.ai tracked projects as of Tue Jan 16 21:54:08 EST 2018.

## Modules 

| MODULE & Logfile | Status | Detail | Test Pass | Test Fail| Build | Attempt|
| --- | --- | --- | --- | ---  | --- | --- | 
| [OpenCOG_DebOld_AtomSpace](jobs/OpenCOG_DebOld_AtomSpace.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 2018-01-15 |
| [OpenCOG_DebOld_CogUtil](jobs/OpenCOG_DebOld_CogUtil.log) | ![Status](/images/TESTFAIL.svg) |  |  | 2018-01-15 | 2018-01-15  | 2018-01-15 |
| [OpenCOG_DebOld__Core_Build](jobs/OpenCOG_DebOld__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-15  | 2018-01-15 |
| [OpenCOG_DebOld_Moses](jobs/OpenCOG_DebOld_Moses.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-15  | 2018-01-15 |
| [OpenCOG_DebOld_Opencog](jobs/OpenCOG_DebOld_Opencog.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 2018-01-15 |
| [OpenCOG_DebStab_AtomSpace](jobs/OpenCOG_DebStab_AtomSpace.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 21:19 |
| [OpenCOG_DebStab_CogUtil](jobs/OpenCOG_DebStab_CogUtil.log) | ![Status](/images/TESTFAIL.svg) |  |  | 21:36 |   | 21:36 |
| [OpenCOG_DebStab__Core_Build](jobs/OpenCOG_DebStab__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 21:19  | 21:19 |
| [OpenCOG_DebStab_Moses](jobs/OpenCOG_DebStab_Moses.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 21:19 |
| [OpenCOG_DebStab_Opencog](jobs/OpenCOG_DebStab_Opencog.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 21:19 |
| [OpenCOG_U1404_AtomSpace](jobs/OpenCOG_U1404_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  |  | 21:27 | 21:51  | 21:51 |
| [OpenCOG_U1404_CogUtil](jobs/OpenCOG_U1404_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 21:33 |  | 21:50  | 21:50 |
| [OpenCOG_U1404__Core_Build](jobs/OpenCOG_U1404__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 21:16  | 21:16 |
| [OpenCOG_U1404_Moses](jobs/OpenCOG_U1404_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 21:33 |  | 21:53  | 21:53 |
| [OpenCOG_U1404_Opencog](jobs/OpenCOG_U1404_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 21:36 | 21:54  | 21:54 |
| [OpenCOG_U1604_AtomSpace](jobs/OpenCOG_U1604_AtomSpace.log) | ![Status](/images/TESTFAIL.svg) | 98% tests passed, 2 tests failed out of 111 |  | 21:45 | 21:22  | 21:45 |
| [OpenCOG_U1604_CogUtil](jobs/OpenCOG_U1604_CogUtil.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 12 | 21:43 |  | 21:21  | 21:43 |
| [OpenCOG_U1604__Core_Build](jobs/OpenCOG_U1604__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 21:25  | 21:25 |
| [OpenCOG_U1604_Moses](jobs/OpenCOG_U1604_Moses.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 35 | 21:43 |  | 21:24  | 21:43 |
| [OpenCOG_U1604_Opencog](jobs/OpenCOG_U1604_Opencog.log) | ![Status](/images/TESTFAIL.svg) | 76% tests passed, 6 tests failed out of 25 |  | 21:48 | 21:25  | 21:48 |
| [OpenCOG_U1704_AtomSpace](jobs/OpenCOG_U1704_AtomSpace.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 21:18 |
| [OpenCOG_U1704_CogUtil](jobs/OpenCOG_U1704_CogUtil.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 21:18 |
| [OpenCOG_U1704__Core_Build](jobs/OpenCOG_U1704__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 21:18  | 21:18 |
| [OpenCOG_U1704_Moses](jobs/OpenCOG_U1704_Moses.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 21:18 |
| [OpenCOG_U1704_Opencog](jobs/OpenCOG_U1704_Opencog.log) | ![Status](/images/TESTFAIL.svg) |  |  | 21:36 |   | 21:36 |

( Times are currently EST/EDT GMT-5/-4) 

## Error Detail


###  OpenCOG_U1604_AtomSpace
```
 41/111 Test  #41: BasicSCMUTest ....................***Failed    0.17 sec

111/111 Test #111: CythonGuile ......................***Exception: SegFault  0.21 sec

```


###  OpenCOG_U1604_Opencog
```
 2/25 Test  #2: AtomSpacePublisherModuleUTest ....***Exception: Other  5.14 sec

 6/25 Test  #6: AtomOcTreeUTest ..................***Exception: SegFault  0.07 sec

 7/25 Test  #7: TimeSpaceAtomUTest ...............***Exception: SegFault  0.07 sec

 8/25 Test  #8: AnaphoraTest .....................***Failed    1.22 sec

12/25 Test #12: OpenPsiRulesUTest ................***Failed    0.49 sec

14/25 Test #14: OpenPsiSCMUTest ..................***Failed    8.84 sec

```


## Contributors

Ed Guy.

## License

MIT license. 

