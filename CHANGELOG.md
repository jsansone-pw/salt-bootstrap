# v2024.07.23

## What's Changed

- Updated link for Supported Operating Systems and Repository supported by Salt by @dmurphy18 in https://github.com/saltstack/salt-bootstrap/pull/2010
- Cleanup use of the term 'Post Neon' given only support 3006 and up by @dmurphy18 in https://github.com/saltstack/salt-bootstrap/pull/2011
- Added support with -W for installing salt-api by @dmurphy18 in https://github.com/saltstack/salt-bootstrap/pull/2013

**Full Changelog**: https://github.com/saltstack/salt-bootstrap/compare/v2024.07.18...v2024.07.23

# v2024.07.18

## What's Changed

- Updated README, and removed experimental  to ability install different Python version which was limited to RHEL 7, which is EOL by @dmurphy18 in https://github.com/saltstack/salt-bootstrap/pull/2009

**Full Changelog**: https://github.com/saltstack/salt-bootstrap/compare/v2024.07.16...v2024.07.18

# v2024.07.16

## What's Changed

- Update bootstrap-salt.sh by @javatask in https://github.com/saltstack/salt-bootstrap/pull/2005
- Updated GitHub actions to later v4 by @dmurphy18 in https://github.com/saltstack/salt-bootstrap/pull/2004
- Don't sort lists and dicts, as order of items matters  by @dmurphy18 in https://github.com/saltstack/salt-bootstrap/pull/2006

## New Contributors

- @javatask made their first contribution in https://github.com/saltstack/salt-bootstrap/pull/2005

**Full Changelog**: https://github.com/saltstack/salt-bootstrap/compare/v2024.07.12...v2024.07.16

# v2024.07.12

## What's Changed

- Add script version to powershell script by @twangboy in https://github.com/saltstack/salt-bootstrap/pull/1996
- Add support for mint-21 by @jhubbardnso in https://github.com/saltstack/salt-bootstrap/pull/1997
- Added support for Amazon 2023, Debian 12, Ubuntu 24.04, removed EOL and BSD OSs and Python 2.7 support by @dmurphy18 in https://github.com/saltstack/salt-bootstrap/pull/1987

## New Contributors

- @jhubbardnso made their first contribution in https://github.com/saltstack/salt-bootstrap/pull/1997

**Full Changelog**: https://github.com/saltstack/salt-bootstrap/compare/v2024.04.03...v2024.07.12

# v2024.07.11

## What's Changed

- Migrated to using GitHub Actions
- Removed support of End-Of-Life OS's, for example: Debian 7, 8, 9 & 10, RHEL 7
- Removed support for FreeBSD and OpenBSD
- Removed support for Solaris and it's derivatives
- Removed support for EOL Salt releases, pre-3006
- Added support for new OS's, for example: Ubuntu 24.04, Debian 12, Amazon 2023
- Updated to minimum Python 3.10 version from 3.9
- Removed '-y' option which was experimental and only on RHEL 7 or less which are now EOL
- Updated to current stable version of Ruby v3.3.4
- Removed git-master support for Photon 4 & 5 due to gcc errors building salt.
- Add support for Arm64 for MacOS

**Full Changelog**: https://github.com/saltstack/salt-bootstrap/compare/v2024.04.03...v2024.07.11

# v2024.04.03

## What's Changed

- Remove automated PR against salt repo at release by @ScriptAutomate in https://github.com/saltstack/salt-bootstrap/pull/1984
- Update actions by @twangboy in https://github.com/saltstack/salt-bootstrap/pull/1985
- Fix DEBIAN Keyring url by @Dudek-AMS in https://github.com/saltstack/salt-bootstrap/pull/1983
- Fix script to support installing RC on Windows by @twangboy in https://github.com/saltstack/salt-bootstrap/pull/1993

## New Contributors

- @Dudek-AMS made their first contribution in https://github.com/saltstack/salt-bootstrap/pull/1983

**Full Changelog**: https://github.com/saltstack/salt-bootstrap/compare/v2024.01.04...v2024.04.03

# v2024.01.04

## What's Changed

- Add arm support for Debian 10 by @twangboy in https://github.com/saltstack/salt-bootstrap/pull/1981

**Full Changelog**: https://github.com/saltstack/salt-bootstrap/compare/v2023.11.16...v2024.01.04

# v2023.11.16

## What's Changed

- checking out stable branch on update-s3-bucket job by @felippeb in https://github.com/saltstack/salt-bootstrap/pull/1977

**Full Changelog**: https://github.com/saltstack/salt-bootstrap/compare/v2023.11.07...v2023.11.16

# v2023.11.07

## What's Changed

- cleanup old information in the README.rst file by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1955
- Moving quick start scripts to bootstrap repo. by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1960
- Suppress progress bar by @twangboy in https://github.com/saltstack/salt-bootstrap/pull/1964
- Fix global variable by @twangboy in https://github.com/saltstack/salt-bootstrap/pull/1965
- Debian 12 arm64 by @joelpmichael in https://github.com/saltstack/salt-bootstrap/pull/1962
- Mirror Linux output, display root_dir by @twangboy in https://github.com/saltstack/salt-bootstrap/pull/1967
- Add asterisks to the output by @twangboy in https://github.com/saltstack/salt-bootstrap/pull/1968
- Fixes to salt-quick-start.sh by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1973
- Update requirements by @twangboy in https://github.com/saltstack/salt-bootstrap/pull/1974

**Full Changelog**: https://github.com/saltstack/salt-bootstrap/compare/v2023.08.03...v2023.11.07

# v2023.08.03

## What's Changed

- Set RootDir depending on Salt Version by @twangboy in https://github.com/saltstack/salt-bootstrap/pull/1952
- Bump to `certifi==2023.07.22` due to https://github.com/advisories/GHSA-xqr8-7jwr-rhp7 by @s0undt3ch in https://github.com/saltstack/salt-bootstrap/pull/1954
- Update windows commands to support TLS1.2 by @twangboy in https://github.com/saltstack/salt-bootstrap/pull/1956

**Full Changelog**: https://github.com/saltstack/salt-bootstrap/compare/v2023.07.25...v2023.08.03

# v2023.07.25

## What's Changed

- fix gpg pub key name for nightly rhel_onedir_repository by @ITJamie in https://github.com/saltstack/salt-bootstrap/pull/1943
- Adding quickstart option by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1945
- fix install_amazon_linux_ami_2_onedir nightly gpg key path by @ITJamie in https://github.com/saltstack/salt-bootstrap/pull/1949

## New Contributors

- @ITJamie made their first contribution in https://github.com/saltstack/salt-bootstrap/pull/1943

**Full Changelog**: https://github.com/saltstack/salt-bootstrap/compare/v2023.06.28...v2023.07.25

# v2023.06.28

## What's Changed

- SUSE Fixes by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1925
- Add old_stable type by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1934
- Test out the minor versions by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1936

**Full Changelog**: https://github.com/saltstack/salt-bootstrap/compare/v2023.04.26...v2023.06.28

# v2023.04.26

## What's Changed

- Updates for Fedora and Photon by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1920
- Fixing defaults by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1921

**Full Changelog**: https://github.com/saltstack/salt-bootstrap/compare/v2023.04.21...v2023.04.26

# v2023.04.21

## What's Changed

- Update release process by @s0undt3ch in https://github.com/saltstack/salt-bootstrap/pull/1908
- Update with 3006 stable installs by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1906
- Add support for 3006 on windows bootstrap script by @twangboy in https://github.com/saltstack/salt-bootstrap/pull/1918
- Fixes for 3006 by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1912
- Don't use GITHUB_OUTPUT by @s0undt3ch in https://github.com/saltstack/salt-bootstrap/pull/1911

