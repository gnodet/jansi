# ![Jansi](http://fusesource.github.io/jansi/images/project-logo.png)

## [Jansi 1.16][1_16], released 2017-05-xx
[1_16]: http://repo.fusesource.com/nexus/content/groups/public/org/fusesource/jansi/jansi/1.16

* Support insert / delete lines ansi sequences
* Fix inverted colors
* Upgraded to the latest jansi native release (1.7).
* ANSI output stripping does not work if TERM is xterm, fixes [#83](https://github.com/fusesource/jansi/pull/83)
* Provide FreeBSD native support by default, fixes [#56](https://github.com/fusesource/jansi/pull/56)
* Make AnsiOutputStream#write synchronized to avoid possible problems
* Harcode the reset code to avoid having the AnsiOutputStream depending on Ansi, fix typo
* Avoid the charset lookup
* Correct support for the bright colors on windows
* Add a few methods to be able to render code names more easily, fixes [#14](https://github.com/fusesource/jansi/pull/14)
* Fix encoding problem on AnsiConsole.out on windows, fixes [#79](https://github.com/fusesource/jansi/pull/79)

## [Jansi 1.15][1_15], released 2017-03-17
[1_15]: http://repo.fusesource.com/nexus/content/groups/public/org/fusesource/jansi/jansi/1.15

## [Jansi 1.14][1_14], released 2016-10-04
[1_14]: http://repo.fusesource.com/nexus/content/groups/public/org/fusesource/jansi/jansi/1.14

## [Jansi 1.13][1_13], released 2016-06-15
[1_13]: http://repo.fusesource.com/nexus/content/groups/public/org/fusesource/jansi/jansi/1.13

## [Jansi 1.12][1_12], released 2016-04-27
[1_12]: http://repo.fusesource.com/nexus/content/groups/public/org/fusesource/jansi/jansi/1.12

* [5d4eb66](#5d4eb665e428a63851ab2b51bad7c3487803e841) Fixing dep id.
* [3949775](#3949775bb2df312d720fa22439efbea2b14e6ef4) Update parent pom.
* [ec777e7](#ec777e737a508e7cd1aa477a9d2681c6d0638bad) Switch to released jansi-native artifacts.
* [5dcfc1a](#5dcfc1ad5bec9f21c02c0839cdd325d8560b2d59) Update to use new style of native artifacts.
* [a7a0120](#a7a0120a299b8c052b392ebd6c8ef173a36df0f6) Switching to sonatype mvn repo.
* [daff2c9](#daff2c9384bf939273dc9969805b07f52461ea5b) Build against jansi-native 1.6-SNAPSHOT
* [5aa64b1](#5aa64b112c1544363deae81688b97cf56cc37c19) Merge pull request [#46] from DevFactory/release/multiple-code-improvements-fix-1
* [23afd0e](#23afd0e094a6c4de0fb26f4b370ee6add944faee) Merge pull request [#15] from garydgregory/better-Ansi
* [236d35f](#236d35fadb9cf3ff75f90236f2e6aec45c69ba55) Merge pull request [#45] from sschuberth/master
* [1f0e856](#1f0e856398b4ee4b304bd61e17399205412c7c66) Multiple code improvements - squid:SwitchLastCaseIsDefaultCheck, squid:S1197, squid:S1118
* [65d955b](#65d955bf0aa8ae480ee5d8eefdd8057ff7471eca) Detect Cygwin, including the MSYS(2) forks
* [704633f](#704633fd36399437ebea59dded84324a9f09616a) Fix compatibility with jansi 1.11
* [bc4e70a](#bc4e70af8739231cd60502bb72377302925564e0) Upgrade to jansi-native 1.6-SNAPSHOT
* [4a018a5](#4a018a520f9baf4b09f0c3577aa871c9c74a17b8) Export the internal package so that Kernel32 and CLibrary can be used in OSGi
* [620c446](#620c44697fea322181f402cd325998b871afee00) Fill console attributes when erasing the screen on windows to not leave unwanted backgrounds on the screen
* [bf3b544](#bf3b544a172a57e62412dff9043faa428ee31b2f) Make sure bright colors are not completely ignored on windows
* [c69c78b](#c69c78b2f3855255b0432162d2e94f9d84951b0b) Fix some javadocs warnings
* [2400c7a](#2400c7acd9941a8974258804b63876512f6b4bf7) Merge pull request [#35] from udalov/patch-1
* [0d398a5](#0d398a57e70f2654631dbcd7adc34bc85428b172) Check isatty() separately for stdout and stderr
* [c3b76bc](#c3b76bcad382f6a76cfb1534e6b068ee53774554) Merge pull request [#26] from ghquant/fix-Ansi-DefaultColors-Windows
* [5f202de](#5f202def7a3cfb2584b442bcdce0ed2d6600b76e) Merge pull request [#20] from tksk/master
* [fc87486](#fc87486cea26655e7c6eda77b1b582e2bf416f33) [#10]: Fixed broken links in readme file.
* [239255c](#239255ca6221da5bf453065cc8ddbd45b2e4a406) [#17]: Fixed typos, and @deprecated methods with typo.
* [489c4d3](#489c4d3a74f93dbd17bb8927feac4ba82dfbb23c) Merge pull request [#21] from jdbernard/master
* [20a1ebb](#20a1ebb2a15003cc290d461f6da30e9787b1f6f1) Merge pull request [#13] from garydgregory/turkish-fix
* [682f9c3](#682f9c3eb4df5e95ac6383d20bddcd788cccaacd) implemented missing functions to set the default text and background colors on Windows
* [0d05930](#0d059308450dbe9a122b61b7a9424b12ed25cf79) Added additional escape sequences defined in ECMA-48.
* [2ef5976](#2ef5976879123accb0f9adc22c0014eb0310e298) support jansi.force property to force ansi escapes
* [9bab505](#9bab505bfbd57c8511ef3641c6d0fe41c92302dd) Merge pull request [#19] from xuwei-k/patch-1

## [Jansi 1.11][1_11], released 2013-05-13
[1_11]: http://repo.fusesource.com/nexus/content/groups/public/org/fusesource/jansi/jansi/1.11

* Upgraded to the latest hawtjni version.

## [Jansi 1.10][1_10], released 2013-03-25
[1_10]: http://repo.fusesource.com/nexus/content/groups/public/org/fusesource/jansi/jansi/1.10

* Upgraded to the latest jansi native release (1.5).

## [Jansi 1.9][1_9], released 2012-06-04
[1_9]: http://repo.fusesource.com/nexus/content/groups/public/org/fusesource/jansi/jansi/1.9

* Added HtmlAnsiOutputStream that converts ANSI output to HTML.
* Fixed handling of default text and background color.

## [Jansi 1.8][1_8], released 2012-02-15
[1_8]: http://repo.fusesource.com/nexus/content/groups/public/org/fusesource/jansi/jansi/1.8

* Updated bundled native libraries:
  * Windows: Added support for isatty and link against the system msvcrt.dll (so no need for VC redistributables).
* Add some helper methods to turn bold on and off.
* If the jansi.passthrough system property is set, then Jansi will not interpret any of the ANSI sequences.

## [Jansi 1.7][1_7], released 2011-09-21
[1_7]: http://repo.fusesource.com/nexus/content/groups/public/org/fusesource/jansi/jansi/1.7

* Updated bundled native libraries:
  * Windows: Adding support for PeekConsoleInputW, FlushConsoleInputBuffer so that CTRL-C can be handled by jline. Discarding mouse events on readConsoleInput.
  * Linux: Built against glib 2.0 to be compatible with more versions of Linux.
  
## [Jansi 1.6][1_6], released 2011-06-19
[1_6]: http://repo.fusesource.com/nexus/content/groups/public/org/fusesource/jansi/jansi/1.6

* Upgrade to HawtJNI 1.2 to pick up a fix to support 32 and 64 bit JVMs on a single machine.
* Add copy constructor for Ansi class.
* Port website doco to use Scalate instead of webgen.

## [Jansi 1.5][1_5], released 2010-11-04
[1_5]: http://repo.fusesource.com/nexus/content/groups/public/org/fusesource/jansi/jansi/1.5

* Support for parsing Operating System Command (OSC) control sequences.
* Windows: added support for setting the console title through an OSC command, like on xterm.
* Added option to strip ANSI escapes if the 'jansi.strip' system property is set to true.

## [Jansi 1.4][1_4], released 2010-07-15
[1_4]: http://repo.fusesource.com/nexus/content/groups/public/org/fusesource/jansi/jansi/1.4

* JNI libs are now bundled in the Jansi jar.
* Windows: added support for save and restore of cursor position, fixed bug in processCursorTo.

## [Jansi 1.3][1_3], released 2010-03-08
[1_3]: http://repo.fusesource.com/nexus/content/groups/public/org/fusesource/jansi/jansi/1.3

* Switched to a HawtJNI generated native library instead of using JNA to access native functions.

## [Jansi 1.2.1][1_2_1], released 2010-03-08
[1_2_1]: http://repo.fusesource.com/nexus/content/groups/public/org/fusesource/jansi/jansi/1.2.1

* Released to Maven Central.

## [Jansi 1.2][1_2], released 2010-02-09
[1_2]: http://jansi.fusesource.org/repo/release/org/fusesource/jansi/jansi/1.2

* Improved Java Docs.
* Better windows ANSI handling of: erase screen and line and move to col.
* New method: Ansi.newline().
* Fixed missing return statement in cursor up case. 
* Reset the attributes when the ANSI output stream is closed on unix.

## [Jansi 1.1][1_1], released 2009-11-23
[1_1]: http://jansi.fusesource.org/repo/release/org/fusesource/jansi/jansi/1.1

* AnsiRender can now be used in a static way and made easier to use with the ANSI builder.
* Merged [Jason Dillon's Fork](http://github.com/jdillon/jansi/tree/bb86e0e79bec850167ddfd8c4a86fb9ffef704e5): 
	* Pluggable ANSI support detection.
	* ANSI builder can be configured to not generate ANSI escapes.
	* AnsiRender provides an easier way to generate escape sequences.
* [JANSI-5](http://fusesource.com/issues/browse/JANSI-5): Attribute Reset escape should respect original console colors.
* [JANSI-4](http://fusesource.com/issues/browse/JANSI-4): Restore command console after closing wrapped OutputStream on Windows.
* [JANSI-1](http://fusesource.com/issues/browse/JANSI-1): Added extensions for colors and other attributes to Ansi builder. 

## [Jansi 1.0][1_0], released 2009-08-25
[1_0]: http://jansi.fusesource.org/repo/release/org/fusesource/jansi/jansi/1.0

* Initial Release.
