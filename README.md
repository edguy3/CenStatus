
## Synopsis

This file shows the status of public cen.ai tracked projects as of Wed Feb  7 13:40:36 EST 2018.

## Modules 

| MODULE & Logfile | Status | Detail | Test Pass | Test Fail| Build | Attempt|
| --- | --- | --- | --- | ---  | --- | --- | 
| [OpenCOG_DebOld__Core_Build](jobs/OpenCOG_DebOld__Core_Build.log) | ![Status](/images/BUILDPASS.svg) |  |  |  | 2018-01-15  | 2018-01-15 |
| [OpenCOG_DebStab_AtomSpace](jobs/OpenCOG_DebStab_AtomSpace.log) | ![Status](/images/TESTFAIL.svg) | [98% tests passed, 2 tests failed out of 112](#opencog_debstab_atomspace) | 2018-02-05 | 13:01 | 12:19  | 13:01 |
| [OpenCOG_DebStab_CogUtil](jobs/OpenCOG_DebStab_CogUtil.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 12 | 12:59 |  | 12:17  | 12:59 |
| [OpenCOG_DebStab__Core_Build](jobs/OpenCOG_DebStab__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-16  | 12:23 |
| [OpenCOG_DebStab_Guile](jobs/OpenCOG_DebStab_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 12:17 |
| [OpenCOG_DebStab_Moses](jobs/OpenCOG_DebStab_Moses.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 35 | 13:08 |  | 12:22  | 13:08 |
| [OpenCOG_DebStab_Opencog](jobs/OpenCOG_DebStab_Opencog.log) | ![Status](/images/TESTFAIL.svg) | [88% tests passed, 3 tests failed out of 24](#opencog_debstab_opencog) |  | 13:11 | 12:22  | 13:11 |
| [OpenCOG_U1404_AtomSpace](jobs/OpenCOG_U1404_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 2018-02-05 | 12:26 | 13:27  | 13:27 |
| [OpenCOG_U1404_CogUtil](jobs/OpenCOG_U1404_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 12:23 | 2018-01-21 | 13:26  | 13:26 |
| [OpenCOG_U1404__Core_Build](jobs/OpenCOG_U1404__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 13:30 |
| [OpenCOG_U1404_Guile](jobs/OpenCOG_U1404_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 13:26 |
| [OpenCOG_U1404_Moses](jobs/OpenCOG_U1404_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 12:32 | 2018-01-21 | 13:29  | 13:29 |
| [OpenCOG_U1404_Opencog](jobs/OpenCOG_U1404_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 12:35 | 13:30  | 13:30 |
| [OpenCOG_U1604_AtomSpace](jobs/OpenCOG_U1604_AtomSpace.log) | ![Status](/images/BUILDPASS.svg) |  | 12:38 | 2018-01-27 | 13:34  | 13:34 |
| [OpenCOG_U1604_CogUtil](jobs/OpenCOG_U1604_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 12:35 | 2018-01-21 | 13:33  | 13:33 |
| [OpenCOG_U1604__Core_Build](jobs/OpenCOG_U1604__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 13:38 |
| [OpenCOG_U1604_Guile](jobs/OpenCOG_U1604_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  | 2018-01-22  | 13:33 |
| [OpenCOG_U1604_Moses](jobs/OpenCOG_U1604_Moses.log) | ![Status](/images/BUILDPASS.svg) |  | 12:44 | 2018-01-21 | 13:37  | 13:37 |
| [OpenCOG_U1604_Opencog](jobs/OpenCOG_U1604_Opencog.log) | ![Status](/images/BUILDPASS.svg) |  |  | 12:47 | 13:37  | 13:37 |
| [OpenCOG_U1710_AtomSpace](jobs/OpenCOG_U1710_AtomSpace.log) | ![Status](/images/TESTFAIL.svg) | [98% tests passed, 2 tests failed out of 107](#opencog_u1710_atomspace) | 2018-02-05 | 12:50 | 12:08  | 12:50 |
| [OpenCOG_U1710_CogUtil](jobs/OpenCOG_U1710_CogUtil.log) | ![Status](/images/BUILDPASS.svg) |  | 12:48 |  | 13:40  | 13:40 |
| [OpenCOG_U1710__Core_Build](jobs/OpenCOG_U1710__Core_Build.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 12:12 |
| [OpenCOG_U1710_Guile](jobs/OpenCOG_U1710_Guile.log) | ![Status](/images/BUILDPASSNOTEST.svg) |  |  |  |   | 13:40 |
| [OpenCOG_U1710_Moses](jobs/OpenCOG_U1710_Moses.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 34 | 12:55 |  | 12:11  | 12:55 |
| [OpenCOG_U1710_Opencog](jobs/OpenCOG_U1710_Opencog.log) | ![Status](/images/TESTPASS.svg) | 100% tests passed, 0 tests failed out of 18 | 12:58 | 2018-01-29 | 12:12  | 12:58 |

( Times are currently EST/EDT GMT-5/-4) 

## Error Detail


###  OpenCOG_DebStab_AtomSpace
```
 25/112 Test  #25: PutLinkUTest .....................***Failed    0.64 sec
 40/112 Test  #40: AttentionUTest ...................***Failed    0.01 sec
```

See the log file at this link: [OpenCOG_DebStab_AtomSpace](jobs/OpenCOG_DebStab_AtomSpace.log) for more detail.


###  OpenCOG_DebStab_Opencog
```
 6/24 Test  #6: AnaphoraTest .....................***Exception: SegFault  1.01 sec
 8/24 Test  #8: PLNRulesUTest ....................***Failed    1.76 sec
17/24 Test #17: RestApiTest ......................***Failed    0.35 sec
```

See the log file at this link: [OpenCOG_DebStab_Opencog](jobs/OpenCOG_DebStab_Opencog.log) for more detail.


###  OpenCOG_U1710_AtomSpace
```
 25/107 Test  #25: PutLinkUTest .....................***Failed    0.51 sec
 40/107 Test  #40: AttentionUTest ...................***Failed    0.01 sec
```

See the log file at this link: [OpenCOG_U1710_AtomSpace](jobs/OpenCOG_U1710_AtomSpace.log) for more detail.


## Benchmarks


## Contributors

Ed Guy.

## License

MIT license. 