**Full Changelog**: https://github.com/saltstack/salt-bootstrap/compare/v2023.04.06...v2023.04.21

# v2023.04.06

## What's Changed

- Fix missing functions for post-installation on EL clones by @ggiesen in https://github.com/saltstack/salt-bootstrap/pull/1877
- Support for dotZero in version beginning in 3006 by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1879
- Update gemfile by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1882
- update openbsd to 7, seems like 6 (6.9) is no longer available. by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1881
- Adding tests for installing onedir packages by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1880
- Removing EPEL, which is no longer needed. by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1884
- Add support for the -R flag on macOS. by @pjcreath in https://github.com/saltstack/salt-bootstrap/pull/1871
- feat: add `onedir nightly` support by @myii in https://github.com/saltstack/salt-bootstrap/pull/1885
- ci: add `fedora-37` & `fedora-38` by @myii in https://github.com/saltstack/salt-bootstrap/pull/1840
- Debian ARM Fix by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1887
- Added Pop!\_OS as a Ubuntu derivative by @shombando in https://github.com/saltstack/salt-bootstrap/pull/1888
- Don't attempt to stable install on Red Hat onedir only systems by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1889
- \[docs\] Improve Windows readme instructions and links in script by @dafyddj in https://github.com/saltstack/salt-bootstrap/pull/1897
- Adding newer versions of CentOS Stream and AlmaLinux by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1890
- Add support for KDE neon based on Ubuntu 22.04 by @digitalkram in https://github.com/saltstack/salt-bootstrap/pull/1894
- Removing Ubuntu 16.04 by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1886
- Adding rockylinux 9 by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1899
- Bootstrap fixes for 3006 by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1900
- Adding 3006.0rc1 to Github actions. by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1901
- Adding 3006.0rc2 to bootstrap tests. by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1902

## New Contributors

- @ggiesen made their first contribution in https://github.com/saltstack/salt-bootstrap/pull/1877
- @shombando made their first contribution in https://github.com/saltstack/salt-bootstrap/pull/1888
- @digitalkram made their first contribution in https://github.com/saltstack/salt-bootstrap/pull/1894

**Full Changelog**: https://github.com/saltstack/salt-bootstrap/compare/v2022.10.04...v2023.04.06

# v2022.10.04

## What's Changed

- Update README for Windows installation by @eozer in https://github.com/saltstack/salt-bootstrap/pull/1860
- Update the bootstrap script to work with final onedir releases. by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1863
- Install Oracle's EPEL repo on Oracle Linux 7 and 8. by @pjcreath in https://github.com/saltstack/salt-bootstrap/pull/1839
- onedir install - correct version regex by @jeff350 in https://github.com/saltstack/salt-bootstrap/pull/1868
- Ensure the REPO_ARCH for Arm64 is correct. by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1867

## New Contributors

- @eozer made their first contribution in https://github.com/saltstack/salt-bootstrap/pull/1860
- @jeff350 made their first contribution in https://github.com/saltstack/salt-bootstrap/pull/1868

**Full Changelog**: https://github.com/saltstack/salt-bootstrap/compare/v2022.08.13...v2022.10.04

# v2022.08.13

## What's Changed

- Fix test-windows workflow powershell syntax & Run pre-commit when resolving conflicts on the release workflow by @s0undt3ch in https://github.com/saltstack/salt-bootstrap/pull/1857
- Update `*.sha256` files when merging develop into stable by @s0undt3ch in https://github.com/saltstack/salt-bootstrap/pull/1859

**Full Changelog**: https://github.com/saltstack/salt-bootstrap/compare/v2022.08.12...v2022.08.13

# v2022.08.13

## What's Changed

- Fix test-windows workflow powershell syntax & Run pre-commit when resolving conflicts on the release workflow by @s0undt3ch in https://github.com/saltstack/salt-bootstrap/pull/1857
- Update `*.sha256` files when merging develop into stable by @s0undt3ch in https://github.com/saltstack/salt-bootstrap/pull/1859

**Full Changelog**: https://github.com/saltstack/salt-bootstrap/compare/v2022.08.12...v2022.08.13

# v2022.08.12

## What's Changed

- Update README.rst with 2022.05.19 release sha256sum by @github-actions in https://github.com/saltstack/salt-bootstrap/pull/1832
- ci(eol): remove `fedora-34` and `3002` by @myii in https://github.com/saltstack/salt-bootstrap/pull/1835
- ci(freebsd): replace `13.0` with newly released `13.1` box by @myii in https://github.com/saltstack/salt-bootstrap/pull/1836
- feat: add support and update CI for openSUSE Leap 15.4 by @myii in https://github.com/saltstack/salt-bootstrap/pull/1837
- Rename to py39-salt, Python 3.9 is default version on FreeBSD by @krionbsd in https://github.com/saltstack/salt-bootstrap/pull/1842
- Adding bits to install Salt packages built using Tiamat. by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1819
- replace all references of tiamat to onedir by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1845
- use SHA-256 key for Red Hat / CentOS relesaes 9 and over. by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1846
- Add version for Salt version 3005. by @garethgreenaway in https://github.com/saltstack/salt-bootstrap/pull/1848
- Automate the release process by @s0undt3ch in https://github.com/saltstack/salt-bootstrap/pull/1849
- Tighten Release Workflow Permissions & Rework the CI Workflow by @s0undt3ch in https://github.com/saltstack/salt-bootstrap/pull/1850
- Fix Release Workflow by @s0undt3ch in https://github.com/saltstack/salt-bootstrap/pull/1852
- Fix parameter name for the changed files action by @s0undt3ch in https://github.com/saltstack/salt-bootstrap/pull/1853
- Specify the repository by @s0undt3ch in https://github.com/saltstack/salt-bootstrap/pull/1854

**Full Changelog**: https://github.com/saltstack/salt-bootstrap/compare/v2022.05.19...v2022.08.12

# v2022.05.19:

- Fix situations where the registry key for root_dir does not exist
  on Windows (twangboy) #1828
- Add Ubuntu 22 support (krionbsd) #1820
- Add Fedora 36 support (myii) #1818

# v2022.03.15:

- Add detection and functions for AlmaLinux and Rocky Linux (myii) #1803
- Copy configs to correct config dirs (v3004+) (dafyddj) #1798
- Support Non-LTS Ubuntu 21.04 & 21.10 (blindpirate) #1793
- Use native repositories for Debian 11 (jpacura) #1615
- Keep all command-line parameters when UAC is enabled (Simon-TheUser) #1613
- Add support for Raspbian (Jille) #1612
- Add openrc to alpine:latest dependencies (krionbsd) #1609
- Add CentOS 7 base key (bryceml) #1608
- Fix git master install on alpine 3.12+ (Nascire) #1604
- Sort help alphabetically (krionbsd) #1601

# v2021.09.17:

- Re-add Ubuntu-16 support as it's still supported with 3001 and 3002 (krionbsd) #1594
- Add oncoming 3004 release (krionbsd) #1593

# v2021.09.14:

- Update latest Salt version in README (krionbsd) #1588
- Make Python 3 the default (bryceml) #1577
- Don't output info if using the default -x value (bryceml) #1587

# v2021.08.19:

- Update README with instructions to use salt-bootstrap custom version (ari) #1580
- Remove unsupported versions (bryceml) #1578
- Update FreeBSD default Python version to 3.8 (myii) #1574

# v2021.06.23:

- Use salt.list instead of saltstack.list (bryceml) #1563
- Use fetch_url function for curl (xeacott) #1562
- Add Ubuntu 21.04 support (krionbsd) #1559
- Remove python2-futures package for ArchLinux (myii) #1546

