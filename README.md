
## Synopsis

This file shows the status of public cen.ai tracked projects as of Wed Feb  7 20:20:10 EST 2018.

## Modules 

| MODULE & Logfile | Status | Detail | Test Pass | Test Fail| Build | Attempt|
| --- | --- | --- | --- | ---  | --- | --- | 
| [OpenCOG_DebOld__Core_Build](jobs/OpenCOG_DebOld__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-15  | 2018-01-15 |
| [OpenCOG_DebStab_AtomSpace](jobs/OpenCOG_DebStab_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 2018-02-05 | 19:23 | 20:05  | 20:05 |
| [OpenCOG_DebStab_CogUtil](jobs/OpenCOG_DebStab_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 19:21 |  | 20:04  | 20:04 |
| [OpenCOG_DebStab__Core_Build](jobs/OpenCOG_DebStab__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-16  | 20:09 |
| [OpenCOG_DebStab_Guile](jobs/OpenCOG_DebStab_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 20:04 |
| [OpenCOG_DebStab_Moses](jobs/OpenCOG_DebStab_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 19:30 |  | 20:08  | 20:08 |
| [OpenCOG_DebStab_Opencog](jobs/OpenCOG_DebStab_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 19:31 | 20:09  | 20:09 |
| [OpenCOG_U1404_AtomSpace](jobs/OpenCOG_U1404_AtomSpace.log) | ![Status](/images/TESTFAIL.svg) | [97% tests passed, 3 tests failed out of 105](#opencog_u1404_atomspace) | 2018-02-05 | 20:12 | 19:41  | 20:12 |
| [OpenCOG_U1404_CogUtil](jobs/OpenCOG_U1404_CogUtil.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 12 | 20:09 | 2018-01-21 | 19:40  | 20:09 |
| [OpenCOG_U1404__Core_Build](jobs/OpenCOG_U1404__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 19:44 |
| [OpenCOG_U1404_Guile](jobs/OpenCOG_U1404_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 19:40 |
| [OpenCOG_U1404_Moses](jobs/OpenCOG_U1404_Moses.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 35 | 20:18 | 2018-01-21 | 19:43  | 20:18 |
| [OpenCOG_U1404_Opencog](jobs/OpenCOG_U1404_Opencog.log) | ![Status](/images/TESTFAIL.svg) | [56% tests passed, 8 tests failed out of 18](#opencog_u1404_opencog) |  | 20:19 | 19:44  | 20:19 |
| [OpenCOG_U1604_AtomSpace](jobs/OpenCOG_U1604_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 19:04 | 2018-01-27 | 19:48  | 19:48 |
| [OpenCOG_U1604_CogUtil](jobs/OpenCOG_U1604_CogUtil.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 12 | 20:20 | 2018-01-21 | 19:47  | 20:20 |
| [OpenCOG_U1604__Core_Build](jobs/OpenCOG_U1604__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 19:51 |
| [OpenCOG_U1604_Guile](jobs/OpenCOG_U1604_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 19:46 |
| [OpenCOG_U1604_Moses](jobs/OpenCOG_U1604_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 19:10 | 2018-01-21 | 19:50  | 19:50 |
| [OpenCOG_U1604_Opencog](jobs/OpenCOG_U1604_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 19:11 | 19:51  | 19:51 |
| [OpenCOG_U1710_AtomSpace](jobs/OpenCOG_U1710_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 2018-02-05 | 19:14 | 19:55  | 19:55 |
| [OpenCOG_U1710_CogUtil](jobs/OpenCOG_U1710_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 19:12 |  | 19:53  | 19:53 |
| [OpenCOG_U1710__Core_Build](jobs/OpenCOG_U1710__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 19:59 |
| [OpenCOG_U1710_Guile](jobs/OpenCOG_U1710_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 19:53 |
| [OpenCOG_U1710_Moses](jobs/OpenCOG_U1710_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 19:19 |  | 19:58  | 19:58 |
| [OpenCOG_U1710_Opencog](jobs/OpenCOG_U1710_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  | 15:59 | 19:20 | 19:59  | 19:59 |

( Times are currently EST/EDT GMT-5/-4) 

## Error Detail


###  OpenCOG_U1404_AtomSpace
```
 25/105 Test  #25: PutLinkUTest .....................***Failed    0.73 sec
 40/105 Test  #40: AttentionUTest ...................***Failed    0.01 sec
 46/105 Test  #46: SCMExecutionOutputUTest ..........***Exception: Other  0.65 sec
```

See the log file at this link: [OpenCOG_U1404_AtomSpace](jobs/OpenCOG_U1404_AtomSpace.log) for more detail.


###  OpenCOG_U1404_Opencog
```
 2/18 Test  #2: AtomSpacePublisherModuleUTest ....***Exception: SegFault  0.36 sec
 3/18 Test  #3: CogServerUTest ...................***Exception: SegFault  0.34 sec
 4/18 Test  #4: ShellUTest .......................***Exception: SegFault  0.31 sec
 5/18 Test  #5: AgentUTest .......................***Exception: SegFault  0.32 sec
 6/18 Test  #6: AtomOcTreeUTest ..................***Exception: SegFault  0.07 sec
 7/18 Test  #7: TimeSpaceAtomUTest ...............***Exception: SegFault  0.07 sec
 9/18 Test  #9: PLNRulesUTest ....................***Failed    2.48 sec
13/18 Test #13: DimEmbedUTest ....................***Exception: SegFault  0.32 sec
```

See the log file at this link: [OpenCOG_U1404_Opencog](jobs/OpenCOG_U1404_Opencog.log) for more detail.


## Benchmarks


## Contributors

Ed Guy.

## License

MIT license. 

