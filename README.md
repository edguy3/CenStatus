
## Synopsis

This file shows the status of public cen.ai tracked projects as of Wed Feb 21 06:40:51 EST 2018.

## Modules 

| MODULE & Logfile | Status | Detail | Test Pass | Test Fail| Build | Attempt|
| --- | --- | --- | --- | ---  | --- | --- | 
| [OpenCOG_DebOld__Core_Build](jobs/OpenCOG_DebOld__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-15  | 2018-01-15 |
| [OpenCOG_DebStab_AtomSpace](jobs/OpenCOG_DebStab_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 2018-02-05 | 02:53 | 06:37  | 06:37 |
| [OpenCOG_DebStab_CogUtil](jobs/OpenCOG_DebStab_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 02:50 |  | 06:36  | 06:36 |
| [OpenCOG_DebStab__Core_Build](jobs/OpenCOG_DebStab__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-16  | 02:21 |
| [OpenCOG_DebStab_Guile](jobs/OpenCOG_DebStab_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 06:36 |
| [OpenCOG_DebStab_Moses](jobs/OpenCOG_DebStab_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 03:00 |  | 06:40  | 06:40 |
| [OpenCOG_DebStab_Opencog](jobs/OpenCOG_DebStab_Opencog.log) | ![Status](/images/TESTFAIL.svg) | [56% tests passed, 7 tests failed out of 16](#opencog_debstab_opencog) |  | 03:01 | 02:21  | 03:01 |
| [OpenCOG_U1404_AtomSpace](jobs/OpenCOG_U1404_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 2018-02-05 | 02:24 | 06:13  | 06:13 |
| [OpenCOG_U1404_CogUtil](jobs/OpenCOG_U1404_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 02:21 | 2018-01-21 | 06:12  | 06:12 |
| [OpenCOG_U1404__Core_Build](jobs/OpenCOG_U1404__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 06:16 |
| [OpenCOG_U1404_Guile](jobs/OpenCOG_U1404_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 06:11 |
| [OpenCOG_U1404_Moses](jobs/OpenCOG_U1404_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 02:30 | 2018-01-21 | 06:15  | 06:15 |
| [OpenCOG_U1404_Opencog](jobs/OpenCOG_U1404_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 02:31 | 06:16  | 06:16 |
| [OpenCOG_U1604_AtomSpace](jobs/OpenCOG_U1604_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 02:34 | 2018-01-27 | 06:20  | 06:20 |
| [OpenCOG_U1604_CogUtil](jobs/OpenCOG_U1604_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 02:32 | 2018-01-21 | 06:19  | 06:19 |
| [OpenCOG_U1604__Core_Build](jobs/OpenCOG_U1604__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 06:23 |
| [OpenCOG_U1604_Guile](jobs/OpenCOG_U1604_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 06:19 |
| [OpenCOG_U1604_Moses](jobs/OpenCOG_U1604_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 02:41 | 2018-01-21 | 06:22  | 06:22 |
| [OpenCOG_U1604_Opencog](jobs/OpenCOG_U1604_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 02:41 | 06:23  | 06:23 |
| [OpenCOG_U1710_AtomSpace](jobs/OpenCOG_U1710_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 2018-02-05 | 02:44 | 06:27  | 06:27 |
| [OpenCOG_U1710_CogUtil](jobs/OpenCOG_U1710_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 02:42 |  | 06:25  | 06:25 |
| [OpenCOG_U1710__Core_Build](jobs/OpenCOG_U1710__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 06:31 |
| [OpenCOG_U1710_Guile](jobs/OpenCOG_U1710_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 06:25 |
| [OpenCOG_U1710_Moses](jobs/OpenCOG_U1710_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 02:49 |  | 06:30  | 06:30 |
| [OpenCOG_U1710_Opencog](jobs/OpenCOG_U1710_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  | 2018-02-07 | 02:50 | 06:31  | 06:31 |

( Times are currently EST/EDT GMT-5/-4) 

## Error Detail


###  OpenCOG_DebStab_Opencog
```
 2/16 Test  #2: AtomSpacePublisherModuleUTest ....***Exception: SegFault  0.38 sec
 3/16 Test  #3: CogServerUTest ...................***Exception: SegFault  0.26 sec
 4/16 Test  #4: ShellUTest .......................***Exception: SegFault  0.26 sec
 5/16 Test  #5: AgentUTest .......................***Exception: SegFault  0.26 sec
 7/16 Test  #7: PLNRulesUTest ....................***Failed    1.75 sec
11/16 Test #11: DimEmbedUTest ....................***Exception: SegFault  0.26 sec
16/16 Test #16: UREPatternMinerUTest .............***Failed   15.31 sec
```

See the log file at this link: [OpenCOG_DebStab_Opencog](jobs/OpenCOG_DebStab_Opencog.log) for more detail.


## Benchmarks


## Contributors

Ed Guy.

## License

MIT license. 