# v2020.03.02:

- Debian 11 (bullseye/testing) support using Debian 10 packages (jpacura, bryceml) #1514
- Fix bootstrap on Gentoo (ijansky) #1516 #1518
- Fix project URLs (bryceml) #1526
- FreeBSD also needs the \_PKI_DIR reset (krionbsd) #1523
- Fix openSUSE Tumbleweed support. (myii) #1525
- Fix Debian and Ubuntu version support. (jpacura) #1529
- Powershell: Implement configure only option (for Vagrant). (dafyddj) #1530
- Powershell: Handle Vagrant's `grains_config` option. (dafyddj) #1520
- apt-key is deprecated on Debian 10+ and Ubuntu 20+ (bryceml) #1533
- Fix python Tornado on FreeBSD. (krionbsd) #1522

# v2020.10.20:

- Add support to allow bootstrapping Salt 3002 (s0undt3ch) #1506

# v2020.10.19:

- Fix v3000+ with git install on FreeBSD (krionbsd) #1487
- Update README giving ONE example of WINDOWS bootstrapping. Default to python3 instead of
  python2. (noelmcloughlin) #1496
- Support git and stable salt-bootstrap on Gentoo. (ijansky) #1500
- Add support for Linux Mint 20. (taigrr) #1502
- Adding missing functions for Red Hat 8. (mbochenk) #1489
- Allow pinning minor 3xxx versions. (max-arnold) #1491

# v2020.06.23:

- Fix for Cumulus Linux 4.1 (darylturner) #1474
- Fix file download exit code, improve error message on failed download (bryceml) #1478
- Add support for Ubuntu 20.04 (bryceml) #1479
- Default Ubuntu 20.04 to Py3 since there isn't a Py2 release for it (bryceml) #1480
- Warn instead of exit when using -R and -x python3 on centos to allow installing python3
  versions of salt on centos from other repos.  Old unsupported releases probably need to
  manually install epel-release before running the bootstrap script for versions before 2018.3.5
  and before 2019.2.1 (bryceml) #1482
- Start maintaining .sha256 files for the bootstrap script

# v2020.05.28:

- Fix Opensuse Tumbleweed (noelmcloughlin) #1441
- Remove Debian 8 from Python 3 supported list (jay1648) #1448
- Fixed deps parsing for FreeBSD git installs (cedwards) #1462
- Added support for the upcoming Sodium release (s0undt3ch) #1466
- Fixed KDE Neon detection (ender8282) #1466
- Updated README python 2 and 3 installations (gdebunne) #1466
- Updated README and CONTRIBUTING to prefer Salt's master branch (DmitryKuzmenko) #1466
- Fixed IUS repo addresses (oeuftete) #1469
- Updated tests to assert target Python and Salt versions (s0undt3ch) #1470
- Fixed Amazon 2 -x support (s0undt3ch) #1470
- Fix Fedora stable installs for older releases (s0undt3ch) #1470
- Fix CentOS 8 installations (s0undt3ch) #1470
- Default Debian 10 to Py3 (s0undt3ch) #1470
- Fix Arch Linux installs (s0undt3ch) #1470

# v2020.02.24:

- Fix SLES 15 install (max298) #1431
- Fix 3000(Neon) stable install (sblaisot) #1433
- Fix Amazon Linux Py3 install (s0undt3ch) #1434

# v2020.02.04:

- Add support for the Salt Neon(3000) release (s0undt3ch) #1424
- Drop support for Fedora \< 30 (s0undt3ch) #1424
- Drop support for Debian \< 8 (s0undt3ch) #1424

# v2020.01.29:

- FreeBSD fixes (cedwards) #1413
- Support the upcoming Neon release (s0undt3ch) #1420

# v2020.01.21:

- FreeBSD fixes (kgbsd) #1376
- Fix macOS support (s0undt3ch) #1397

# v2019.11.04:

- Fix busybox mktemp compatibility (stanzgy) #1369
- Install debian 10 packages on debian 10 instead of 9 (kiemlicz) #1375
- move centos to python36, use python specified by -x (Ch3LL,bryceml) #1380
- Add debian 10 git install support (Ch3LL) #1378

# v2019.10.03:

- Fix possible typo with `gnupg-curl` vs `gnupg curl` (zahiar)
- Install only python3 packges if requested on ubuntu (noelmcloughlin) #1356
- Fixing debian wheezy (bryceml) #1359
- Fixed Amazon Linux 2 detection when lsb_release is installed (jars99) #1361
- Mac OS Support (felippeb) #1363 #1364 #1365 #1366

# v2019.05.20:

- Allow stable version selection for amazon linux (puluanau) #1328
- FreeBSD 12 support (sticky-note) #1329
- Apt wait for lock modification (ripesensor) #1335
- Opensuse 15 Git installation fixes (s0undt3ch) #1340 #1341
- Amazon Linux Image fixes (nshenry03) #1343
- apt_key_fetch fixes (greut) #1344
- CentOS Git and PIP installation m2crypto fixes (s0undt3ch) #1347
- CI process enhancements/fixes (s0undt3ch) #1347

# v2019.02.27:

- Add support for bunsenlabs devian derivative (kevinquinnyo) #1300
- Add support for TurnKey devian derivative (dafyddj) #1313
- Fix BSD develop install (hackacad) #1316
- Ensure python-concurrent.futures is installed for Ubuntu (garethgreenaway) #1321

# v2019.01.08:

- use official amazon linux 2 repo for amazon linux 2 (mchugh19) #1287
- Add release info to applicable docs (rallytime) #1292
- Modify wait_for_apt function (ripesensor) #1291
- Add support for LinuxMint 19 (darkocerdic) #1289
- FIX #1237 SmartOS should use pkgin show-deps (sjorge) #1283
- Fedora: Reduce DNF calls to 2 during install_dep phase (The-Loeki) #1278

# v2018.08.15:

- Add tests using kitchen-salt (gtmanfred) #1279
- Add python-futures to Py2 installs (gtmanfred) #1279

# v2018.08.13:

- Fedora Py3 fixes (The-Loeki) #1273
- Handle commented lines in the requirements files for pip pkgs (rallytime) #1271
- Remove typo: extra 'c' was accidentally added in #1269 (rallytime) #1270
- \[Arch\] Add python2-futures to list of pkgs on git install (rallytime) #1269
- Fix undefined variable warn_msg on amd64 (alexandruavadanii) #1268
- SLES12SP changed packages git to git-core and libzmq3 to libzmq4 (mfapouw) #1266
- Add opensuse 15 specific installation functions (rallytime) #1263
- Remove support for openSUSE Leap 42.2 (rallytime) #1262
- Remove support for Fedora 26 (rallytime) #1261
- Remove support for Ubuntu 17.10 (rallytime) #1260
- Ensure pipe is absent before mkfifo/mknod (noelmcloughlin) #1256
- fix for opensuse15 if no lsb_release pkg (noelmcloughlin) #1255
- Fix Up ShellCheck errors/warnings for latest version of shellcheck (rallytime) #1253
- Remove daily install option on Ubuntu system (icy) #1250
- Add python 3 support for Ubuntu 18 (rallytime) #1248
- Return immediately if apt-get fails (icy) #1247
- Disable shell error about unbound variable during daily install (icy) #1246
- OpenSuse_Leap_15.0 saltstack repo support (noelmcloughlin) #1244
- Add Python3 package support for Debian 9 (rallytime) #1243
- Add Python3 package support for CentOS 7 (rallytime) #1242
- Shellcheck fixes found when running latest version (rallytime) #1239
- Add Python3 package support for Ubuntu 16.04 (rallytime) #1238
- Fix the variable ref from #803 (rallytime) #1229
- Add Ubuntu 18.04 support (rallytime) #1228
- Call \_\_git_clone_and_checkout directly (jheidbrink) #1226
- Fix for silently ignored version argument on CentOS/RHEL (pjcreath) #1210

