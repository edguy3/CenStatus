
## Synopsis

This file shows the status of public cen.ai tracked projects as of Mon Apr 23 18:22:15 EDT 2018.

## Modules 

| MODULE & Logfile | Status | Detail | Test Pass | Test Fail| Build | Attempt|
| --- | --- | --- | --- | ---  | --- | --- | 
| [OpenCOG_DebOld__Core_Build](jobs/OpenCOG_DebOld__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-15  | 2018-01-15 |
| [OpenCOG_DebStab_AtomSpace](jobs/OpenCOG_DebStab_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 2018-02-05 | 06:17 | 18:18  | 18:18 |
| [OpenCOG_DebStab_CogUtil](jobs/OpenCOG_DebStab_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 06:15 | 2018-04-16 | 18:17  | 18:17 |
| [OpenCOG_DebStab_Guile](jobs/OpenCOG_DebStab_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 18:17 |
| [OpenCOG_DebStab_Moses](jobs/OpenCOG_DebStab_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 06:24 |  | 18:21  | 18:21 |
| [OpenCOG_DebStab_Opencog](jobs/OpenCOG_DebStab_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 06:25 | 18:22  | 18:22 |
| [OpenCOG_DebStab__Core_Build](jobs/OpenCOG_DebStab__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-16  | 05:49 |
| [OpenCOG_U1404_AtomSpace](jobs/OpenCOG_U1404_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 2018-02-05 | 05:55 | 17:58  | 17:58 |
| [OpenCOG_U1404_CogUtil](jobs/OpenCOG_U1404_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 05:49 | 2018-01-21 | 17:57  | 17:57 |
| [OpenCOG_U1404_Guile](jobs/OpenCOG_U1404_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 17:57 |
| [OpenCOG_U1404_Moses](jobs/OpenCOG_U1404_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 06:01 | 2018-01-21 | 18:00  | 18:00 |
| [OpenCOG_U1404_Opencog](jobs/OpenCOG_U1404_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 06:02 | 18:01  | 18:01 |
| [OpenCOG_U1404__Core_Build](jobs/OpenCOG_U1404__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 18:01 |
| [OpenCOG_U1604_AtomSpace](jobs/OpenCOG_U1604_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 06:05 | 2018-01-27 | 18:05  | 18:05 |
| [OpenCOG_U1604_CogUtil](jobs/OpenCOG_U1604_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 06:02 | 2018-01-21 | 18:03  | 18:03 |
| [OpenCOG_U1604_Guile](jobs/OpenCOG_U1604_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 18:03 |
| [OpenCOG_U1604_Moses](jobs/OpenCOG_U1604_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 06:12 | 2018-01-21 | 18:07  | 18:07 |
| [OpenCOG_U1604_Opencog](jobs/OpenCOG_U1604_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 06:14 | 18:08  | 18:08 |
| [OpenCOG_U1604__Core_Build](jobs/OpenCOG_U1604__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 18:08 |
| [OpenCOG_U1710_AtomSpace](jobs/OpenCOG_U1710_AtomSpace.log) | ![Status](/images/TESTFAIL.svg) | [98% tests passed, 2 tests failed out of 106](#opencog_u1710_atomspace) | 2018-02-05 | 2018-02-23 | 2018-02-23  | 2018-02-23 |
| [OpenCOG_U1710_CogUtil](jobs/OpenCOG_U1710_CogUtil.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 12 | 2018-02-23 |  | 2018-02-23  | 2018-02-23 |
| [OpenCOG_U1710_Guile](jobs/OpenCOG_U1710_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 2018-02-23 |
| [OpenCOG_U1710_Moses](jobs/OpenCOG_U1710_Moses.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 34 | 2018-02-23 |  | 2018-02-23  | 2018-02-23 |
| [OpenCOG_U1710_Opencog](jobs/OpenCOG_U1710_Opencog.log) | ![Status](/images/TESTFAIL.svg) | [69% tests passed, 5 tests failed out of 16](#opencog_u1710_opencog) | 2018-02-07 | 2018-02-23 | 2018-02-23  | 2018-02-23 |
| [OpenCOG_U1710__Core_Build](jobs/OpenCOG_U1710__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 2018-02-23 |

( Times are currently EST/EDT GMT-5/-4) 

## Error Detail


###  OpenCOG_U1710_AtomSpace
```
 25/106 Test  #25: PutLinkUTest .....................***Exception: SegFault  0.55 sec
 40/106 Test  #40: AttentionUTest ...................***Failed    0.01 sec
```

See the log file at this link: [OpenCOG_U1710_AtomSpace](jobs/OpenCOG_U1710_AtomSpace.log) for more detail.


###  OpenCOG_U1710_Opencog
```
 2/16 Test  #2: AtomSpacePublisherModuleUTest ....***Exception: SegFault  0.15 sec
 3/16 Test  #3: CogServerUTest ...................***Exception: SegFault  0.14 sec
 4/16 Test  #4: ShellUTest .......................***Exception: SegFault  0.15 sec
 5/16 Test  #5: AgentUTest .......................***Exception: SegFault  0.14 sec
11/16 Test #11: DimEmbedUTest ....................***Exception: SegFault  0.14 sec
```

See the log file at this link: [OpenCOG_U1710_Opencog](jobs/OpenCOG_U1710_Opencog.log) for more detail.


## Benchmarks


## Contributors

Ed Guy.

## License

MIT license. 

