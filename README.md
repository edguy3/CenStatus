
## Synopsis

This file shows the status of public cen.ai tracked projects as of Wed Jan 24 04:29:28 EST 2018.

## Modules 

| MODULE & Logfile | Status | Detail | Test Pass | Test Fail| Build | Attempt|
| --- | --- | --- | --- | ---  | --- | --- | 
| [OpenCOG_DebOld__Core_Build](jobs/OpenCOG_DebOld__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-15  | 2018-01-15 |
| [OpenCOG_DebStab_Atomspace](jobs/OpenCOG_DebStab_Atomspace.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 111 | 03:50 |  |   | 03:50 |
| [OpenCOG_DebStab_AtomSpace](jobs/OpenCOG_DebStab_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 03:16  | 03:16 |
| [OpenCOG_DebStab_CogUtil](jobs/OpenCOG_DebStab_CogUtil.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 12 | 03:47 |  | 03:15  | 03:47 |
| [OpenCOG_DebStab__Core_Build](jobs/OpenCOG_DebStab__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-16  | 03:21 |
| [OpenCOG_DebStab_Guile](jobs/OpenCOG_DebStab_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 03:15 |
| [OpenCOG_DebStab_Moses](jobs/OpenCOG_DebStab_Moses.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 35 | 03:57 |  | 03:19  | 03:57 |
| [OpenCOG_DebStab_Opencog](jobs/OpenCOG_DebStab_Opencog.log) | ![Status](/images/TESTFAIL.svg) | [70% tests passed, 7 tests failed out of 23](#opencog_debstab_opencog) |  | 04:00 | 03:21  | 04:00 |
| [OpenCOG_U1404_AtomSpace](jobs/OpenCOG_U1404_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  |  | 03:25 | 04:27  | 04:27 |
| [OpenCOG_U1404_CogUtil](jobs/OpenCOG_U1404_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 03:21 | 2018-01-21 | 04:26  | 04:26 |
| [OpenCOG_U1404__Core_Build](jobs/OpenCOG_U1404__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 02:52 |
| [OpenCOG_U1404_Guile](jobs/OpenCOG_U1404_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 04:26 |
| [OpenCOG_U1404_Moses](jobs/OpenCOG_U1404_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 03:31 | 2018-01-21 | 04:29  | 04:29 |
| [OpenCOG_U1404_Opencog](jobs/OpenCOG_U1404_Opencog.log) | ![Status](/images/TESTFAIL.svg) | [80% tests passed, 5 tests failed out of 25](#opencog_u1404_opencog) |  | 03:34 | 02:52  | 03:34 |
| [OpenCOG_U1604_AtomSpace](jobs/OpenCOG_U1604_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  |  | 03:37 | 04:08  | 04:08 |
| [OpenCOG_U1604_CogUtil](jobs/OpenCOG_U1604_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 03:34 | 2018-01-21 | 04:07  | 04:07 |
| [OpenCOG_U1604__Core_Build](jobs/OpenCOG_U1604__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 04:11 |
| [OpenCOG_U1604_Guile](jobs/OpenCOG_U1604_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 04:07 |
| [OpenCOG_U1604_Moses](jobs/OpenCOG_U1604_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 03:44 | 2018-01-21 | 04:10  | 04:10 |
| [OpenCOG_U1604_Opencog](jobs/OpenCOG_U1604_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 03:47 | 04:11  | 04:11 |
| [OpenCOG_U1704_AtomSpace](jobs/OpenCOG_U1704_AtomSpace.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 2018-01-16 |
| [OpenCOG_U1704_CogUtil](jobs/OpenCOG_U1704_CogUtil.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 2018-01-16 |
| [OpenCOG_U1704__Core_Build](jobs/OpenCOG_U1704__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-16  | 2018-01-16 |
| [OpenCOG_U1704_Moses](jobs/OpenCOG_U1704_Moses.log) | ![Status](/images/INSTALLFAIL.svg) |  |  |  |   | 2018-01-16 |
| [OpenCOG_U1704_Opencog](jobs/OpenCOG_U1704_Opencog.log) | ![Status](/images/TESTFAIL.svg) |  |  | 2018-01-16 |   | 2018-01-16 |

( Times are currently EST/EDT GMT-5/-4) 

## Error Detail


###  OpenCOG_DebStab_Opencog
```
 2/23 Test  #2: AtomSpacePublisherModuleUTest ....***Exception: Other  5.98 sec
 6/23 Test  #6: AnaphoraTest .....................***Failed    9.60 sec
 8/23 Test  #8: PLNRulesUTest ....................***Failed    2.87 sec
10/23 Test #10: OpenPsiRulesUTest ................***Failed    2.68 sec
11/23 Test #11: OpenPsiImplicatorUTest ...........***Failed    0.95 sec
12/23 Test #12: OpenPsiSCMUTest ..................***Failed    0.82 sec
17/23 Test #17: RestApiTest ......................***Failed    1.18 sec
```

See the log file at this link: [OpenCOG_DebStab_Opencog](jobs/OpenCOG_DebStab_Opencog.log) for more detail.


###  OpenCOG_U1404_Opencog
```
 6/25 Test  #6: AtomOcTreeUTest ..................***Exception: SegFault  0.11 sec
 7/25 Test  #7: TimeSpaceAtomUTest ...............***Exception: SegFault  0.08 sec
 8/25 Test  #8: AnaphoraTest .....................***Failed   11.05 sec
10/25 Test #10: PLNRulesUTest ....................***Failed    2.91 sec
19/25 Test #19: RestApiTest ......................***Failed    1.47 sec
```

See the log file at this link: [OpenCOG_U1404_Opencog](jobs/OpenCOG_U1404_Opencog.log) for more detail.


## Contributors

Ed Guy.

## License

MIT license. 