# v2018.04.25:

- Install py-tornado4 for FreeBSD. (abednarik) #1219
- Remove COPR repos configuration for Fedora (vutny ) #1211
- Fix for silently ignored version argument on CentOS/RHEL (pjcreath) #1210
- Use integer parameter for sleep command (bdrung) #1205
- Add 2018.3 branch to list of stable options (rallytime) #1204
- If installing with -P, install tornado\<5.0. (rallytime) #1203
- Add M2Crypto to python27 centos 6 bootstrap install (Ch3LL) #1201
- Update README to include mention of bootstrap-salt.ps1 for Windows (rallytime) #1200
- Port spelling fixes from change in Salt to Bootstrap (rallytime) #1199
- Add M2Crypto package back to git install functions (rallytime) #1198
- OpenBSD has a cdn which handles selecting the best mirror (jasperla) #1197
- Change gnupg2 pacakge to gnupg for non-LTS versions of Ubuntu (rallytime) #1196
- Install swig30 as freebsd dep instead of swig. (abednarik) #1191
- make salt-syndic optional on salt bootstrap (sybix) #1190
- Add \_\_wait_for_apt function: avoid locking on the apt-get process (rallytime) #1186
- Update the README.rst file with some grammatical changes (rallytime) #1185
- Update Fedora support: 25 is EOL, 27 is supported (rallytime) #1184
- Add a note about the use of sudo when running commands to README (rallytime) #1183
- Adding support for minor release pinning on AWS Linux (cmclaughlin) #1182
- Wait for zypper processes to finish before calling zypper again (rallytime) #1181
- only install ca-certificates on opensuse if it isn't already installed (gtmanfred) #1179

# v2017.12.13:

- Use HTTPS URL for OpenSuse's saltstack repo (gdm85) #1174
- Respect disable repos (-r) option on OpenBSD (eradman) #1171
- Fix #1168 : -b option causes error (vutny) #1170
- Fix fatal error with using the -b option. (arizvisa) #1169
- Devuan support (ymasson) #1165
- Fix yum repo on AWS Linux (cmclaughlin) #1164
- Use suse repo to install packages, rather than defining them (rallytime) #1157
- Remove patch-level-1 specific code for SLES installs (rallytime) #1156
- priority sort fedora-release (toanju) #1153
- Declare EOL for SUSE Linux Enterprise Server releases (vutny) #1150
- Fix #1142: allow git install on Raspbian 9 (vutny) #1146
- Follow symlinks when parsing distro release files (vutny) #1145
- fedora: use dnf-utils for F26 and above (toanju) #1144
- Declare EOL for openSUSE LEAP 42.1 (vutny) #1143
- Fix #1137: import GPG key through an HTTP(S) proxy (vutny) #1139
- Fix #1138: git install on Debian/Ubuntu various arches (vutny) #1141
- Declare EOL for openSUSE releases earlier and including 13.X (vutny) #1136
- Update Fedora support: 24 is EOL (rallytime) #1134

# v2017.08.17:

- Add new authors (rallytime) #1130
- README: Fix typo and Table of Contents for Debian section (vutny) #1129
- Reduce the # of days an issue is stale to 6 months (rallytime) #1125
- Only install Python version if "-y" is defined (rallytime) #1124
- Allow powershell bootstrap script to specify PY2 or 3 (rallytime) #1123
- Remove the test that checks if the EPEL RPM was installed (amendlik) #1122
- added latest version string of nitrogen release 2017.7 (sourceindex) #1120
- use versions specified in base.txt when doing pip installs (aflat) #1116
- Remove pip install requirement on Fedora git installs (rallytime) #1114
- Introductory support for Debian 10 (Buster) (rallytime) #1113
- Add Debian 9 support using official repo.saltstack.com packages (rallytime) #1111
- Fix 1105 (vernondcole) #1110
- Move SUSE specific function closer to related code (vutny) #1107
- Update Authors file (rallytime) #1103
- Fix ubuntu 16.04 LTS installation (BlaineAtAffirm) #1102
- Add debian_codename_translation function, similar to Ubuntu (rallytime) #1101
- Add the CODE_OF_CONDUCT.md file (rallytime) #1100
- Update Debian and Ubuntu service file paths to be consistent with salt (rallytime) #1099
- Add hash verification information to installation instructions (rallytime) #1098
- Fix installing salt-cloud package on Arch Linux (rallytime) #1097
- Support bootstrapping on upcoming Debian GNU/Linux 9.0 (vutny) #1096
- Removes faulty explicit version ordering (absolutejam) #1095
- Remove configuring EPEL repo for Amazon Linux (vutny) #1093
- Fix -j/-J (JSON configs) options for Debian 8 (vutny) #1092
- Fix #1035: detect and log errors earlier (vutny) #1091
- Update AUTHORS file (rallytime) #1089
- Autounmask as separate step (decomposite) #1088
- Ensure presence of CONFIG_PROTECT_MASK files (decomposite) #1087
- Update Fedora support: 23 is EOL now. (rallytime) #1084
- Fix the -R option on Debian/Ubuntu (rallytime) #1082
- Declare End-Of-Life for Ubuntu 12.04 LTS (vutny) #1080

# v2017.05.24:

- Use freebsd repo to query for salt dependencies (Ch3LL) #1076
- Allow amazon to work with python2.7 on installs over 2016.11 (Ch3LL) #1073
- ensure sles12 enables services with stable installs (Ch3LL) #1075
- Declare End-of-Life for RHEL 5 and its variants (vutny) #1070
- Fix configuring SaltStack's repo URL for RHEL variants (vutny) #1068
- Add Manjaro as Arch derivative (luthes) #1063
- Add "unmarkComment" option to probot-stale config (rallytime) #1064
- Properly detect all supported Debian GNU/Linux derivatives (vutny) #1062
- Archlinux must always update (gtmanfred) #1060
- Alpine: fix adding, checking and running Salt Syndic in stable mode (vutny) #1059
- Add KDE neon... (EHJ-52n) #1058
- Update probot-stale message formatting. (rallytime) #1057
- Fix `git` bootstrap mode for CentOS (vutny) #1054
- update install_freebsd_10_stable to use FreeBSD repo (bytesatwork-xx) #1053
- Support OpenBSD 6.1 (eradman) #1048
- Update daysUntilStale value in probot-stale config (rallytime) #1055
- Add ability to install and use a different python version when installing salt (Ch3LL) #1049
- Add non-LTS type support for Ubuntu 17.04 (rallytime) #1051
- Allow -R option to work for Debian/Ubuntu (rallytime) #1045
- Adjust "daysUntilStale" variable to 190 days. #1047
- Reduce the number of days an issue is considered "stale" (rallytime) #1046
- Alpine: fix bootstrapping from Git -- install OpenRC initscripts (vutny) #1044
- Add probot-stale config file (rallytime) #1042
- Shallow cloning and Python setup fix for BSD (amontalban) #1040
- Fix not needed quoting for salt/salt-bootstrap#1026 (amontalban) #1039
- Update README file with supported release documentation (rallytime) #1034
- Remove \<\<\< bashism (The-Loeki) #1032
- \[-R option\] Fix logic error where we trying to enable epel with -R (rallytime) #1033
- Alpine: check Salt services have been enabled to start on boot (vutny) #1031
- AWS Linux Native Support (bkruger99) #1022
- Correct package name for FreeBSD installation (amontalban) #1030
- README: describe architectures support for Salt deps on Linux distros (vutny) #1029
- This commit addresses some of the issues in salt/salt-bootstrap#996 (amontalban) #1026
- Add support for stable installation on Alpine Linux release 3.5 (vutny) #1028
- Alpine Linux: fix installation of multiple pkgs ("stable" bootstrap) (vutny) #1027
- Add Void Linux support (ndrwdn) #1025
- RHEL6: disable stdin to fix shell session hang on killing tee pipe (vutny) #1018
- Adding 2016.11 to stable version (ashokrajar) #1017
- Update bootstrap-salt.sh (caelor) #1015
- Alpine Linux support #1009 (ek9) #1010
- Add Table of Contents in README (vutny) #1014

