
## Synopsis

This file shows the status of public cen.ai tracked projects as of Fri Feb 23 07:10:08 EST 2018.

## Modules 

| MODULE & Logfile | Status | Detail | Test Pass | Test Fail| Build | Attempt|
| --- | --- | --- | --- | ---  | --- | --- | 
| [OpenCOG_DebOld__Core_Build](jobs/OpenCOG_DebOld__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-15  | 2018-01-15 |
| [OpenCOG_DebStab_AtomSpace](jobs/OpenCOG_DebStab_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 2018-02-05 | 04:01 | 06:53  | 06:53 |
| [OpenCOG_DebStab_CogUtil](jobs/OpenCOG_DebStab_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 03:59 |  | 06:52  | 06:52 |
| [OpenCOG_DebStab__Core_Build](jobs/OpenCOG_DebStab__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-16  | 06:57 |
| [OpenCOG_DebStab_Guile](jobs/OpenCOG_DebStab_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 06:52 |
| [OpenCOG_DebStab_Moses](jobs/OpenCOG_DebStab_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 04:08 |  | 06:56  | 06:56 |
| [OpenCOG_DebStab_Opencog](jobs/OpenCOG_DebStab_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 04:09 | 06:57  | 06:57 |
| [OpenCOG_U1404_AtomSpace](jobs/OpenCOG_U1404_AtomSpace.log) | ![Status](/images/TESTFAIL.svg) | [97% tests passed, 3 tests failed out of 106](#opencog_u1404_atomspace) | 2018-02-05 | 07:02 | 06:28  | 07:02 |
| [OpenCOG_U1404_CogUtil](jobs/OpenCOG_U1404_CogUtil.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 12 | 06:57 | 2018-01-21 | 06:27  | 06:57 |
| [OpenCOG_U1404__Core_Build](jobs/OpenCOG_U1404__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 06:31 |
| [OpenCOG_U1404_Guile](jobs/OpenCOG_U1404_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 06:27 |
| [OpenCOG_U1404_Moses](jobs/OpenCOG_U1404_Moses.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 35 | 07:09 | 2018-01-21 | 06:30  | 07:09 |
| [OpenCOG_U1404_Opencog](jobs/OpenCOG_U1404_Opencog.log) | ![Status](/images/TESTFAIL.svg) | [56% tests passed, 8 tests failed out of 18](#opencog_u1404_opencog) |  | 07:09 | 06:31  | 07:09 |
| [OpenCOG_U1604_AtomSpace](jobs/OpenCOG_U1604_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 03:43 | 2018-01-27 | 06:36  | 06:36 |
| [OpenCOG_U1604_CogUtil](jobs/OpenCOG_U1604_CogUtil.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 12 | 07:10 | 2018-01-21 | 06:34  | 07:10 |
| [OpenCOG_U1604__Core_Build](jobs/OpenCOG_U1604__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 06:39 |
| [OpenCOG_U1604_Guile](jobs/OpenCOG_U1604_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 06:34 |
| [OpenCOG_U1604_Moses](jobs/OpenCOG_U1604_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 03:49 | 2018-01-21 | 06:38  | 06:38 |
| [OpenCOG_U1604_Opencog](jobs/OpenCOG_U1604_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 03:50 | 06:39  | 06:39 |
| [OpenCOG_U1710_AtomSpace](jobs/OpenCOG_U1710_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 2018-02-05 | 03:52 | 06:42  | 06:42 |
| [OpenCOG_U1710_CogUtil](jobs/OpenCOG_U1710_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 03:50 |  | 06:41  | 06:41 |
| [OpenCOG_U1710__Core_Build](jobs/OpenCOG_U1710__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 06:46 |
| [OpenCOG_U1710_Guile](jobs/OpenCOG_U1710_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 06:41 |
| [OpenCOG_U1710_Moses](jobs/OpenCOG_U1710_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 03:58 |  | 06:45  | 06:45 |
| [OpenCOG_U1710_Opencog](jobs/OpenCOG_U1710_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  | 2018-02-07 | 03:59 | 06:46  | 06:46 |

( Times are currently EST/EDT GMT-5/-4) 

## Error Detail


###  OpenCOG_U1404_AtomSpace
```
 25/106 Test  #25: PutLinkUTest .....................***Exception: Other119.82 sec
 40/106 Test  #40: AttentionUTest ...................***Failed    0.01 sec
 46/106 Test  #46: SCMExecutionOutputUTest ..........***Exception: Other  0.71 sec
```

See the log file at this link: [OpenCOG_U1404_AtomSpace](jobs/OpenCOG_U1404_AtomSpace.log) for more detail.


###  OpenCOG_U1404_Opencog
```
 2/18 Test  #2: AtomSpacePublisherModuleUTest ....***Exception: SegFault  0.33 sec
 3/18 Test  #3: CogServerUTest ...................***Exception: SegFault  0.31 sec
 4/18 Test  #4: ShellUTest .......................***Exception: SegFault  0.31 sec
 5/18 Test  #5: AgentUTest .......................***Exception: SegFault  0.31 sec
 6/18 Test  #6: AtomOcTreeUTest ..................***Exception: SegFault  0.07 sec
 7/18 Test  #7: TimeSpaceAtomUTest ...............***Exception: SegFault  0.08 sec
 9/18 Test  #9: PLNRulesUTest ....................***Failed    2.57 sec
13/18 Test #13: DimEmbedUTest ....................***Exception: SegFault  0.31 sec
```

See the log file at this link: [OpenCOG_U1404_Opencog](jobs/OpenCOG_U1404_Opencog.log) for more detail.


## Benchmarks


## Contributors

Ed Guy.

## License

MIT license. 

