# Node.js 14 ChangeLog

<!--lint disable prohibited-strings-->
<!--lint disable maximum-line-length-->

<table>
<tr>
<th>Current</th>
</tr>
<tr>
<td>
<a href="#14.0.0">14.0.0</a><br/>
</td>
</tr>
</table>

* Other Versions
  * [13.x](CHANGELOG_V13.md)
  * [12.x](CHANGELOG_V12.md)
  * [11.x](CHANGELOG_V11.md)
  * [10.x](CHANGELOG_V10.md)
  * [9.x](CHANGELOG_V9.md)
  * [8.x](CHANGELOG_V8.md)
  * [7.x](CHANGELOG_V7.md)
  * [6.x](CHANGELOG_V6.md)
  * [5.x](CHANGELOG_V5.md)
  * [4.x](CHANGELOG_V4.md)
  * [0.12.x](CHANGELOG_V012.md)
  * [0.10.x](CHANGELOG_V010.md)
  * [io.js](CHANGELOG_IOJS.md)
  * [Archive](CHANGELOG_ARCHIVE.md)

<a id="14.0.0"></a>
## 2020-04-21, Version 14.0.0 (Current), @BethGriggs

### Notable Changes

* TBD

### Semver-Major Commits

* [[`9b6e797379`](https://github.com/nodejs/node/commit/9b6e797379)] - **(SEMVER-MAJOR)** ***Revert*** "**assert**: fix line number calculation after V8 upgrade" (Michaël Zasso) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`5360dd151d`](https://github.com/nodejs/node/commit/5360dd151d)] - **(SEMVER-MAJOR)** **assert**: handle (deep) equal(NaN, NaN) as being identical (Ruben Bridgewater) [#30766](https://github.com/nodejs/node/pull/30766)
* [[`a621608f12`](https://github.com/nodejs/node/commit/a621608f12)] - **(SEMVER-MAJOR)** **build**: update macos deployment target to 10.13 for 14.x (AshCripps) [#32454](https://github.com/nodejs/node/pull/32454)
* [[`6a349019da`](https://github.com/nodejs/node/commit/6a349019da)] - **(SEMVER-MAJOR)** **build**: temporarily skip ASAN build (Matheus Marchini) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`da92f15413`](https://github.com/nodejs/node/commit/da92f15413)] - **(SEMVER-MAJOR)** **build**: reset embedder string to "-node.0" (Matheus Marchini) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`e65bed1b7e`](https://github.com/nodejs/node/commit/e65bed1b7e)] - **(SEMVER-MAJOR)** **child_process**: create proper public API for `channel` (Anna Henningsen) [#30165](https://github.com/nodejs/node/pull/30165)
* [[`1b9a62cff4`](https://github.com/nodejs/node/commit/1b9a62cff4)] - **(SEMVER-MAJOR)** **crypto**: make DH error messages consistent (Tobias Nießen) [#31873](https://github.com/nodejs/node/pull/31873)
* [[`bffa5044c5`](https://github.com/nodejs/node/commit/bffa5044c5)] - **(SEMVER-MAJOR)** **crypto**: move pbkdf2 without digest to EOL (James M Snell) [#31166](https://github.com/nodejs/node/pull/31166)
* [[`10f5fa7513`](https://github.com/nodejs/node/commit/10f5fa7513)] - **(SEMVER-MAJOR)** **crypto**: forbid setting the PBKDF2 iter count to 0 (Tobias Nießen) [#30578](https://github.com/nodejs/node/pull/30578)
* [[`1cd235d1a0`](https://github.com/nodejs/node/commit/1cd235d1a0)] - **(SEMVER-MAJOR)** **deps**: patch V8 to run on Xcode 8 (Matheus Marchini) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`5d867badd0`](https://github.com/nodejs/node/commit/5d867badd0)] - **(SEMVER-MAJOR)** **deps**: V8: silence irrelevant warnings (Michaël Zasso) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`8d2c441e4d`](https://github.com/nodejs/node/commit/8d2c441e4d)] - **(SEMVER-MAJOR)** **deps**: V8: cherry-pick 931bdbd76f5b (Matheus Marchini) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`049160dfb6`](https://github.com/nodejs/node/commit/049160dfb6)] - **(SEMVER-MAJOR)** **deps**: V8: cherry-pick 1e36e21acc40 (Matheus Marchini) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`0220c298c5`](https://github.com/nodejs/node/commit/0220c298c5)] - **(SEMVER-MAJOR)** **deps**: bump minimum icu version to 65 (Michaël Zasso) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`f90eba1d91`](https://github.com/nodejs/node/commit/f90eba1d91)] - **(SEMVER-MAJOR)** **deps**: make v8.h compatible with VS2015 (Joao Reis) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`56b6a4f732`](https://github.com/nodejs/node/commit/56b6a4f732)] - **(SEMVER-MAJOR)** **deps**: V8: forward declaration of `Rtl\*FunctionTable` (Refael Ackermann) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`40c9419b35`](https://github.com/nodejs/node/commit/40c9419b35)] - **(SEMVER-MAJOR)** **deps**: V8: patch register-arm64.h (Refael Ackermann) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`55407ab73e`](https://github.com/nodejs/node/commit/55407ab73e)] - **(SEMVER-MAJOR)** **deps**: patch V8 to run on older XCode versions (Ujjwal Sharma) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`990bc9adb4`](https://github.com/nodejs/node/commit/990bc9adb4)] - **(SEMVER-MAJOR)** **deps**: V8: un-cherry-pick bd019bd (Refael Ackermann) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`17a6def4e8`](https://github.com/nodejs/node/commit/17a6def4e8)] - **(SEMVER-MAJOR)** **deps**: update V8 dtrace & postmortem metadata (Colin Ihrig) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`2883c855e0`](https://github.com/nodejs/node/commit/2883c855e0)] - **(SEMVER-MAJOR)** **deps**: update V8 to 8.1.307.20 (Matheus Marchini) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`1b2e2944bc`](https://github.com/nodejs/node/commit/1b2e2944bc)] - **(SEMVER-MAJOR)** **dgram**: don't hide implicit bind errors (Colin Ihrig) [#31958](https://github.com/nodejs/node/pull/31958)
* [[`75ee5b2622`](https://github.com/nodejs/node/commit/75ee5b2622)] - **(SEMVER-MAJOR)** **doc**: deprecate process.umask() with no arguments (Colin Ihrig) [#32499](https://github.com/nodejs/node/pull/32499)
* [[`afe353061b`](https://github.com/nodejs/node/commit/afe353061b)] - **(SEMVER-MAJOR)** **doc**: fs.write is not longer coercing strings (Juan José Arboleda) [#31030](https://github.com/nodejs/node/pull/31030)
* [[`4455f60320`](https://github.com/nodejs/node/commit/4455f60320)] - **(SEMVER-MAJOR)** **doc**: use shorter fs.copyFile examples (Ruben Bridgewater) [#27044](https://github.com/nodejs/node/pull/27044)
* [[`a45c1aa39f`](https://github.com/nodejs/node/commit/a45c1aa39f)] - **(SEMVER-MAJOR)** **doc**: fix mode and flags being mistaken in fs (Ruben Bridgewater) [#27044](https://github.com/nodejs/node/pull/27044)
* [[`331d636240`](https://github.com/nodejs/node/commit/331d636240)] - **(SEMVER-MAJOR)** **errors**: remove unused ERR\_SOCKET\_CANNOT\_SEND error (Colin Ihrig) [#31958](https://github.com/nodejs/node/pull/31958)
* [[`b8e41774d4`](https://github.com/nodejs/node/commit/b8e41774d4)] - **(SEMVER-MAJOR)** **fs**: add fs/promises alias module (Gus Caplan) [#31553](https://github.com/nodejs/node/pull/31553)
* [[`fb6df3bfac`](https://github.com/nodejs/node/commit/fb6df3bfac)] - **(SEMVER-MAJOR)** **fs**: validate the input data to be of expected types (Ruben Bridgewater) [#31030](https://github.com/nodejs/node/pull/31030)
* [[`2d8febceef`](https://github.com/nodejs/node/commit/2d8febceef)] - **(SEMVER-MAJOR)** **fs**: deprecate closing FileHandle on garbage collection (James M Snell) [#28396](https://github.com/nodejs/node/pull/28396)
* [[`67e067eb06`](https://github.com/nodejs/node/commit/67e067eb06)] - **(SEMVER-MAJOR)** **fs**: watch signals for recursive incompatibility (Eran Levin) [#29947](https://github.com/nodejs/node/pull/29947)
* [[`f0d2df41f8`](https://github.com/nodejs/node/commit/f0d2df41f8)] - **(SEMVER-MAJOR)** **fs**: change streams to always emit close by default (Robert Nagy) [#31408](https://github.com/nodejs/node/pull/31408)
* [[`a13500f503`](https://github.com/nodejs/node/commit/a13500f503)] - **(SEMVER-MAJOR)** **fs**: improve mode and flags validation (Ruben Bridgewater) [#27044](https://github.com/nodejs/node/pull/27044)
* [[`535e9571f5`](https://github.com/nodejs/node/commit/535e9571f5)] - **(SEMVER-MAJOR)** **fs**: make FSStatWatcher.start private (Lucas Holmquist) [#29971](https://github.com/nodejs/node/pull/29971)
* [[`c1b2f6afbe`](https://github.com/nodejs/node/commit/c1b2f6afbe)] - **(SEMVER-MAJOR)** **http**: detach socket from IncomingMessage on keep-alive (Robert Nagy) [#32153](https://github.com/nodejs/node/pull/32153)
* [[`173d044d09`](https://github.com/nodejs/node/commit/173d044d09)] - **(SEMVER-MAJOR)** **http**: align OutgoingMessage and ClientRequest destroy (Robert Nagy) [#32148](https://github.com/nodejs/node/pull/32148)
* [[`d3715c76b5`](https://github.com/nodejs/node/commit/d3715c76b5)] - **(SEMVER-MAJOR)** **http**: move OutboundMessage.prototype.flush to EOL (James M Snell) [#31164](https://github.com/nodejs/node/pull/31164)
* [[`c776a37791`](https://github.com/nodejs/node/commit/c776a37791)] - **(SEMVER-MAJOR)** **http**: end with data can cause write after end (Robert Nagy) [#28666](https://github.com/nodejs/node/pull/28666)
* [[`ff2ed3ec85`](https://github.com/nodejs/node/commit/ff2ed3ec85)] - **(SEMVER-MAJOR)** **http**: remove unused hasItems() from freelist (Rich Trott) [#30744](https://github.com/nodejs/node/pull/30744)
* [[`d247a8e1dc`](https://github.com/nodejs/node/commit/d247a8e1dc)] - **(SEMVER-MAJOR)** **http**: emit close on socket re-use (Robert Nagy) [#28685](https://github.com/nodejs/node/pull/28685)
* [[`6f0ec79e42`](https://github.com/nodejs/node/commit/6f0ec79e42)] - **(SEMVER-MAJOR)** **http,stream**: make virtual methods throw an error (Luigi Pinca) [#31912](https://github.com/nodejs/node/pull/31912)
* [[`ec0dd6fa1c`](https://github.com/nodejs/node/commit/ec0dd6fa1c)] - **(SEMVER-MAJOR)** **lib**: move GLOBAL and root aliases to EOL (James M Snell) [#31167](https://github.com/nodejs/node/pull/31167)
* [[`d7452b7140`](https://github.com/nodejs/node/commit/d7452b7140)] - **(SEMVER-MAJOR)** **module**: warn on using unfinished circular dependency (Anna Henningsen) [#29935](https://github.com/nodejs/node/pull/29935)
* [[`eeccd52b4e`](https://github.com/nodejs/node/commit/eeccd52b4e)] - **(SEMVER-MAJOR)** **net**: make readable/writable start as true (Robert Nagy) [#32272](https://github.com/nodejs/node/pull/32272)
* [[`ab4115f17c`](https://github.com/nodejs/node/commit/ab4115f17c)] - **(SEMVER-MAJOR)** **os**: move tmpDir() to EOL (James M Snell) [#31169](https://github.com/nodejs/node/pull/31169)
* [[`8c18e91c8a`](https://github.com/nodejs/node/commit/8c18e91c8a)] - **(SEMVER-MAJOR)** **process**: remove undocumented `now` argument from emitWarning() (Rich Trott) [#31643](https://github.com/nodejs/node/pull/31643)
* [[`84c426cb60`](https://github.com/nodejs/node/commit/84c426cb60)] - **(SEMVER-MAJOR)** **repl**: properly handle `repl.repl` (Ruben Bridgewater) [#30981](https://github.com/nodejs/node/pull/30981)
* [[`d19a2c33b3`](https://github.com/nodejs/node/commit/d19a2c33b3)] - **(SEMVER-MAJOR)** **src**: migrate measureMemory to new v8 api (gengjiawen) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`a63db7fb5e`](https://github.com/nodejs/node/commit/a63db7fb5e)] - **(SEMVER-MAJOR)** **src**: remove deprecated wasm type check (Clemens Backes) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`c080b2d821`](https://github.com/nodejs/node/commit/c080b2d821)] - **(SEMVER-MAJOR)** **src**: avoid calling deprecated method (Clemens Backes) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`7ed0d1439e`](https://github.com/nodejs/node/commit/7ed0d1439e)] - **(SEMVER-MAJOR)** **src**: remove use of deprecated Symbol::Name() (Colin Ihrig) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`59eeb3b5b9`](https://github.com/nodejs/node/commit/59eeb3b5b9)] - **(SEMVER-MAJOR)** **src**: stop overriding deprecated V8 methods (Clemens Backes) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`339c192ddb`](https://github.com/nodejs/node/commit/339c192ddb)] - **(SEMVER-MAJOR)** **src**: update NODE\_MODULE\_VERSION to 83 (Matheus Marchini) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`4f523c2c1a`](https://github.com/nodejs/node/commit/4f523c2c1a)] - **(SEMVER-MAJOR)** **src**: migrate to new V8 ArrayBuffer API (Thang Tran) [#30782](https://github.com/nodejs/node/pull/30782)
* [[`c712fb7cd6`](https://github.com/nodejs/node/commit/c712fb7cd6)] - **(SEMVER-MAJOR)** **src**: add abstract `IsolatePlatformDelegate` (Marcel Laverdet) [#30324](https://github.com/nodejs/node/pull/30324)
* [[`1428a92492`](https://github.com/nodejs/node/commit/1428a92492)] - **(SEMVER-MAJOR)** **stream**: make pipeline try to wait for 'close' (Robert Nagy) [#32158](https://github.com/nodejs/node/pull/32158)
* [[`388cef61e8`](https://github.com/nodejs/node/commit/388cef61e8)] - **(SEMVER-MAJOR)** **stream**: align stream.Duplex with net.Socket (Robert Nagy) [#32139](https://github.com/nodejs/node/pull/32139)
* [[`7cafd5f3a9`](https://github.com/nodejs/node/commit/7cafd5f3a9)] - **(SEMVER-MAJOR)** **stream**: fix finished w/ 'close' before 'end' (Robert Nagy) [#31545](https://github.com/nodejs/node/pull/31545)
* [[`311e12b962`](https://github.com/nodejs/node/commit/311e12b962)] - **(SEMVER-MAJOR)** **stream**: fix multiple destroy calls (Robert Nagy) [#29197](https://github.com/nodejs/node/pull/29197)
* [[`1f209129c7`](https://github.com/nodejs/node/commit/1f209129c7)] - **(SEMVER-MAJOR)** **stream**: throw invalid argument errors (Robert Nagy) [#31831](https://github.com/nodejs/node/pull/31831)
* [[`d016b9d708`](https://github.com/nodejs/node/commit/d016b9d708)] - **(SEMVER-MAJOR)** **stream**: finished callback for closed streams (Robert Nagy) [#31509](https://github.com/nodejs/node/pull/31509)
* [[`e559842188`](https://github.com/nodejs/node/commit/e559842188)] - **(SEMVER-MAJOR)** **stream**: make readable & writable computed (Robert Nagy) [#31197](https://github.com/nodejs/node/pull/31197)
* [[`907c07fa85`](https://github.com/nodejs/node/commit/907c07fa85)] - **(SEMVER-MAJOR)** **stream**: move \_writableState.buffer to EOL (James M Snell) [#31165](https://github.com/nodejs/node/pull/31165)
* [[`66f4e4edcb`](https://github.com/nodejs/node/commit/66f4e4edcb)] - **(SEMVER-MAJOR)** **stream**: do not emit 'end' after 'error' (Robert Nagy) [#31182](https://github.com/nodejs/node/pull/31182)
* [[`75b30c606c`](https://github.com/nodejs/node/commit/75b30c606c)] - **(SEMVER-MAJOR)** **stream**: emit 'error' asynchronously (Robert Nagy) [#29744](https://github.com/nodejs/node/pull/29744)
* [[`4bec6d13f9`](https://github.com/nodejs/node/commit/4bec6d13f9)] - **(SEMVER-MAJOR)** **stream**: enable autoDestroy by default (Robert Nagy) [#30623](https://github.com/nodejs/node/pull/30623)
* [[`20d009d2fd`](https://github.com/nodejs/node/commit/20d009d2fd)] - **(SEMVER-MAJOR)** **stream**: pipe should not swallow error (Robert Nagy) [#30993](https://github.com/nodejs/node/pull/30993)
* [[`67ed526ab0`](https://github.com/nodejs/node/commit/67ed526ab0)] - **(SEMVER-MAJOR)** **stream**: error state cleanup (Robert Nagy) [#30851](https://github.com/nodejs/node/pull/30851)
* [[`e902fadc5e`](https://github.com/nodejs/node/commit/e902fadc5e)] - **(SEMVER-MAJOR)** **stream**: do not throw multiple callback errors in writable (Robert Nagy) [#30614](https://github.com/nodejs/node/pull/30614)
* [[`e13a37e49d`](https://github.com/nodejs/node/commit/e13a37e49d)] - **(SEMVER-MAJOR)** **stream**: ensure finish is emitted in next tick (Robert Nagy) [#30733](https://github.com/nodejs/node/pull/30733)
* [[`9d09969f4c`](https://github.com/nodejs/node/commit/9d09969f4c)] - **(SEMVER-MAJOR)** **stream**: always invoke end callback (Robert Nagy) [#29747](https://github.com/nodejs/node/pull/29747)
* [[`52944b834a`](https://github.com/nodejs/node/commit/52944b834a)] - **(SEMVER-MAJOR)** **test**: remove test (Clemens Backes) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`119fdf6813`](https://github.com/nodejs/node/commit/119fdf6813)] - **(SEMVER-MAJOR)** **test**: remove checks for deserializing wasm (Matheus Marchini) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`405ae1909b`](https://github.com/nodejs/node/commit/405ae1909b)] - **(SEMVER-MAJOR)** **tools**: update V8 gypfiles for 8.1 (Matheus Marchini) [#32116](https://github.com/nodejs/node/pull/32116)
* [[`0f78dcc86d`](https://github.com/nodejs/node/commit/0f78dcc86d)] - **(SEMVER-MAJOR)** **util**: escape C1 control characters and switch to hex format (Ruben Bridgewater) [#29826](https://github.com/nodejs/node/pull/29826)
* [[`cb8898c48f`](https://github.com/nodejs/node/commit/cb8898c48f)] - **(SEMVER-MAJOR)** **win**: block running on EOL Windows versions (João Reis) [#31954](https://github.com/nodejs/node/pull/31954)
* [[`a9401439c7`](https://github.com/nodejs/node/commit/a9401439c7)] - **(SEMVER-MAJOR)** **zlib**: align with streams (Robert Nagy) [#32220](https://github.com/nodejs/node/pull/32220)

### Semver-Minor Commits

* TBD

### Semver-Patch Commits

* TBD