# v2017.01.10:

- Update AUTHORS.rst with new contributors (rallytime) #1011
- fix bootstrap in Arch Linux by updating package name from salt-zmq to salt (ek9) #1007
- Add python-systemd package to debian 8 git install (rallytime) #1003
- Updated supported versions for Ubuntu: 12.04, 14.04, 16.04, and 16.10 (best effort) (rallytime) #1002
- Add "yakkety" to ubuntu_codename_translation function (rallytime) #1001
- Update supported versions for Fedora: 23, 24, and 25. (rallytime) #1000
- Handle renaming of gnupg-curl to gnupg1-curl for Ubuntu 16.10 (marco-m) #998
- fix systemctl path (dmitrievav) #997
- Drop unnecessary workarounds (creating directories) for early releases (vutny) #995
- Let's detect newly released Salt 2016.11 stable release (vutny) #994
- Adjust code examples to use the actual bootstrap-salt.sh file name (rallytime) #993
- Install TLS certs before cloning git repo via https (vutny) #991
- Remove fix me comment and fix systemsmanagement link (rallytime) #990
- Correct usage description about "config only" mode (vutny) #989
- Fix overwriting Minion config from temporarily directory (vutny) #988
- Configure Salt components after the dependencies installation (vutny) #987
- Add CloudLinux support (rallytime) #986
- Apply the insecure flag to git as well (cachedout) #981

# v2016.10.25:

- Update AUTHORS.rst with new contributors (rallytime) #978
- Let's start detecting the upcoming Debian 9 (Stretch) (lhost) #975
- FreeBSD: set \_SALT_ETC_DIR directory to match ports (eradman) #970
- Update OpenBSD 6.0+ provisioning (eradman) #969
- adds supports for Cumulus Linux (plumbis) #967
- Run "pip install -U futures" for SmartOS git install (rallytime) #966
- Change /pkg/rpm/ to /pkg/deb/ in install_ubuntu_git_post func (rallytime) #965
- SUSE: Refactor systemsmanagement_saltstack repo checks to be DRY (rallytime) #964
- Fix detection of EPEL repository with not-expired metadata (sp1r) #963
- Display warning message about deprecating the `-G` option (vutny) #958
- Allow correct salt paths to be used when -c is passed (justinta) #955
- Fix issues with replacing configs when python3 is default in os. (fizmat) #954
- Remove m2crypto package installs (rallytime) #951
- Try to install SP4 packages on SLE 11 when SP version is older (rallytime) #950
- Add python-futures package to install_centos_git_deps (rallytime) #948
- Add /etc/portage/package.accept_keywords to CONFIG_PROTECT_MASK (rallytime) #947
- Deprecate `-G` option: use `https` scheme for GitHub by default (vutny) #945
- \[SECURITY\] Properly handle GnuPG keys for APT repositories (vutny) #940

# v2016.08.16:

- Ubuntu git mode: install all deps from SaltStack corp repo by default. (vutny) #936

# v2016.08.15:

- Remove chris-lea python-zmq repo. (rallytime) #929
- Disable the '--enablerepo=${\_EPEL_REPO}' part of yum install cmds when passing -R/-r. (rallytime) #928
- Fix grep pattern in `__check_services_sysvinit`. (vutny) #927
- Missing python dependency for salt-cloud added. (toanju) #925
- Fix git install mode when using commit hash with `-g` option. (vutny) #922
- Install `salt-cloud` package with `-L` option in `stable` mode. (vutny) #919
- Fix bootstrapping from Git on CentOS7 when `systemd` is not running. (vutny) #915

# v2016.07.07:

- Add new contributors to authors list. (rallytime) #910
- Split up python-requests and python-msgpack packages for newer Fedora. (rallytime) #909
- Fix typo in repository configuration for FreeBSD. (ekollof) #907
- Make sure $STABLE_REV is set before setting up SaltStack repo. (rallytime) #906
- Remove tests written question from template. (rallytime) #904
- Adding support for Linux Mint 18 (based on Ubuntu 16.04). (eliezerlp) #902
- Allow git installation for SLES 12. (rallytime) #903
- Set repo_arch for raspberry pi installs. (mrichar1) #899
- Change temporary directory for storing executable to C:\\Windows\\Temp. (themalkolm) #897
- add apt-transport-https for ubuntu. (epcim) #896
- Fix expanding shell script position parameters with nounset enabled. (vutny) #895
- RFC: Add tests for bootstrap-salt.ps1. (themalkolm) #893
- Keep original name of salt executable. (themalkolm) #857

# v2016.06.27:

- Fix race condition when doing one-liner bootstrap. (vutny) #889
- Add space back in between 'install' and '--install'. (rallytime) #890

# v2016.06.24:

- Save invocation command and arguments into variables. (jfindlay) #885
- Update the authors list with new contributors. (rallytime) #884
- Add option to make setup.py install quiet. (nasenbaer13) #865
- Fix lint. (jfindlay) #881
- Add -R option to allow a custom repo URL. (rallytime) #877
- Exclude path of script when called from another dir. (l2ol33rt) #871
- Print invocation info. (jfindlay) #869
- Always refresh the Arch Linux keyring if needed. (cachedout) #868
- Ubuntu 16.04 LTS Xenial Support. (notpeter) #852
- Install Salt packages from repo.saltstack.com on Debian 7 "Wheezy". (vutny) #864
- Drop support for Debian 6 old-old-stable "squeeze": reached end-of-life. (vutny) #860
- Removed ubuntu version restriction for apt-get update. (marccardinal) #859
- Fix bootstrapping from git on Debian 8 by installing latest `tornado` via pip. (vutny) #828
- Add the ability to override master and/or minion configs from CLI. (rallytime) #841
- Don't sleep 11 seconds if the user allowed overwrite of config files. (poelzi) #832

# v2016.05.11:

- Only overwrite the minion config file if '-C' is passed. Otherwise, preserve it. (rallytime) #848

# v2016.05.10:

- Removed libzmq4 and forking-deamon-patch for Opensuse13. (jtand) #840
- Ubuntu 12.04 needs to be updated before installing packages. (jtand) #829
- Always download and install *latest* `epel-release` package on RHEL systems. (vutny) #825
- Fix Amazon Linux EOL check. (vutny) #818

# v2016.04.18:

