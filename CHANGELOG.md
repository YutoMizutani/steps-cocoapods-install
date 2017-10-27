## Changelog (Current version: 1.7.2)

-----------------

### 1.7.2 (2017 Oct 27)

* [f7236e7] Prepare for 1.7.2
* [bd75d0d] Optional cache (#31)

### 1.7.1 (2017 Jun 08)

* [66dee16] Prepare for 1.7.1

### 1.7.0 (2017 Jun 07)

* [6514b5f] Prepare for 1.7.0
* [b7ee105] Added built-in cache (#30)

### 1.6.1 (2017 Jan 16)

* [37291fd] prepare for 1.6.1
* [8e6b6e0] Rubycommand (#28)

### 1.6.0 (2017 Jan 10)

* [f554e88] Merge pull request #26 from bitrise-io/feature/go-deps-update
* [325d9b9] go deps update
* [cb7bf87] gows init
* [6354673] STEP_VERSION: 1.6.0
* [7f51312] Merge pull request #25 from bitrise-io/feature/podfile-lock-priority-before-gemfile-lock
* [2c44ee9] fixing the test workflow's change dir
* [0639a84] Typo fix - determinE
* [4ec9ea4] If Podfile.lock found use that, not Gemfile.lock

### 1.5.9 (2016 Dec 19)

* [95cdca8] prepare for 1.5.9
* [0508c48] add macos tag (#24)

### 1.5.8 (2016 Dec 05)

* [7e4636f] prepare for 1.5.8
* [517905d] Go toolkit (#23)

### 1.5.7 (2016 Sep 07)

* [a35d4ff] prepare for 1.5.7
* [10b21bd] log config: verbose; added test_without_verbose to test wf (#20)
* [b97c058] Add option to disable verbose (#19)
* [d2fdc1e] removed `create-release` workflow

### 1.5.6 (2016 Aug 19)

* [8c93dea] prep for v1.5.6
* [d687de9] Merge pull request #18 from bitrise-io/feature/bundle-install-retry-and-parallel
* [3284714] bundle install - parallel and retry

### 1.5.5 (2016 Aug 11)

* [2e3a6b1] prepare for 1.5.5
* [4065235] use sudo for gem managemnt install/uninstall commands if system ruby used (#17)

### 1.5.4 (2016 Jul 20)

* [b5432d6] prepare for 1.5.4
* [de74814] case insensitive search for podfile (#15)

### 1.5.3 (2016 Jul 13)

* [4ad778d] prepare for 1.5.3
* [6e9e930] Merge pull request #14 from bitrise-io/remove_ssh_fix
* [218fcd2] private repo ssh issue fixed in cocoapods 0.35 https://github.com/CocoaPods/CocoaPods/issues/2827#issuecomment-62972054

### 1.5.2 (2016 Jun 30)

* [c620a89] prepare for 1.5.2
* [cf969de] Merge pull request #13 from bitrise-io/logging
* [76bf59d] log improvements

### 1.5.1 (2016 Jun 29)

* [93fc636] prepare for 1.5.1
* [338fe08] Merge pull request #12 from bitrise-io/podfile_search_fix
* [7e03b27] fixed Podfile search, install gem with "--no-document" flag

### 1.5.0 (2016 Jun 29)

* [7247d78] prepare for v1.5.0
* [3103401] Merge pull request #11 from bitrise-io/review
* [38f8ac8] PR fix
* [6d0c715] ruby command
* [234c2ab] typo fix
* [b30a8b6] gem install fix
* [63f915d] review, cleanup, gitignore

### 1.4.2 (2016 Jun 14)

* [9ccc90d] prepare for version 1.4.2
* [c40cd5c] Merge pull request #9 from bitrise-io/install_fix
* [a182042] install version fix

### 1.4.1 (2016 Jun 13)

* [17112db] prepare for v1.4.1
* [028c30c] Merge pull request #8 from bitrise-io/cocoapods_version
* [c52598d] update cocoapods to Podfile.lock specified version

### 1.4.0 (2016 May 24)

* [757d200] release configs
* [032e6df] Merge pull request #7 from bitrise-io/install_cocoapods_version
* [6cca36c] install_cocoapods_versioninstall cocoapods version
* [62854f5] STEP_GIT_VERION_TAG_TO_SHARE: 1.3.0

### 1.3.0 (2016 May 21)

* [3bde379] `podfile_path` input handling
* [f369f47] bitrise.yml : better test setup - can be called separately and run all at the same time
* [43fe5b0] STEP_GIT_VERION_TAG_TO_SHARE: 1.2.1

### 1.2.1 (2016 May 19)

* [3cf12db] README update
* [fb17c83] step.yml cleanup
* [a4642a9] run `pod repo update` before retry - required for CocoaPods 1.0
* [5aa61bc] 1.2.0

### 1.2.0 (2016 Apr 13)

* [27ee14c] Try to `pod install --no-repo-update` first, and just retry without the `--no-repo-update` flag if that fails

### 1.1.0 (2016 Jan 11)

* [b2f6195] v1.1.0

### 1.0.3 (2015 Oct 05)

* [1a9b607] Merge pull request #3 from birmacher/master
* [c210005] don't search `Podfile` in `.git` directories
* [6153f86] Merge pull request #2 from bazscsa/patch-1
* [84caa91] depman-update
* [25e76cb] Update step.yml

### 1.0.2 (2015 Sep 21)

* [d2b3466] better testing `bitrise.yml`, with source-dir change (introduced in bitrise CLI 1.1.1) & README update
* [4241448] more (debug) information in case a Gemfile is found and used for `pod install` - printing the used `pod --version` as well, the one used through the Gemfile (`bundle exec`)
* [81a7d34] dont cleanup formatted output
* [9cbdd80] cd into the source root path as soon as possible

### 1.0.1 (2015 Sep 03)

* [4365217] renamed the depman managed cocoapods-update step's folder - prefixed with an underscore

-----------------

Updated: 2017 Oct 27