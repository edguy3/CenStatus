
## Synopsis

This file shows the status of public cen.ai tracked projects as of Mon Jan 29 23:00:39 EST 2018.

## Modules 

| MODULE & Logfile | Status | Detail | Test Pass | Test Fail| Build | Attempt|
| --- | --- | --- | --- | ---  | --- | --- | 
| [OpenCOG_DebOld__Core_Build](jobs/OpenCOG_DebOld__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-15  | 2018-01-15 |
| [OpenCOG_DebStab_AtomSpace](jobs/OpenCOG_DebStab_AtomSpace.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 111 | 22:18 |  | 21:37  | 22:18 |
| [OpenCOG_DebStab_CogUtil](jobs/OpenCOG_DebStab_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 22:15 |  | 23:00  | 23:00 |
| [OpenCOG_DebStab__Core_Build](jobs/OpenCOG_DebStab__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-16  | 21:40 |
| [OpenCOG_DebStab_Guile](jobs/OpenCOG_DebStab_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 23:00 |
| [OpenCOG_DebStab_Moses](jobs/OpenCOG_DebStab_Moses.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 35 | 22:25 |  | 21:39  | 22:25 |
| [OpenCOG_DebStab_Opencog](jobs/OpenCOG_DebStab_Opencog.log) | ![Status](/images/TESTFAIL.svg) | [83% tests passed, 4 tests failed out of 23](#opencog_debstab_opencog) |  | 22:28 | 21:40  | 22:28 |
| [OpenCOG_U1404_AtomSpace](jobs/OpenCOG_U1404_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  |  | 21:44 | 22:37  | 22:37 |
| [OpenCOG_U1404_CogUtil](jobs/OpenCOG_U1404_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 21:41 | 2018-01-21 | 22:36  | 22:36 |
| [OpenCOG_U1404__Core_Build](jobs/OpenCOG_U1404__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 22:40 |
| [OpenCOG_U1404_Guile](jobs/OpenCOG_U1404_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 22:36 |
| [OpenCOG_U1404_Moses](jobs/OpenCOG_U1404_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 21:50 | 2018-01-21 | 22:39  | 22:39 |
| [OpenCOG_U1404_Opencog](jobs/OpenCOG_U1404_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 21:53 | 22:40  | 22:40 |
| [OpenCOG_U1604_AtomSpace](jobs/OpenCOG_U1604_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 21:55 | 2018-01-27 | 22:44  | 22:44 |
| [OpenCOG_U1604_CogUtil](jobs/OpenCOG_U1604_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 21:53 | 2018-01-21 | 22:43  | 22:43 |
| [OpenCOG_U1604__Core_Build](jobs/OpenCOG_U1604__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 22:47 |
| [OpenCOG_U1604_Guile](jobs/OpenCOG_U1604_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 22:43 |
| [OpenCOG_U1604_Moses](jobs/OpenCOG_U1604_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 22:02 | 2018-01-21 | 22:46  | 22:46 |
| [OpenCOG_U1604_Opencog](jobs/OpenCOG_U1604_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 22:05 | 22:47  | 22:47 |
| [OpenCOG_U1710_AtomSpace](jobs/OpenCOG_U1710_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 22:07 | 2018-01-28 | 22:51  | 22:51 |
| [OpenCOG_U1710_CogUtil](jobs/OpenCOG_U1710_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 22:05 |  | 22:50  | 22:50 |
| [OpenCOG_U1710__Core_Build](jobs/OpenCOG_U1710__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 22:55 |
| [OpenCOG_U1710_Guile](jobs/OpenCOG_U1710_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 22:50 |
| [OpenCOG_U1710_Moses](jobs/OpenCOG_U1710_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 22:13 |  | 22:54  | 22:54 |
| [OpenCOG_U1710_Opencog](jobs/OpenCOG_U1710_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 22:15 | 22:55  | 22:55 |

( Times are currently EST/EDT GMT-5/-4) 

## Error Detail


###  OpenCOG_DebStab_Opencog
```
 2/23 Test  #2: AtomSpacePublisherModuleUTest ....***Exception: Other  5.33 sec
 6/23 Test  #6: AnaphoraTest .....................***Exception: SegFault  0.70 sec
 8/23 Test  #8: PLNRulesUTest ....................***Failed    1.72 sec
17/23 Test #17: RestApiTest ......................***Failed    0.31 sec
```

See the log file at this link: [OpenCOG_DebStab_Opencog](jobs/OpenCOG_DebStab_Opencog.log) for more detail.


## Benchmarks


## Contributors

Ed Guy.

## License

MIT license. 