- Add support for openSUSE Leap. Thanks Roman Inflianskas(rominf). #693
- Fix missing deps installation on Debian. Thanks  Steve Groesz(wolfpackmars2). #699
- Update SaltStack repo location and latest version for Windows. (brandon099) #711
- Better EPEL repository detection on RHEL and CentOS. (vutny) #717
- Fix git invocation fail when `man` command is not available. (vutny) #718
- Fix `epel-release` package installation on CentOS/RHEL 5. (vutny) #719
- Removed deprecated cli option. (abednarik) #705
- Remove RHEL optional repo check and enable. (vutny) #720
- Remove SaltStack COPR repository configuration for CentOS/RHEL5. (vutny) #721
- Add opensuse_Tumbleweed support. (aboe76) #725
- Sometimes bootstrap doesn't install zmq. (jtand) #726
- Process -s (default sleep for service restarts) in bootstrap-salt.sh. (hipikat) #692
- Minion keys and /etc/salt/minion should be overwritten on -C. (cro) #541
- Fix for -C (\_CONFIG_ONLY). (beaucephus) #544
- Fix when using upstream tags. (The-Loeki) #564
- COPR project moved. (rmohr) #738
- Update license year range. (pra85) #743
- Use POSIX-Compliant Command-Exists Test. (kojiromike) #741
- Add -f option to force shallow cloning. (eyj) #660
- add SLE 12 support, fix OpenSUSE support. (grep4linux) #748
- Fix CentOS git setup.py syntax error upon installation. (The-Loeki) #746
- Enable shallow cloning for version branches by default, not only tags. (vutny) #750
- do not install copr repo on fedora 22+. (toanju) #751
- Add support for pegged versions on YUM based OS'ses through repo.saltstack.com. (The-Loeki) #685
- fix for FreeBSD 11 CURRENT install functions. (serge-p) #723
- Don't add zypp repo if it already exists. (furlongm) #731
- switch repositories for suse and sles fixes `#706`\_. (aboe76) #734
- Reformat and correct usage instructions. (vutny) #755
- fixed missing repo for suse 12. (aboe76) #756
- fix for Amazon Linux. (shawnbutts) #700
- adding support for OpenBSD distribution. (serge-p) #722
- fixing syntax errors. (beardedeagle) #760
- Import CentOS 7 GPG key on RHEL for installing base dependencies from Salt corp repo. (vutny) #765
- Fix multiple lint errors (shellcheck) and make some refactoring. (vutny) #768
- Fix sleep time option to recognize a numeric argument. (vutny) #771
- Update README. (vutny) #787
- get tornado from pip on a fedora git install. (jfindlay) #785
- Remove the Saltstack repo's alias. (cro) #794
- Ability to change cache dir. (clarkperkins) #761
- Add config_freebsd_salt func so freebsd puts cfgs in the right place. (ryanwalder) #779
- Allow archive versions. (clarkperkins) #769
- Lack of HTTPS for RPM packages. (jaredestroud) #783
- Ability to change cache dir. (clarkperkins) #761
- Bootstrap on Docker. (vutny) #793
- add downstream pkg repo for SUSE. (jfindlay) #791
- Fixed use of HTTP over HTTPS for anonscm.debian.org. (gdm85) #788
- Bump Salt version to latest stable in PS bootstrap script for Windows. (vutny) #801
- Add an -l option to switch https to http links. (rallytime) #795
- Virtualenv support for Ubuntu. (l2ol33rt) #666
- Lint. (jfindlay) #805
- use portable command check. (jfindlay) #806
- Update epel-release version number (RuriRyan) #809

# v2015.11.09

- Make sure that wget is installed. #868

# v2015.11.04:

- Allow bypassing dependencies installation. Thanks EYJ. #656.
- Add FreeBSD 11 support. Thanks Chris Buechler(cbuechler). #653
- Move RHEL installations to use repo.saltstack.com #674
- Move Debian 8 installation to use repo.saltstack.com #674
- Fix error finding python-jinja2 in RHEL 7. Thanks Rob Eden(hedinfaok). #654
- Move Ubuntu 12 and 14 installations to use repo.saltstack.com #674
- Move FreeBSD installations to use repo.saltstack.com #674
- Use dnf on Fedora 22 and later. Thanks Michele Bologna (mbologna). #665

# v2015.08.06:

- Fix python-requests installations for Ubuntu >= 14.04 LTS. #631, #632, #633
- Install python-crypto from Chris Lea's PPA for Ubuntu \< 14.04
- Exit the git checkout directory before deleting it. Thanks Bret Fisher. #634
- Use prefix /usr for centos git install. Thanks Stanislav B. #638
- Drop Ubuntu EOL versions. All Ubuntu version before 12.04.
- Make sure python-dev is installed wheb trying to install tornado from PyPi. #640

# v2015.07.22:

- Fix tornado installation in Ubuntu. Thanks Yushi Nakai. #627
- Install tornado using pip on Ubuntu for Salt's v2015.8.xx onward stable releases.
- Install requests on Ubuntu from Chris Lea's PPA. #630

# v2015.07.17:

- Make sure setuptools is installed before using it. #598.
- `systemd` is only fully supported from 15.04 onwards. #602
- Fix debian mirrors issue. Thanks Wolodja Wentland(babilen). #606
- Fix python-jinja2 repo move on RHEL6. Thanks lomeroe. #621
- Allow skipping services. Thanks denmat. #455
- Fix missing Debian init script. #607 saltstack/salt#25270 and saltstack/salt#25456
- Fix SmartOS etc path. Thanks Bret Fisher. #624
- Fix possible unbound variable in Gentoo. #625
- Properly detect the git binary in SmartOS. #611

# v2015.05.07:

- Lower required requests version dependency. Use system requests package where possible.
- Allow Ubuntu alternate ppas. Thanks Peter Tripp(notpeter). #563

# v2015.05.04:

- Fix the configuration path for FreeBSD. #567/#552. Thanks Ronald van Zantvoort(The-Loeki).
  \+ Fix non grouping support in POSIX sed. Thanks Ronald van Zantvoort(The-Loeki).
- Add Debian 8 support. Thanks Matt Black(mafrosis)
- Improve Debian version parsing. Thanks Mark Lee(malept)
- Make sure we update packages list one Chris Lea's PPA repository is added.
- Hard code the Debian Squeeze backports to the DE mirror since the main repository is down.
  Thanks @panticz. #589.
- Only install git if not already installed. #560
- Fix openSUSE 13.2 where we need to pass --replaceflags. Thanks Roman Inflianskas(rominf).
  #504.
- Make sure that a recent enough requests package is installed in Debian/Ubuntu.
- Install tornado on git installs for the develop branch if necessary. #580
- Add support for Ubuntu 15.04

# v2015.03.15:

- Add multi-master support. Thanks Fred Reimer(freimer). #555

# v2015.03.04:

- Fix the salt package selection on Arch stable installs.

# v2015.02.28:

- Fix Debian backports repository.

# v2015.02.27:

- Try other tools besides wget when downloading the COPR repo file. Thanks Ronald van
  Zantvoort(The-Loeki)
- No need to install packages from the Unstable repository for debian, use backports. Thanks
  Ari Aosved(devaos)
- Fix an issue in CentOS where the syndic package wasn't being installed(since it's now a
  separate package). Thanks Ronald van Zantvoort(The-Loeki)
- Enable the server-optionals repository for RHEL >= 7
- RHEL/CentOS 5 now uses the COPR repository. #533

# v2015.01.12:

- Add package upgrades support to FreeBSD. Thanks William Eshagh(eshagl).
- Make sure wget is installed on debian bare systems.
- Make sure the Arch pacman database is up to date
- Install `python-hashlib` in CentOS 5 in order to use the COPR repository

# v2014.12.11:

- Enable binary installations on CentOS 7. Thanks ggillies
- Updated the URL for EPEL 7

# v2014.10.30:

- Apply the forking patch to openSUSE git installations.

# v2014.10.28:

- Install the python systemd bindings for Arch and Fedora git installations
- Allow cloning from Salt's git repository using HTTPS. #475

# v2014.10.21:

