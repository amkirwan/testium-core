### 1.10.0

* Revert "Merge pull request #39 from anil-groupon/pass-debug-port" - **[@jkrems](https://github.com/jkrems)** [#40](https://github.com/testiumjs/testium-core/pull/40)
  - [`a7b2116`](https://github.com/testiumjs/testium-core/commit/a7b21161d6aacf2ecc21f45bf5d0806f3e5bed38) **fix:** Revert "Merge pull request #39 from anil-groupon/pass-debug-port"
  - [`ee2e251`](https://github.com/testiumjs/testium-core/commit/ee2e251f604c1151861c015748c950c48aa92994) **feat:** reimplement getChromeDevtoolsPort
  - [`30e3e9a`](https://github.com/testiumjs/testium-core/commit/30e3e9ae458ce3f66f31100dbaf01345ef6b70fb) **feat:** Add debug log for devtools port


### 1.9.0

* Pass remote debugging port for chrome - **[@anil-groupon](https://github.com/anil-groupon)** [#39](https://github.com/testiumjs/testium-core/pull/39)
  - [`209ebae`](https://github.com/testiumjs/testium-core/commit/209ebae6dd8751e233a646655f2ea23c9a8eaa32) **feat:** Pass remote debugging port for chrome
  - [`2274697`](https://github.com/testiumjs/testium-core/commit/227469762a78c5a749a8f060f63a5d21d53cab4c) **chore:** handle review comments
  - [`c942a21`](https://github.com/testiumjs/testium-core/commit/c942a21c0260788553c2fbdca6ca8fcdf32914d8) **chore:** PR review comment
  - [`115d0c7`](https://github.com/testiumjs/testium-core/commit/115d0c7d6f0665d019c1616ec608bf7c2ac9a9ef) **chore:** remove check for the config flag


### 1.8.1

* chrome --no-sandbox when run as root - **[@dbushong](https://github.com/dbushong)** [#38](https://github.com/testiumjs/testium-core/pull/38)
  - [`a1af370`](https://github.com/testiumjs/testium-core/commit/a1af370bbee31d8639e100d4b7278cc05a6c41d8) **fix:** chrome --no-sandbox when run as root


### 1.8.0

* use chromedriver directly without jar - **[@dbushong](https://github.com/dbushong)** [#37](https://github.com/testiumjs/testium-core/pull/37)
  - [`f5c9220`](https://github.com/testiumjs/testium-core/commit/f5c9220cf823656dbf6de9cf0b1e745e3787e5c3) **feat:** use chromedriver directly without jar


### 1.7.3

* selenium invocation -debug argument - **[@dbushong](https://github.com/dbushong)** [#36](https://github.com/testiumjs/testium-core/pull/36)
  - [`346055d`](https://github.com/testiumjs/testium-core/commit/346055d57307a00712724ce34bae51ba62b27d2d) **fix:** selenium invocation -debug argument


### 1.7.2

* fix: properly invoke selenium.jar with -debug flag - **[@dbushong](https://github.com/dbushong)** [#35](https://github.com/testiumjs/testium-core/pull/35)
  - [`76f1358`](https://github.com/testiumjs/testium-core/commit/76f13586d852783a0f5e723cabd8a87f041d188e) **fix:** properly invoke selenium.jar with -debug flag


### 1.7.1

* fix: fail quickly on aborted client request - **[@dbushong](https://github.com/dbushong)** [#33](https://github.com/testiumjs/testium-core/pull/33)
  - [`ce08240`](https://github.com/testiumjs/testium-core/commit/ce082401cd53ae3099ffff478adf24088dca3dd3) **fix:** fail quickly on aborted client request
  - [`1c370c4`](https://github.com/testiumjs/testium-core/commit/1c370c4ca6a86cb794f0e598e5c08a90e72b50fa) **chore:** test on node 4 & 6, fix java
  - [`bbfd324`](https://github.com/testiumjs/testium-core/commit/bbfd324a2ddd4450ee3f6e42e3a1e2775bc3e6ef) **fix:** make selenium standalone args 3.x compat


### 1.7.0

* feat: tunnel: checks ~/.ssh for keys if no agent - **[@dbushong](https://github.com/dbushong)** [#30](https://github.com/testiumjs/testium-core/pull/30)
  - [`f345b0d`](https://github.com/testiumjs/testium-core/commit/f345b0d393fe51c98d1c5115ea231f9ef3833a79) **feat:** tunnel: checks ~/.ssh for keys if no agent
  - [`7957cd8`](https://github.com/testiumjs/testium-core/commit/7957cd846d8bf01b96da207b8a697dd5c296aabf) **test:** use & verify dynamic ports for proxy testing


### 1.6.0

* Add support for `proxy.tunnel` - **[@dbushong](https://github.com/dbushong)** [#28](https://github.com/testiumjs/testium-core/pull/28)
  - [`e903115`](https://github.com/testiumjs/testium-core/commit/e903115df9494b13ce2ea728a6d607be205099e6) **chore:** update nlm stuffs
  - [`ac85f32`](https://github.com/testiumjs/testium-core/commit/ac85f3286671ebbd390b63beabb34d16c250756f) **feat:** add support for proxy.tunnel.host


### 1.5.0

* feat: use proxy.host for remote selenium grid - **[@dbushong](https://github.com/dbushong)** [#27](https://github.com/testiumjs/testium-core/pull/27)
  - [`9bd6642`](https://github.com/testiumjs/testium-core/commit/9bd66424bea8798eef197c083aa10039193e3ae7) **feat:** use proxy.host for remote selenium grid


### 1.4.8

* fix: switch cleanly between driver types per-file - **[@dbushong](https://github.com/dbushong)** [#23](https://github.com/testiumjs/testium-core/pull/23)
  - [`5087c11`](https://github.com/testiumjs/testium-core/commit/5087c1175f1462bb00edc7443b3e86e2c1449952) **fix:** switch cleanly between driver types per-file


### 1.4.7

* Correct config setting for `selenium.timeout` - **[@dbushong](https://github.com/dbushong)** [#22](https://github.com/testiumjs/testium-core/pull/22)
  - [`c01fb8f`](https://github.com/testiumjs/testium-core/commit/c01fb8f95dd4eaed3876d0dcc47c628932667886) **fix:** correct config setting for selenium.timeout


### 1.4.6

* Initial URL is never the new page URL - **[@jkrems](https://github.com/jkrems)** [#20](https://github.com/testiumjs/testium-core/pull/20)
  - [`aa1587e`](https://github.com/testiumjs/testium-core/commit/aa1587e88c4dbde80049818686a15468ec658901) **fix:** Initial URL is never the new page URL
* Use Groupon project template & nlm - **[@jkrems](https://github.com/jkrems)** [#21](https://github.com/testiumjs/testium-core/pull/21)
  - [`d79ed1b`](https://github.com/testiumjs/testium-core/commit/d79ed1b7211e64063181a3db3e17d3fc3f603c5b) **chore:** Use Groupon project template & nlm
  - [`d69df68`](https://github.com/testiumjs/testium-core/commit/d69df685d6ff0cdba398de0b5d3cbb29b030f56f) **chore:** Use latest lodash & bluebird


1.4.5
-----
* fix: Use existing app when started with `testium_launch=false`
  https://github.com/testiumjs/testium-core/pull/18
* Port contributor info, add code of conduct - @jkrems
  https://github.com/testiumjs/testium-core/pull/17

1.4.4
-----
* Send headers to a page with hash segments - @jkrems
  https://github.com/testiumjs/testium-core/pull/16

1.4.3
-----
* Fix handling of urls hash segment - @jkrems
  https://github.com/testiumjs/testium-core/pull/15

1.4.2
-----
* Fix regression when using launch=false - @jkrems
  https://github.com/testiumjs/testium-core/pull/13

1.4.1
-----
* Restore page size when getting testium - @jkrems
  https://github.com/testiumjs/testium-core/pull/14

1.4.0
-----
* Prefer browser.quit for wd's sake
  https://github.com/testiumjs/testium-core/pull/11

1.3.1
-----
* Default proxy port to 4445 - @jkrems
  https://github.com/testiumjs/testium-core/pull/12

1.3.0
-----
* Add singleton logic from testium - @jkrems
  https://github.com/testiumjs/testium-core/pull/10

1.2.0
-----
* Support the testium_app=null variant
* Fix hanging build on node 0.10
* Add support for launching selenium
  https://github.com/testiumjs/testium-core/pull/8

1.1.3
-----
* Fix handling of external urls
  https://github.com/testiumjs/testium-core/pull/7

1.1.2
-----
* Fix new page url with options - @jkrems
  https://github.com/testiumjs/testium-core/pull/6

1.1.1
-----
* Fix missing _testium_ cookies - @jkrems
  https://github.com/testiumjs/testium-core/pull/5

1.1.0
-----
* Use the newly released testium-cookie - @jkrems
  https://github.com/testiumjs/testium-core/pull/4
* Fix .close() after switch to subprocess - @jkrems
  https://github.com/testiumjs/testium-core/pull/3

1.0.0
-----
* Initial release
