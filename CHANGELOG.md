# Change log

## [2.1.0] - 2017-05-15

* Improve changelist workflow
* Add `annotate` support (#31)
* Support for shelved files (thanks @ihalip)
* Ignore files specified in settings and .p4ignore (#27, thanks @ihalip)
* Change extension category to `SCM Providers` (thanks @joaomoreno)

## [2.0.1] - 2017-04-09

* Display errors as status bar message (#33)
* Better compatibility with sourcedepot (#48, thanks @hoovercj)
* Improve performance on refresh (#50, #52, thanks @hoovercj)
* Configurable maxBuffer for commands (#53)
* Experimental: Resolve realpath before executing commands (#42, thanks @silenaker)

## [2.0.0] - 2017-04-07

* VS Code SCM Provider - beta (#39, 41, thanks @seanmcbreen, @joaomoreno)
* Better changelist support (#22, #32)
* Add submit support (#30)

## [1.1.0] - 2017-04-04

* Show revisions as QuickPick for diffRevision
* `login` and `logout` commands (#18)
* More robust file path handling (#38, #43, thanks @eeroh)
* ContentProvider for P4 operations

## [1.0.0] - 2017-01-01

* Convert plugin to use Typescript and overall refactor (#26, thanks @jel-massih)
* Use `onWillSaveTextDocument` event (#16, #25)
* No need for workspace folder to (#13, #29)

## [0.1.9] - 2016-09-23

* Fix issue #23 - error with `diff` keyboard shortcut

## [0.1.8] - 2016-07-11

* Add ability to configure the p4 client per workspace. (#19, thanks @ralberts)
* Add ability to diff specific revisions (#20, thanks @hoovercj)
* Add ability to see files opened in perforce and open one in the editor (#21, thanks @hoovercj)

## [0.1.7] - 2016-05-11

* the perforce command path can be configured in settings (#15, thanks @hoovercj)

## [0.1.6] - 2016-03-31

* Fix a temporary file issue on Windows

## [0.1.5] - 2016-03-30

* Show diff in a compare window
* Fix issue #10 - change warning boxes for status bar messages

## [0.1.4] - 2016-01-21

* Fix issue #9 - check for a valid p4 root before running automatic commands

## [0.1.3] - 2015-12-21

* status bar icons
* options to run `add`,`edit`,`delete` on file operations (thanks @jel-massih)

## [0.1.2] - 2015-11-18

* `info` to display client/server information
* Fix issue #2 - set open folder as working directory for `p4` commands

## [0.1.1] - 2015-11-15

* activationEvents (thanks @egamma)
* QuickPick on cancel

## [0.1.0] - 2015-11-14

* MIT License
* new icon
* vscode API 0.10.x

## [0.0.3] - 2015-10-18

* group commands in QuickPick

## [0.0.2] - 2015-10-18

* `add` command on a new file
* `diff` current file in output log
* icon

## [0.0.1] - 2015-10-18

* `edit` command on opened file
* `revert` command on opened file

[2.1.0]: https://github.com/stef-levesque/vscode-perforce/compare/5dd2025bdcbc906fc77b4019fe92d2263c06bc00...61ff3b2a6dd1d32d3e572e788034fedd62455b35
[2.0.1]: https://github.com/stef-levesque/vscode-perforce/compare/1a08507ae3a0b825563d2c9444210194abf75962...852d772956b3e68baf06a064632b71e0f7c44444
[2.0.0]: https://github.com/stef-levesque/vscode-perforce/compare/a83bf106468feec7ed8c6aaac841487654eb0737...3fe2af32f4c4b6e34443e1baf0724984c76be69d
[1.1.0]: https://github.com/stef-levesque/vscode-perforce/compare/e08c66e833e8508fda4d190697934b5bb1a7a3d5...b143313ec7263d82fd40f6a32c3e366c0778998f
[1.0.0]: https://github.com/stef-levesque/vscode-perforce/compare/dc0542519de6249438582750cc928b70ac075114...e68aee4a38589ebfbb1346e945c117fcb111ac25
[0.1.9]: https://github.com/stef-levesque/vscode-perforce/compare/62008b25044c90cc382c2cc952e454591af78b47...c584470fe7a1328be3895c49242e543a3ed06d3c
[0.1.8]: https://github.com/stef-levesque/vscode-perforce/compare/2af4e1713633c96ed70ee8366fd533094377ef55...2da50c202f9c711a3b5e6e40d7333bf71cac1f90
[0.1.7]: https://github.com/stef-levesque/vscode-perforce/compare/cf189871bdc013e4342d5c3fd0ee485ddae4734e...1fbce841c7f52f65a00f1c25bc530b8c4296aafe
[0.1.6]: https://github.com/stef-levesque/vscode-perforce/compare/2915c7688d1c71dd1815350313f7d4344cab1607...b9bb4076beb62d47d17abfd8fc515058ab9f5adb
[0.1.5]: https://github.com/stef-levesque/vscode-perforce/compare/383da5048e342cbbe90ab4f74fecd0db9e3d85fc...faad0b0db08d87f04664dfa9bc8a3be3640c6311
[0.1.4]: https://github.com/stef-levesque/vscode-perforce/compare/168cd653195f33774f8c6c795ab29adba4bbe499...d07a5c45df1db65cf0335b5949a55077b84fe4b4
[0.1.3]: https://github.com/stef-levesque/vscode-perforce/compare/1e006e1c51640756b6e6cbd39a78d050e13f5f6a...168cd653195f33774f8c6c795ab29adba4bbe499
[0.1.2]: https://github.com/stef-levesque/vscode-perforce/compare/ada0c5a47eb39fd05cbd3d45433cd351f759f072...1e006e1c51640756b6e6cbd39a78d050e13f5f6a
[0.1.1]: https://github.com/stef-levesque/vscode-perforce/compare/afbe80a4549dad0f45410ab48ab3cf7e59497286...ada0c5a47eb39fd05cbd3d45433cd351f759f072
[0.1.0]: https://github.com/stef-levesque/vscode-perforce/compare/cc98c00da2aac4771f2c6923eb7d8dd968a0aa92...afbe80a4549dad0f45410ab48ab3cf7e59497286
[0.0.3]: https://github.com/stef-levesque/vscode-perforce/compare/d088f2844785e3c607a55e6a165f76e0179dc4c2...cc98c00da2aac4771f2c6923eb7d8dd968a0aa92
[0.0.2]: https://github.com/stef-levesque/vscode-perforce/compare/ec31157dee778c7a59cf86b7382f1d8a5c152736...d088f2844785e3c607a55e6a165f76e0179dc4c2
[0.0.1]: https://github.com/stef-levesque/vscode-perforce/commit/ec31157dee778c7a59cf86b7382f1d8a5c152736