- Fix path to python on FreeBSD. Thanks Pavel Snagovsky(paha)
- Fix syndic installation on RHEL based installations. Thanks markgaylard
- Properly detect the git checkout `basename` directory instead of hard coding it. Thanks
  Howard Mei(HowardMei).
- Allow installing ZMQ for SaltStack's COPR repository.
- Allow installing ZMQ4/PyZMQ14 from Chris Lea's PPA repository.

# v2014.10.14:

- Fixed a regex issue with matching Salt's tags. Match v2014.7 but not 2014.7 as a valid tag
- Distro Support Added:
- Added Linux Mint 17 support(Thanks Skyler Berg)
- Disrto Suuport Fixed:
- Init pacman keys if not done so previously

# v2014.09.25:

- Properly detect Amazon AMI's >= 2014.9. #468

# v2014.09.09:

- Distro Support Fixes:
- Updated the URL for EPEL 7
- PIP based installations on Ubuntu 10.04 need setuptools installed
- Arch stopped providing the version information on `/etc/arch-release`
- Complete `salt-api` services checking. #450

# v2014.08.30:

- Skip service checks for `salt-api`, since this should be an opt-in service not necessarily
  meant to start at boot time.
- Distro Support Fixes:
- Also install the salt-api service on RHEL based distributions for git based
  installations.
- Properly detect Arch Linux when lsb-release is available
- Updated the URL for EPEL 7

# v2014.08.23:

- Avoid redirect breakage when installing EPEL with rpm on RHEL 5
- Ensure python-apt is installed by the bootstrap script for Debian & Ubuntu minions. Thanks
  @garethgreenaway.
- Don't shallow clone on git versions lower than 1.7.10
- Only shallow clone on git tag based installations
- Configurable Salt repository clone directory for git based installations
- Distro Support Fixed:
- Fixed the URL to download EPEL for Cent 5
- Use the full path to the `chkconfig` binary when checking for services in SysV init
  systems.
- Fixed an issue where the default sleep period(3 secs) on Ubuntu would cause a race
  condition with upstart wherein the package installation would call an upstart start and
  before it could complete, bootstrap would call another. The result was *two* copies of salt
  running which ended up causing a most stubborn bug that's documented in
  https://github.com/saltstack/salt/issues/12248

# v2014.07.29:

- Shallow clone Salt's repository for speed improvements. In case of failure, resume old
  behaviour.
- Fixed bug introduced in 0577622 when salt-api service install and checks were added
- Distro Support Fixed:
- Fixed infinite loop when handling RHEL dependencies. Thanks Dan Mick(@dmick).

# v2014.07.27:

- Amazon Linux AMI 2010.xx is not explicitly not supported.
- Install the `salt-api` scripts if available when the `salt-master` is also installed.
- Added support for a configurable sleep time when starting, restarting and checking for
  enabled services.
