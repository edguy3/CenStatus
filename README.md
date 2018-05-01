
## Synopsis

This file shows the status of public cen.ai tracked projects as of Mon Apr 30 22:16:34 EDT 2018.

## Modules 

| MODULE & Logfile | Status | Detail | Test Pass | Test Fail| Build | Attempt|
| --- | --- | --- | --- | ---  | --- | --- | 
| [OpenCOG_DebOld__Core_Build](jobs/OpenCOG_DebOld__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-15  | 2018-01-15 |
| [OpenCOG_DebStab_AtomSpace](jobs/OpenCOG_DebStab_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 2018-02-05 | 13:52 | 22:12  | 22:12 |
| [OpenCOG_DebStab_CogUtil](jobs/OpenCOG_DebStab_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 13:50 | 2018-04-16 | 22:11  | 22:11 |
| [OpenCOG_DebStab_Guile](jobs/OpenCOG_DebStab_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 22:11 |
| [OpenCOG_DebStab_Moses](jobs/OpenCOG_DebStab_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 13:59 |  | 22:15  | 22:15 |
| [OpenCOG_DebStab_Opencog](jobs/OpenCOG_DebStab_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 14:00 | 22:16  | 22:16 |
| [OpenCOG_DebStab__Core_Build](jobs/OpenCOG_DebStab__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-16  | 22:16 |
| [OpenCOG_U1404_AtomSpace](jobs/OpenCOG_U1404_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 2018-02-05 | 13:30 | 21:44  | 21:44 |
| [OpenCOG_U1404_CogUtil](jobs/OpenCOG_U1404_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 13:24 | 2018-01-21 | 21:43  | 21:43 |
| [OpenCOG_U1404_Guile](jobs/OpenCOG_U1404_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 21:43 |
| [OpenCOG_U1404_Moses](jobs/OpenCOG_U1404_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 13:36 | 2018-01-21 | 21:46  | 21:46 |
| [OpenCOG_U1404_Opencog](jobs/OpenCOG_U1404_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 13:37 | 21:47  | 21:47 |
| [OpenCOG_U1404__Core_Build](jobs/OpenCOG_U1404__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 21:47 |
| [OpenCOG_U1604_AtomSpace](jobs/OpenCOG_U1604_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 13:40 | 2018-01-27 | 21:58  | 21:58 |
| [OpenCOG_U1604_CogUtil](jobs/OpenCOG_U1604_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 13:37 | 2018-01-21 | 21:57  | 21:57 |
| [OpenCOG_U1604_Guile](jobs/OpenCOG_U1604_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 21:57 |
| [OpenCOG_U1604_Moses](jobs/OpenCOG_U1604_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 13:47 | 2018-01-21 | 22:00  | 22:00 |
| [OpenCOG_U1604_Opencog](jobs/OpenCOG_U1604_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 13:49 | 22:01  | 22:01 |
| [OpenCOG_U1604__Core_Build](jobs/OpenCOG_U1604__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 22:01 |
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

