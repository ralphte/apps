# Changelog<br>


<a name="sabnzbd-9.0.7"></a>
### [sabnzbd-9.0.7](https://github.com/truecharts/apps/compare/sabnzbd-9.0.6...sabnzbd-9.0.7) (2021-11-09)

#### Chore

* update non-major deps helm releases ([#1297](https://github.com/truecharts/apps/issues/1297))



<a name="sabnzbd-9.0.6"></a>
### [sabnzbd-9.0.6](https://github.com/truecharts/apps/compare/sabnzbd-9.0.5...sabnzbd-9.0.6) (2021-11-07)

#### Chore

* update non-major deps helm releases ([#1295](https://github.com/truecharts/apps/issues/1295))



<a name="sabnzbd-9.0.5"></a>
### [sabnzbd-9.0.5](https://github.com/truecharts/apps/compare/sabnzbd-9.0.4...sabnzbd-9.0.5) (2021-11-07)

#### Chore

* update non-major deps helm releases ([#1291](https://github.com/truecharts/apps/issues/1291))

#### Chore

* Simplify GUI for deployment, persistence and securityContext ([#1289](https://github.com/truecharts/apps/issues/1289))

#### Feat

* Simplify the Services GUI ([#1290](https://github.com/truecharts/apps/issues/1290))



<a name="sabnzbd-9.0.4"></a>
### [sabnzbd-9.0.4](https://github.com/truecharts/apps/compare/sabnzbd-9.0.3...sabnzbd-9.0.4) (2021-11-02)

#### Chore

* update non-major deps helm releases ([#1267](https://github.com/truecharts/apps/issues/1267))



<a name="sabnzbd-9.0.3"></a>
### [sabnzbd-9.0.3](https://github.com/truecharts/apps/compare/sabnzbd-9.0.2...sabnzbd-9.0.3) (2021-11-01)

#### Chore

* update non-major deps helm releases ([#1264](https://github.com/truecharts/apps/issues/1264))



<a name="sabnzbd-9.0.2"></a>
### [sabnzbd-9.0.2](https://github.com/truecharts/apps/compare/sabnzbd-9.0.1...sabnzbd-9.0.2) (2021-10-26)

#### Chore

* update non-major deps helm releases ([#1245](https://github.com/truecharts/apps/issues/1245))



<a name="sabnzbd-9.0.1"></a>
### [sabnzbd-9.0.1](https://github.com/truecharts/apps/compare/sabnzbd-9.0.0...sabnzbd-9.0.1) (2021-10-26)

#### Chore

* update helm chart common to v8.3.15 ([#1240](https://github.com/truecharts/apps/issues/1240))



<a name="sabnzbd-9.0.0"></a>
### [sabnzbd-9.0.0](https://github.com/truecharts/apps/compare/sabnzbd-8.0.17...sabnzbd-9.0.0) (2021-10-25)

#### Chore

* Adapt for TrueNAS SCALE RC1



<a name="sabnzbd-8.0.17"></a>
### [sabnzbd-8.0.17](https://github.com/truecharts/apps/compare/sabnzbd-8.0.14...sabnzbd-8.0.17) (2021-10-20)

#### Chore

* bump apps, remove duplicates and move incubator to stable for RC1
* update non-major deps helm releases ([#1213](https://github.com/truecharts/apps/issues/1213))

#### Fix

* reenable postgresql migration scripting and bump all to force update
* use correct PVC storageClass when using postgresql as a dependency on SCALE ([#1212](https://github.com/truecharts/apps/issues/1212))



<a name="sabnzbd-8.0.14"></a>
### [sabnzbd-8.0.14](https://github.com/truecharts/apps/compare/sabnzbd-8.0.13...sabnzbd-8.0.14) (2021-10-20)

#### Chore

* bump versions to rerelease and fix icons



<a name="sabnzbd-8.0.13"></a>
### [sabnzbd-8.0.13](https://github.com/truecharts/apps/compare/sabnzbd-8.0.12...sabnzbd-8.0.13) (2021-10-19)

#### Change

* Project-Eclipse 3, Automatically generate item.yaml ([#1178](https://github.com/truecharts/apps/issues/1178))

#### Chore

* Project-Eclipse 5, move app-readme to automatic generation script ([#1181](https://github.com/truecharts/apps/issues/1181))
* Project-Eclipse part 2, adapting and cleaning changelog ([#1173](https://github.com/truecharts/apps/issues/1173))
* update helm chart common to v8.3.13 ([#1184](https://github.com/truecharts/apps/issues/1184))
* update non-major ([#1174](https://github.com/truecharts/apps/issues/1174))

#### Feat

* Project-Eclipse 4, Add App grading annotations to Chart.yaml ([#1180](https://github.com/truecharts/apps/issues/1180))

#### Refactor

* Project Eclipse Part 6, move questions.yaml to root App folder ([#1182](https://github.com/truecharts/apps/issues/1182))



<a name="sabnzbd-8.0.12"></a>
### [sabnzbd-8.0.12](https://github.com/truecharts/apps/compare/sabnzbd-8.0.11...sabnzbd-8.0.12) (2021-10-19)

#### Fix

* fix previous SCALE bugfix not correctly being applied



<a name="sabnzbd-8.0.11"></a>
### [sabnzbd-8.0.11](https://github.com/truecharts/apps/compare/sabnzbd-8.0.10...sabnzbd-8.0.11) (2021-10-19)

#### Fix

* Solve issues regarding ix_values.yaml not containing the image and tag definitions. ([#1176](https://github.com/truecharts/apps/issues/1176))



<a name="sabnzbd-8.0.10"></a>
### [sabnzbd-8.0.10](https://github.com/truecharts/apps/compare/sabnzbd-8.0.9...sabnzbd-8.0.10) (2021-10-18)

#### Refactor

* Project Eclipse - part 1 - remove ix_values.yaml ([#1168](https://github.com/truecharts/apps/issues/1168))



<a name="sabnzbd-8.0.9"></a>
### [sabnzbd-8.0.9](https://github.com/truecharts/apps/compare/sabnzbd-8.0.8...sabnzbd-8.0.9) (2021-10-17)

#### Chore

* update helm chart common to v8.3.10 ([#1160](https://github.com/truecharts/apps/issues/1160))

#### Fix

* force users using correct / prefix for mounPath ([#1156](https://github.com/truecharts/apps/issues/1156))



<a name="sabnzbd-8.0.8"></a>
### [sabnzbd-8.0.8](https://github.com/truecharts/apps/compare/sabnzbd-8.0.7...sabnzbd-8.0.8) (2021-10-13)

#### Chore

* update non-major deps helm releases ([#1133](https://github.com/truecharts/apps/issues/1133))



<a name="sabnzbd-8.0.7"></a>
### [sabnzbd-8.0.7](https://github.com/truecharts/apps/compare/sabnzbd-8.0.6...sabnzbd-8.0.7) (2021-10-12)

#### Chore

* update non-major deps helm releases ([#1126](https://github.com/truecharts/apps/issues/1126))



<a name="sabnzbd-8.0.6"></a>
### [sabnzbd-8.0.6](https://github.com/truecharts/apps/compare/sabnzbd-8.0.5...sabnzbd-8.0.6) (2021-10-12)

#### Chore

* update non-major deps helm releases ([#1123](https://github.com/truecharts/apps/issues/1123))



<a name="sabnzbd-8.0.5"></a>
### [sabnzbd-8.0.5](https://github.com/truecharts/apps/compare/sabnzbd-8.0.4...sabnzbd-8.0.5) (2021-10-05)

#### Chore

* update non-major deps helm releases ([#1099](https://github.com/truecharts/apps/issues/1099))



<a name="sabnzbd-8.0.4"></a>
### [sabnzbd-8.0.4](https://github.com/truecharts/apps/compare/sabnzbd-8.0.3...sabnzbd-8.0.4) (2021-09-29)

#### Chore

* update helm chart common to v8.0.13 ([#1060](https://github.com/truecharts/apps/issues/1060))



<a name="sabnzbd-8.0.2"></a>
### [sabnzbd-8.0.2](https://github.com/truecharts/apps/compare/sabnzbd-8.0.1...sabnzbd-8.0.2) (2021-09-28)

#### Chore

* update non-major ([#1046](https://github.com/truecharts/apps/issues/1046))



<a name="sabnzbd-8.0.1"></a>
### [sabnzbd-8.0.1](https://github.com/truecharts/apps/compare/sabnzbd-8.0.0...sabnzbd-8.0.1) (2021-09-26)



<a name="sabnzbd-8.0.0"></a>
### [sabnzbd-8.0.0](https://github.com/truecharts/apps/compare/sabnzbd-7.0.2...sabnzbd-8.0.0) (2021-09-26)



<a name="sabnzbd-7.0.2"></a>
### [sabnzbd-7.0.2](https://github.com/truecharts/apps/compare/sabnzbd-7.0.1...sabnzbd-7.0.2) (2021-09-21)

#### Chore

* update non-major deps helm releases ([#1014](https://github.com/truecharts/apps/issues/1014))



<a name="sabnzbd-7.0.1"></a>
### [sabnzbd-7.0.1](https://github.com/truecharts/apps/compare/sabnzbd-6.11.15...sabnzbd-7.0.1) (2021-09-13)

#### Chore

* update non-major ([#962](https://github.com/truecharts/apps/issues/962))

#### Feat

* add new GUI and VPN support to all Apps ([#977](https://github.com/truecharts/apps/issues/977))
* Add VPN addon and move some config to includes ([#973](https://github.com/truecharts/apps/issues/973))
* pin all container references to digests ([#963](https://github.com/truecharts/apps/issues/963))
* Move some common containers to our own containers

#### Fix

* make sure podSecurityContext is included in both SCALE and Helm installs ([#956](https://github.com/truecharts/apps/issues/956))

<a name="sabnzbd-6.11.15"></a>
## [sabnzbd-6.11.15](https://github.com/truecharts/apps/compare/sabnzbd-6.11.14...sabnzbd-6.11.15) (2021-09-08)

### Fix

* repair Hyperion and some misplaced GUI elements ([#922](https://github.com/truecharts/apps/issues/922))