- Drop the `tsflags` requirement for RHEL and RHEL based distributions.
- When sorting release files, oracle-release has higher priority than redhat-release.
- Distro Support Fixed:
- Debian >= 7 uses system's python-requests package, not PIP
- Install 'python-zypp' in SuSE and openSUSE(required by Salt's zypper module)
- Only install EPEL on requiring distributions if not already installed
- CentOS 7 now uses systemd and the script now properly handles it
- systemd in openSUSE 12.2 complains if service does not contain ``` .service``         * Properly detect openSUSE using  ```lsb_release
- SLES 11 SP3 ships with both python-M2Crypto-0.22.\* and python-m2crypto-0.21 and we will
  be asked which we want to install, even with --non-interactive. Let's try to install the
  higher version first and then the lower one in case of failure.
- Allow some extra time on RHEL for the optionals repo check in case the repository
  subscription is being managed externally.

# v2014.06.30:

- Distro Support Fixed:
- Bump build/maintenance version for epel-release package. Thanks Gregory Meno(GregMeno)
- Properly detect Amazon Linux AMI when using `lsb_release`
- Fix `tsflags` installation.

# v2014.06.28:

- Fixed `tsflags` packages detection for RHEL and Oracle Linux 6.5

# v2014.06.21:

- Also export the HTTPS proxy environment variable. Thanks Giuseppe Iannello(gianello).
- Distro Support Fixed:
- Improve Oracle Linux Server detection
- Overcome the Oracle Linux awkwardness. `--enablerepo=XYX` disables ALL OTHER REPOS!!!!
- Oracle Linux also support testing repositories installation

# v2014.06.19:

- Allow passing the master address as an environment variable, `BS_SALT_MASTER_ADDRESS`
- Fixed an issue with the keys pre-seed. We were passing absolute paths where we only needed
  basenames.
- Added HTTP proxy configuration support. Thanks Giuseppe Iannello(gianello),
- Distro Support Added:
- Elementary OS
- RHEL 7 Beta/RC
- Kali Linux. Thanks Valentin Bud(valentinbud)
- Distro Support Fixed:
- Improved RHEL optionals repository detection

# v2014.04.16:

- Fixed a bug for RHEL 6 based distributions where yum-utils was not getting installed.
- Added minor version check for RHEL 6 optional channel.
- Added quotes around "apache-libcloud>=$\_LIBCLOUD_MIN_VERSION" for proper version requirements
  handling.
- Install the python 'requests' package which is now a hard dependency in Salt.
- When installing from a user defined repository add the official one as a remote and fetch
  its tags for proper versioning.
- Distro Support Fixed:
- CentOS netinstall ISO's don't install `chkconfig`
- Improved RHEL optional repository detection. This allows user repository usage, which
  don't need the optional repository support since they usually provide their packages.
- Distro Support Added:
- Oracle Linux
- Scientific Linux

# v2014.03.10-1:

- Distro Support Fixed:
- Fix the Debian services running function

# v2014.03.10:

- Debian based distributions which don't use upstart now also check if the salt services are
  enabled.
- Distro Support Fixed:
- RedHat based distributions now have a proper services enabled checker.

# v2014.02.27:

- Fixed a bug on the services enabled function searching logic.
- Arch, Fedora, openSUSE and SuSE now check for services enabled, if using systemd
- CentOS(and any RedHat based) and Ubuntu now check for services enabled is using upstart
- Distro Support Added:
- Debian 8. Thank You Boris Feld(Lothiraldan).

# v2014.02.19:

- Fixed a problem with the quotes of an error message
- Arch installations now uses the community repository
- Distro Support Fixed:
- Fixed Fedora Git based installations(git was not being installed)

# v2014.02.18:

- Debian based distribution now get a warning stating that NOT starting daemons does not work
  as supposed, mainly because that's the Debian policy.
- Fix bug introduced when implementing the master ip flag. The default minion includes
  directory is `minion.d`, not `minion.conf.d`

# v2014.02.16:

- The script now allows setting up the salt-master address as a separate configuration file by
  passing `-A` to the script.
- Add support to install apache-libcloud by passing the `-L` flag. In some distribution it's
  also needed to pass `-P` because the minimal apache-libcloud version is `0.14.0`. This support
  is still missing for FreeBSD and SmartOS.
- Fixed an issue when copying or moving files. We now test to see if the destination is a
  directory and create a full path from that so that the "do not override" logic works as
  supposed. #294.
- Allow passing additional package names to install while installing Salt's dependencies. #262
- Pass the salt configuration directory, default or from environment variable to the setup.py
  script for git based installations. #305
- Distro Support Fixed:
- FreeBSD `fetch` now has a notion of insecure certificates. Handle this properly. Thank
  You Mike Carlson(m87carlson).
- Arch, openSUSE and SuSE are now upgradable when the `-U` flag is passed.
- Force overwrites now works for existing init.d scripts on CentOS git installations. #259
- Distro Support Added:
- FreeBSD 10 is now also supported. Thank You Mike Carlson(m87carlson).
- Red Had Enterprise Workstation is now supported.

# v1.5.11:

- Fixed an out of scope variable missed when moving functions around.

# v1.5.10:

- Salt no longer has the master branch in git, install from develop as default.
- Installing from Git on Red Hat based distributions now also needs `yum-utils` installed.
- Allow the script to use a different git repository to install from.
- Fixed a bug where a branch name with dashes would be wrongly detected as an option to the
  script.
- Default to secure file downloads(if any).
- Distro Support Fixed:
- Minimal Ubuntu installation might not have upstart installed, fixed.
- FreeBSD now uses the official FreeBSD repository. Thank You Paul Brian(lifeisstillgood)!

# v1.5.9:

- Allow to not start the daemons after bootstrapping salt. This will allow `vagrant-lxc`
  installations,  `debootstrap*`, etc, to finish properly. Thanks Henrik Holmboe (holmboe).
- Distro Support Fixed:
- Salt >= 0.17 requires ElementTree which is on the python standard library after python
  2.6 but openSUSE split that into a separate package.
- Fixed a logic preventing proper Ubuntu bootstrapping on some situations.

# v1.5.8:

- Fixed an Ubuntu regression. `add-apt-repository` is only available on
  `software-properties-common` after 12.10, inclusive. Thanks Diego Woitasen(diegows)

# v1.5.7:

- For RedHat based distributions which rely on `epel`, the user can now pass `testing` to the
  script and `epel-testing` shall be used to bootstrap salt and it's dependencies.
- No full system upgrades, if optional by the distribution, shall be done unless `-U` is passed
  to the bootstrap script(required upgrade procedures must exist on the script, currently Debian
  and RedHat based distributions support system upgrades).
- Fixed an issue where passing BS_KEEP_TEMP_FILES=1 to the script was causing an error. #206.
- Switched FreeBSD default packages repository to PCBSD(http://www.pcbsd.org) and added
  multiple repository support to install salt from the SaltStack's FreeBSD repository.  Thanks
  Christer Edwards(cedwards).
- Improved Gentoo Support. Thanks Elias Probst(eliasp).
- Stop execution soon for end of life distributions or non supported distribution versions.
- Distro Support Fixed:
- Fixed an unbound variable while bootstraping Gentoo.
- Fixed CentOS/RHEL 5.
- Fixed crypto++ compilation. Thanks Kenneth Wilke(KennethWilke)!
- Fixed FreeBSD git installations not pointing to the proper salt configuration directory,
  which on FreeBSD is '/usr/local/etc/salt'.
- Fixed testing installation for Red Hat based distributions. Thanks Jeff Strunk(jstrunk)
- Fixed wrong package name on Arch. Thanks Niels Abspoel(aboe76)
- Make sure the Ubuntu universe repository is enabled. Thanks Karl Grzeszczak(karlgrz).
- Fixed SmartOS installation. Thanks Matthieu Guegan(mguegan).

# v1.5.6:

- If there's a `grains` file on the provided temporary configuration directory, move it to the
  proper place while moving the minion configuration file.
- Gentoo bootstraps can now use a bin host to provide binary packages, just set the
  `BS_GENTOO_USE_BINHOST` environment variable.
- If `BS_KEEP_TEMP_FILES=1` is found on the environment, the script will copy the files instead
  of moving them.
- There were still some `mv` and `cp` occurrences which were not using their `{move,copy}file`
  replacements which ended up on now respecting the "Do not override existing configuration"
  feature.
- Distro Support Fixed:
- Arch now upgrades it's system package properly as suggested on their mailing list.
- Arch now moves back any configuration files provided by the user renamed by pacman on the
  installation process.
- Fixed SmartOS detection(was being detected as Solaris) and bootstrapping. Fixed SmartOS
  different gcc package names for different package sets.
- Fixed FreeBSD git based installations(no rc.d scripts were available).
- Fixed FreeBSD not re-evaluating the `PKI_DIR` variable since the `SALT_ETC_DIR` was
  redefined.
- Distro Support Added:
- Linux Mint. Thanks Alex Van't Hof(alexvh)!
- Linaro.

# v1.5.5:

- Fixed a variable error in the new pre-seed feature.
- Fixed the destination path to where the pre-seed minions keys should be copied.
- Debian installations now use SaltStack's repository.
- Configuration files can now be passed as an URL to a compressed file. Thanks Geoff Garside!
- Distro Support Fixed:
- Debian's optional ZMQ3 support was fixed (libzmq3 has moved from experimental to
  unstable).
- Ubuntu Lucid Daily PPA
- SmartOS no longer ignores $SALT_ETC_DIR. Matthieu Guegan!
- FreeBSD no longer ignores $SALT_ETC_DIR. Thanks Geoff Garside!
- FreeBSD does not try to install pkgng if pkg is installed. Thanks Geoff Garside!
- SunOS (Make use of XPG4 binaries on SunOS). Thanks Matthieu Guegan!
- openSUSE (Don't fail if only one of the repositories failed to update)
- Arch (Fixed the GPG issues for git installations)
- Distro Support Added:
- Gentoo. Thanks kaithar!

# v1.5.4:

- Fixed an issue we had when /proc/cpuinfo had more than one CPU. Detected on AMD CPUs.
- OpenSUSE 12.3 uses lsb_release. Fix the returned distro name "openSUSE project" to "openSUSE"
  which the script handles.
- Added an custom move function which will only override if required and if we permit it.
- Implemented the necessary function to pre-seed minion keys on a salt master as an optional
  argument.
- Distro Support Fixed:
- FreeBSD (Don't let the script fail if PACKAGESITE is not set)
- Debian Stable installations (the function search was not working as supposed)
- Distro Support Added:
- Ubuntu 13.04 (Was disabled because of a bad beta1. Fixed in beta2)

# v1.5.3:

- Return 0 or 1 from functions
- Convert several pipes into a single awk call
- Fixed `/etc/os-release` parsing
- Fixed `config_salt()`
- Distro Support Fixed:
- EPEL-based installations (CentOS, Amazon Linux, RedHat)
- SuSE/OpenSUSE (problem running the script twice, ie, existing `devel_languages_python`
  repository)
- SuSE 11 SP1 (pip based install and config trigger)
- Distro Support Added:
- Debian 7 (Only git installations at the moment)

# v1.5.2:

- Fix issue with Travis testing (it installs it's own ZeroMQ3 lib
- Allow setting the debug output from an environment variable
- Fix an escape issue in the `printf` calls used in our echo calls
- Don't overwrite files (`config`, `init.d`, etc). Use a specific flag to force overwrites.
- Distro Support Fixed:
- Ubuntu daily installs.
- Distro Support Added:
- Trisquel 6.0 (Ubuntu 12.04)

# v1.5.1:

- Improved unittesting.
- Starting daemons.
- Make sure that daemons are really running.
- For the users to make the choice if installing from PIP (if required since there aren't system
  pacakges).
- Fixed salt's git cloning when the salt git tree is already present on the system.
- Distro Support Fixed:
- Debian 6
- Ubuntu 12.10
- CentOS
- Distro Support Added:
- SuSE 11 SP1/11 SP2
- OpenSUSE 12.x

# v1.5:

- First stable version of the script
- Support for:
- Ubuntu 10.x/11.x/12.x
- Debian 6.x
- CentOS 5/6
- Red Hat 5/6
- Red Hat Enterprise 5/6
- Fedora
- Arch
- SmartOS
- FreeBSD 9.0
