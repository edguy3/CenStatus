
## Synopsis

This file shows the status of public cen.ai tracked projects as of Tue Feb 20 05:30:55 EST 2018.

## Modules 

| MODULE & Logfile | Status | Detail | Test Pass | Test Fail| Build | Attempt|
| --- | --- | --- | --- | ---  | --- | --- | 
| [OpenCOG_DebOld__Core_Build](jobs/OpenCOG_DebOld__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-15  | 2018-01-15 |
| [OpenCOG_DebStab_AtomSpace](jobs/OpenCOG_DebStab_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 2018-02-05 | 04:46 | 05:27  | 05:27 |
| [OpenCOG_DebStab_CogUtil](jobs/OpenCOG_DebStab_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 04:43 |  | 05:26  | 05:26 |
| [OpenCOG_DebStab__Core_Build](jobs/OpenCOG_DebStab__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-16  | 04:14 |
| [OpenCOG_DebStab_Guile](jobs/OpenCOG_DebStab_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 05:26 |
| [OpenCOG_DebStab_Moses](jobs/OpenCOG_DebStab_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 04:52 |  | 05:30  | 05:30 |
| [OpenCOG_DebStab_Opencog](jobs/OpenCOG_DebStab_Opencog.log) | ![Status](/images/TESTFAIL.svg) | [56% tests passed, 7 tests failed out of 16](#opencog_debstab_opencog) |  | 04:53 | 04:14  | 04:53 |
| [OpenCOG_U1404_AtomSpace](jobs/OpenCOG_U1404_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 2018-02-05 | 04:17 | 05:03  | 05:03 |
| [OpenCOG_U1404_CogUtil](jobs/OpenCOG_U1404_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 04:14 | 2018-01-21 | 05:02  | 05:02 |
| [OpenCOG_U1404__Core_Build](jobs/OpenCOG_U1404__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 05:06 |
| [OpenCOG_U1404_Guile](jobs/OpenCOG_U1404_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 05:02 |
| [OpenCOG_U1404_Moses](jobs/OpenCOG_U1404_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 04:23 | 2018-01-21 | 05:05  | 05:05 |
| [OpenCOG_U1404_Opencog](jobs/OpenCOG_U1404_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 04:24 | 05:06  | 05:06 |
| [OpenCOG_U1604_AtomSpace](jobs/OpenCOG_U1604_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 04:26 | 2018-01-27 | 05:10  | 05:10 |
| [OpenCOG_U1604_CogUtil](jobs/OpenCOG_U1604_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 04:24 | 2018-01-21 | 05:09  | 05:09 |
| [OpenCOG_U1604__Core_Build](jobs/OpenCOG_U1604__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 05:13 |
| [OpenCOG_U1604_Guile](jobs/OpenCOG_U1604_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 05:09 |
| [OpenCOG_U1604_Moses](jobs/OpenCOG_U1604_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 04:33 | 2018-01-21 | 05:12  | 05:12 |
| [OpenCOG_U1604_Opencog](jobs/OpenCOG_U1604_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 04:34 | 05:13  | 05:13 |
| [OpenCOG_U1710_AtomSpace](jobs/OpenCOG_U1710_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 2018-02-05 | 04:36 | 05:17  | 05:17 |
| [OpenCOG_U1710_CogUtil](jobs/OpenCOG_U1710_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 04:34 |  | 05:16  | 05:16 |
| [OpenCOG_U1710__Core_Build](jobs/OpenCOG_U1710__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 05:21 |
| [OpenCOG_U1710_Guile](jobs/OpenCOG_U1710_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 05:16 |
| [OpenCOG_U1710_Moses](jobs/OpenCOG_U1710_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 04:42 |  | 05:20  | 05:20 |
| [OpenCOG_U1710_Opencog](jobs/OpenCOG_U1710_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  | 2018-02-07 | 04:43 | 05:21  | 05:21 |

( Times are currently EST/EDT GMT-5/-4) 

## Error Detail


###  OpenCOG_DebStab_Opencog
```
 2/16 Test  #2: AtomSpacePublisherModuleUTest ....***Exception: SegFault  0.40 sec
 3/16 Test  #3: CogServerUTest ...................***Exception: SegFault  0.26 sec
 4/16 Test  #4: ShellUTest .......................***Exception: SegFault  0.26 sec
 5/16 Test  #5: AgentUTest .......................***Exception: SegFault  0.26 sec
 7/16 Test  #7: PLNRulesUTest ....................***Failed    1.78 sec
11/16 Test #11: DimEmbedUTest ....................***Exception: SegFault  0.26 sec
16/16 Test #16: UREPatternMinerUTest .............***Failed   13.86 sec
```

See the log file at this link: [OpenCOG_DebStab_Opencog](jobs/OpenCOG_DebStab_Opencog.log) for more detail.


## Benchmarks


## Contributors

Ed Guy.

## License

MIT license. 

