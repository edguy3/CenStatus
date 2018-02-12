
## Synopsis

This file shows the status of public cen.ai tracked projects as of Mon Feb 12 17:55:09 EST 2018.

## Modules 

| MODULE & Logfile | Status | Detail | Test Pass | Test Fail| Build | Attempt|
| --- | --- | --- | --- | ---  | --- | --- | 
| [OpenCOG_DebOld__Core_Build](jobs/OpenCOG_DebOld__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-15  | 2018-01-15 |
| [OpenCOG_DebStab_AtomSpace](jobs/OpenCOG_DebStab_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 2018-02-05 | 05:18 | 17:52  | 17:52 |
| [OpenCOG_DebStab_CogUtil](jobs/OpenCOG_DebStab_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 05:15 |  | 17:50  | 17:50 |
| [OpenCOG_DebStab__Core_Build](jobs/OpenCOG_DebStab__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-16  | 04:47 |
| [OpenCOG_DebStab_Guile](jobs/OpenCOG_DebStab_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 17:50 |
| [OpenCOG_DebStab_Moses](jobs/OpenCOG_DebStab_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 05:24 |  | 17:55  | 17:55 |
| [OpenCOG_DebStab_Opencog](jobs/OpenCOG_DebStab_Opencog.log) | ![Status](/images/TESTFAIL.svg) | [44% tests passed, 9 tests failed out of 16](#opencog_debstab_opencog) |  | 05:25 | 04:47  | 05:25 |
| [OpenCOG_U1404_AtomSpace](jobs/OpenCOG_U1404_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 2018-02-05 | 04:50 | 17:27  | 17:27 |
| [OpenCOG_U1404_CogUtil](jobs/OpenCOG_U1404_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 04:47 | 2018-01-21 | 17:26  | 17:26 |
| [OpenCOG_U1404__Core_Build](jobs/OpenCOG_U1404__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 17:30 |
| [OpenCOG_U1404_Guile](jobs/OpenCOG_U1404_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 17:26 |
| [OpenCOG_U1404_Moses](jobs/OpenCOG_U1404_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 04:56 | 2018-01-21 | 17:29  | 17:29 |
| [OpenCOG_U1404_Opencog](jobs/OpenCOG_U1404_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 04:57 | 17:30  | 17:30 |
| [OpenCOG_U1604_AtomSpace](jobs/OpenCOG_U1604_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 04:59 | 2018-01-27 | 17:34  | 17:34 |
| [OpenCOG_U1604_CogUtil](jobs/OpenCOG_U1604_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 04:57 | 2018-01-21 | 17:33  | 17:33 |
| [OpenCOG_U1604__Core_Build](jobs/OpenCOG_U1604__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 17:37 |
| [OpenCOG_U1604_Guile](jobs/OpenCOG_U1604_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 17:33 |
| [OpenCOG_U1604_Moses](jobs/OpenCOG_U1604_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 05:06 | 2018-01-21 | 17:36  | 17:36 |
| [OpenCOG_U1604_Opencog](jobs/OpenCOG_U1604_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 05:06 | 17:37  | 17:37 |
| [OpenCOG_U1710_AtomSpace](jobs/OpenCOG_U1710_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 2018-02-05 | 05:09 | 17:41  | 17:41 |
| [OpenCOG_U1710_CogUtil](jobs/OpenCOG_U1710_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 05:06 |  | 17:40  | 17:40 |
| [OpenCOG_U1710__Core_Build](jobs/OpenCOG_U1710__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 17:45 |
| [OpenCOG_U1710_Guile](jobs/OpenCOG_U1710_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 17:40 |
| [OpenCOG_U1710_Moses](jobs/OpenCOG_U1710_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 05:14 |  | 17:44  | 17:44 |
| [OpenCOG_U1710_Opencog](jobs/OpenCOG_U1710_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  | 2018-02-07 | 05:15 | 17:45  | 17:45 |

( Times are currently EST/EDT GMT-5/-4) 

## Error Detail


###  OpenCOG_DebStab_Opencog
```
 2/16 Test  #2: AtomSpacePublisherModuleUTest ....***Exception: SegFault  0.35 sec
 3/16 Test  #3: CogServerUTest ...................***Exception: SegFault  0.26 sec
 4/16 Test  #4: ShellUTest .......................***Exception: SegFault  0.26 sec
 5/16 Test  #5: AgentUTest .......................***Exception: SegFault  0.26 sec
 6/16 Test  #6: MOSESPLNSynergyUTest .............***Failed    1.90 sec
 7/16 Test  #7: PLNRulesUTest ....................***Failed    1.76 sec
11/16 Test #11: DimEmbedUTest ....................***Exception: SegFault  0.26 sec
15/16 Test #15: XPatternMinerUTest ...............***Failed    3.50 sec
16/16 Test #16: UREPatternMinerUTest .............***Failed    4.05 sec
```

See the log file at this link: [OpenCOG_DebStab_Opencog](jobs/OpenCOG_DebStab_Opencog.log) for more detail.


## Benchmarks


## Contributors

Ed Guy.

## License

MIT license. 

