# Harnice application releases are found here.

## [v0.12.2](https://github.com/harnice/harnice-app-releases/releases/tag/v0.12.2)

# Big Changes
* you can now define harnesses via build instructions, no longer necessarily via block diagram reference desginators
## What's Changed
* MCP server, published schema, and a site without code reference (#1567) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1579
* changed keying on refdes uniqueness to the will-be name, not the is-name by @kenyonshutt in https://github.com/harnice/Harnice/pull/1580
* Define harnesses on buses in build instructions (#1574) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1581


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.12.1...v0.12.2

## [v0.12.1](https://github.com/harnice/harnice-app-releases/releases/tag/v0.12.1)

# Big changes
* Store the instances list as json, not csv, and remove a lot of old, vulnerable AST parsing of objects hidden inside CSV's
* Name changes of 3D objects: now Harnice 3D only knows nodes, segments, mates, and bodies. that's it. 
## What's Changed
* Log actions, errors and crashes to a logs folder in app data by @kenyonshutt in https://github.com/harnice/Harnice/pull/1564
* Store the instances list as JSON and share one cell parser by @kenyonshutt in https://github.com/harnice/Harnice/pull/1561
* Undo takes back fresh editor text before a page switch (#1536) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1568
* Mate harness ends at a fixed distance and keep mating connector order… by @kenyonshutt in https://github.com/harnice/Harnice/pull/1570
* Device mating connectors are nodes (#1521) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1571


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.11.5...v0.12.1

## [v0.11.5](https://github.com/harnice/harnice-app-releases/releases/tag/v0.11.5)

## What's Changed
* Never persist text in the project search field (#1557) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1558
* Keep editor scroll aligned when switching diff mode on and off (#1555) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1559
* Available network: available.json is the only source; new available/chosen algorithm (#1556) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1560


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.11.4...v0.11.5

## [v0.11.4](https://github.com/harnice/harnice-app-releases/releases/tag/v0.11.4)

## What's Changed
* Harness routing from the source system's mating connectors, Nodes sidebar, #1470 routing context (#1506) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1519
* Available network editor: Show only chosen in the Nodes panel by @kenyonshutt in https://github.com/harnice/Harnice/pull/1540
* Body macros: name all six faces so images attach to each by @kenyonshutt in https://github.com/harnice/Harnice/pull/1541
* Worktree toggle: slider stays put, never opens a leftover copy (#1525, #1526) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1545
* Context instances: show/hide in every 3D routing view, GUI only, right-click to hide by @kenyonshutt in https://github.com/harnice/Harnice/pull/1547
* Add harnice --check-drawing; tighten the part-family drawing contract by @kenyonshutt in https://github.com/harnice/Harnice/pull/1543
* Add generic ferrules to harnice-general-library by @kenyonshutt in https://github.com/harnice/Harnice/pull/1546
* Loopback length: turn on the same segment the drawing shows (#1489) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1550
* Block diagram export: mating connectors on top (#1478) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1552
* Rebuild test-harness-1 project data by @kenyonshutt in https://github.com/harnice/Harnice/pull/1553
* 3D views orbit from the body; existing-worktree project menus; pickers start in the library root by @kenyonshutt in https://github.com/harnice/Harnice/pull/1549
* Add generic spade terminals to harnice-general-library by @kenyonshutt in https://github.com/harnice/Harnice/pull/1548


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.11.3...v0.11.4

## [v0.11.3](https://github.com/harnice/harnice-app-releases/releases/tag/v0.11.3)

## What's Changed
* Example connector: put 3d-mate at the origin so it has no offset (#1506) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1515
* Console: run commands in Git Bash, never the WSL launcher (#1514) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1516
* Flying leads: flying_lead_generator macro and formboard opt-in (#1505) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1517
* Commit message box starts with pn-rev: prefix (#1528) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1537
* Block diagram exporter: keep self-closing tags valid when hiding a layer by @kenyonshutt in https://github.com/harnice/Harnice/pull/1538
* Channel Types Manager: keep header text on its own line at any width … by @kenyonshutt in https://github.com/harnice/Harnice/pull/1539


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.11.2...v0.11.3

## [v0.11.2](https://github.com/harnice/harnice-app-releases/releases/tag/v0.11.2)

## What's Changed
* Project open on Windows: no prompt_toolkit crash, say why verify prompts by @kenyonshutt in https://github.com/harnice/Harnice/pull/1511
* 1509 need drawing and body viewer for parts by @kenyonshutt in https://github.com/harnice/Harnice/pull/1512
* Skills ask where connector and cable selection rules live (#1474) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1502
* Worktree UX: free the main folder's branch, faster slider, open/new i… by @kenyonshutt in https://github.com/harnice/Harnice/pull/1513


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.11.1...v0.11.2

## [v0.11.1](https://github.com/harnice/harnice-app-releases/releases/tag/v0.11.1)

# Big changes
Worktrees are now a baked-in part of the git navigator panel

## What's Changed
* Save editor text only to its own project; JSON pages: live validation and library diff by @kenyonshutt in https://github.com/harnice/Harnice/pull/1483
* Stop the editor scroll pin from snapping back after user scrolls by @kenyonshutt in https://github.com/harnice/Harnice/pull/1472
* Add system_bom_exporter macro; rename harness BOM macro by @kenyonshutt in https://github.com/harnice/Harnice/pull/1471
* Check imported harness designs against the system (#397) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1485
* Trace layout macro follows formboard bends (#1480) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1481
* Git buttons echo their commands; conflicts name projects; searchable branch menu by @kenyonshutt in https://github.com/harnice/Harnice/pull/1497
* Give the instances chooser its own vertical drag bar (#1475) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1482
* Store device 3D positions in the system instances list (#1490) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1498
* Write block diagram SVG in one canonical form (#1488) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1500
* 1492 copy warnings only button in stdout by @kenyonshutt in https://github.com/harnice/Harnice/pull/1501
* Branch worktrees: per-project Main/Worktree toggle, sparse worktrees per branch by @kenyonshutt in https://github.com/harnice/Harnice/pull/1499


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.31...v0.11.1

## [v0.10.31](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.31)

## What's Changed
* Print more build progress messages during system builds by @kenyonshutt in https://github.com/harnice/Harnice/pull/1463
* Skills: channel-type compatibility only needs one direction (#1460) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1464
* 1462 channel types tsv needs to reload on each build by @kenyonshutt in https://github.com/harnice/Harnice/pull/1465
* updated defaults to put all outputs inside an if true statement by @kenyonshutt in https://github.com/harnice/Harnice/pull/1466
* Keep project saves inside the open project folder (#1422) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1467
* Keep customer data out of the perf log by @kenyonshutt in https://github.com/harnice/Harnice/pull/1468
* Physical drawing: paint every face back to front, skip faces with holes by @kenyonshutt in https://github.com/harnice/Harnice/pull/1469


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.30...v0.10.31

## What's Changed
* Ask chat replies to use plain language and bullets. by @kenyonshutt in https://github.com/harnice/Harnice/pull/1434
* Print build progress messages during system builds by @kenyonshutt in https://github.com/harnice/Harnice/pull/1463
* Skills: channel-type compatibility only needs one direction (#1460) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1464
* 1462 channel types tsv needs to reload on each build by @kenyonshutt in https://github.com/harnice/Harnice/pull/1465
* updated defaults to put all outputs inside an if true statement by @kenyonshutt in https://github.com/harnice/Harnice/pull/1466
* Keep project saves inside the open project folder (#1422) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1467
* Keep customer data out of the perf log. by @kenyonshutt in https://github.com/harnice/Harnice/pull/1468
* Physical drawing: paint every face back to front, skip faces with holes by @kenyonshutt in https://github.com/harnice/Harnice/pull/1469


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.30...v0.10.31

## [v0.10.30](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.30)

## What's Changed
* Store undo snapshots once, free the window's connections, and log slow requests. by @kenyonshutt in https://github.com/harnice/Harnice/pull/1459


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.29...v0.10.30

## [v0.10.29](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.29)

## What's Changed
* 1443 build button overhaul by @kenyonshutt in https://github.com/harnice/Harnice/pull/1457
* 770 channel types console page by @kenyonshutt in https://github.com/harnice/Harnice/pull/1458


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.28...v0.10.29

## [v0.10.28](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.28)

## What's Changed
* System physical view: ignore hidden bodies, add show/hide all, orbit … by @kenyonshutt in https://github.com/harnice/Harnice/pull/1451
* Physical model drawing: keep partly hidden photos, paint by what is seen by @kenyonshutt in https://github.com/harnice/Harnice/pull/1452
* Stop UI clicks from waiting on invisible fetches by @kenyonshutt in https://github.com/harnice/Harnice/pull/1453
* System physical view: multi-select shows shared pose and drives all d… by @kenyonshutt in https://github.com/harnice/Harnice/pull/1454
* Speed up PDF drawing undo and keep the PDF ribbon from collapsing by @kenyonshutt in https://github.com/harnice/Harnice/pull/1455
* System physical view: put pose, fasten, and fix changes on the undo stack (#1446) by @kenyonshutt in https://github.com/harnice/Harnice/pull/1456


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.27...v0.10.28

## [v0.10.27](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.27)

## What's Changed
* Open library locations without waiting on git. by @kenyonshutt in https://github.com/harnice/Harnice/pull/1432
* Drop saved build connectors at the start of a device build. by @kenyonshutt in https://github.com/harnice/Harnice/pull/1435
* updated drawnby request for harnice cli by @kenyonshutt in https://github.com/harnice/Harnice/pull/1437
* skills update for how to better run harnice cli from device families by @kenyonshutt in https://github.com/harnice/Harnice/pull/1438
* added keystrokes to every gui button by @kenyonshutt in https://github.com/harnice/Harnice/pull/1439
* Performance upgrades 2 by @kenyonshutt in https://github.com/harnice/Harnice/pull/1433
* Make part number not selectable by @kenyonshutt in https://github.com/harnice/Harnice/pull/1440


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.26...v0.10.27

## [v0.10.26](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.26)

## What's Changed
* Fill connector-art labels from the connector underneath by @kenyonshutt in https://github.com/harnice/Harnice/pull/1427
* 1426 the UI got a lot slower over the past few days by @kenyonshutt in https://github.com/harnice/Harnice/pull/1428


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.25...v0.10.26

## [v0.10.25](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.25)

## What's Changed
* add gitignore to every project by @kenyonshutt in https://github.com/harnice/Harnice/pull/1409
* major performance upgrades by @kenyonshutt in https://github.com/harnice/Harnice/pull/1412
* Performance upgrades tests by @kenyonshutt in https://github.com/harnice/Harnice/pull/1414
* Seed missing mate connectors instead of failing the build by @kenyonshutt in https://github.com/harnice/Harnice/pull/1410
* added os import to every build instruction by @kenyonshutt in https://github.com/harnice/Harnice/pull/1411
* 1413 terminal upgrades by @kenyonshutt in https://github.com/harnice/Harnice/pull/1415
* Keep a digit-leading refdes and store its SVG id with a leading colon. by @kenyonshutt in https://github.com/harnice/Harnice/pull/1417
* Teach part-family skills to emit one device project per catalog SKU. by @kenyonshutt in https://github.com/harnice/Harnice/pull/1418
* multi-project undo overhaul by @kenyonshutt in https://github.com/harnice/Harnice/pull/1421


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.24...v0.10.25

## [v0.10.24](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.24)

## What's Changed
* Keep a placed blank panel label and body in step with its rack units by @kenyonshutt in https://github.com/harnice/Harnice/pull/1401
* changed default refdes of blank panel by @kenyonshutt in https://github.com/harnice/Harnice/pull/1402
* Release a stuck block diagram save and show why it failed. by @kenyonshutt in https://github.com/harnice/Harnice/pull/1403


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.23...v0.10.24

## [v0.10.23](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.23)

## What's Changed
* 1304 allow paste of objects across systems by @kenyonshutt in https://github.com/harnice/Harnice/pull/1391
* added device refdes change support by @kenyonshutt in https://github.com/harnice/Harnice/pull/1397
* Update general-library generators and catalogs by @kenyonshutt in https://github.com/harnice/Harnice/pull/1392
* Add Molex and McMaster part numbers to ring terminals by @kenyonshutt in https://github.com/harnice/Harnice/pull/1393
* Update service portable-power-cable attributes by @kenyonshutt in https://github.com/harnice/Harnice/pull/1394
* Update W, SPT, SRDT, and SVT cable attributes by @kenyonshutt in https://github.com/harnice/Harnice/pull/1396
* Update junior and thermoplastic portable-power-cable attributes by @kenyonshutt in https://github.com/harnice/Harnice/pull/1395
* Split console dependencies from the harnice -b package. by @kenyonshutt in https://github.com/harnice/Harnice/pull/1376


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.22...v0.10.23

## [v0.10.22](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.22)

## What's Changed
* Show compatibles on device connector cards by @kenyonshutt in https://github.com/harnice/Harnice/pull/1383
* Add rack blank panel by @kenyonshutt in https://github.com/harnice/Harnice/pull/1382
* updated inkscape installation guidance by @kenyonshutt in https://github.com/harnice/Harnice/pull/1385
* Fan panels by @kenyonshutt in https://github.com/harnice/Harnice/pull/1387
* 1333 update node editor graphics in device physical model by @kenyonshutt in https://github.com/harnice/Harnice/pull/1388
* 1366 add json yaml list as configuration types by @kenyonshutt in https://github.com/harnice/Harnice/pull/1386


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.21...v0.10.22

## [v0.10.21](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.21)

## What's Changed
* Paint physical-model screenshots from back to front. by @kenyonshutt in https://github.com/harnice/Harnice/pull/1375
* keep block diagram undo history when autosaves overlap by @kenyonshutt in https://github.com/harnice/Harnice/pull/1377
* 833 make channel map traces less fug 4 by @kenyonshutt in https://github.com/harnice/Harnice/pull/1378
* Stop a block diagram autosave from reloading an older copy. by @kenyonshutt in https://github.com/harnice/Harnice/pull/1380
* update channel type skills and docs: electrical only, no connector information by @kenyonshutt in https://github.com/harnice/Harnice/pull/1381


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.20...v0.10.21

## [v0.10.20](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.20)

## What's Changed
* removed duplicates from readme by @kenyonshutt in https://github.com/harnice/Harnice/pull/1363
* added attributes json editor by @kenyonshutt in https://github.com/harnice/Harnice/pull/1364
* 1354 changing refdess deletes mates by @kenyonshutt in https://github.com/harnice/Harnice/pull/1365


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.19...v0.10.20

## [v0.10.19](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.19)

## What's Changed
* projects pane bug fix by @kenyonshutt in https://github.com/harnice/Harnice/pull/1347
* fixed bump-in on applied traces group by @kenyonshutt in https://github.com/harnice/Harnice/pull/1345
* fixed lagging block diagram symbol updates by @kenyonshutt in https://github.com/harnice/Harnice/pull/1346
* 1348 fix harness refdes behavior by @kenyonshutt in https://github.com/harnice/Harnice/pull/1355
* fixed a bug causing block diagram to disappear while editing by @kenyonshutt in https://github.com/harnice/Harnice/pull/1356
* changed undo approach on block diagrams by @kenyonshutt in https://github.com/harnice/Harnice/pull/1357
* connector art now highlights with trace selection by @kenyonshutt in https://github.com/harnice/Harnice/pull/1359
* generated remove_unused_instances and added it to default build instr… by @kenyonshutt in https://github.com/harnice/Harnice/pull/1358


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.18...v0.10.19

## [v0.10.18](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.18)

## What's Changed
* updated skills on how to point to reference documentation by @kenyonshutt in https://github.com/harnice/Harnice/pull/1330
* changed git_hash_of_harnice_src to harnice_version by @kenyonshutt in https://github.com/harnice/Harnice/pull/1337
* layers and selection filters in pdf editor by @kenyonshutt in https://github.com/harnice/Harnice/pull/1340
* updated deleted instance behavior in console by @kenyonshutt in https://github.com/harnice/Harnice/pull/1342
* fixed conflicting refdes in physical drawing by @kenyonshutt in https://github.com/harnice/Harnice/pull/1343
* 1332 add harness bundles by @kenyonshutt in https://github.com/harnice/Harnice/pull/1341


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.17...v0.10.18

## [v0.10.17](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.17)

## What's Changed
* 833 make channel map traces less fug 3 by @kenyonshutt in https://github.com/harnice/Harnice/pull/1319
* updated sidebar behavior by @kenyonshutt in https://github.com/harnice/Harnice/pull/1321
* updated signals appearance in connector view by @kenyonshutt in https://github.com/harnice/Harnice/pull/1322
* updated loopback logic by @kenyonshutt in https://github.com/harnice/Harnice/pull/1320
* default refdes is now normal text by @kenyonshutt in https://github.com/harnice/Harnice/pull/1323
* allow refresh on next build for selected devices that have local inst… by @kenyonshutt in https://github.com/harnice/Harnice/pull/1324
* Let the source control branch pill switch and create branches. by @kenyonshutt in https://github.com/harnice/Harnice/pull/1325
* added text wrapping in connector view by @kenyonshutt in https://github.com/harnice/Harnice/pull/1326
* 1313 connector art text is not staying in the middle by @kenyonshutt in https://github.com/harnice/Harnice/pull/1327


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.16...v0.10.17

## [v0.10.16](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.16)

## What's Changed
* added device default build instructions, put on website by @kenyonshutt in https://github.com/harnice/Harnice/pull/1289
* fixed rotation center of primitives in block diagram symbol editor by @kenyonshutt in https://github.com/harnice/Harnice/pull/1290
* Added editable textbox in connector art by @kenyonshutt in https://github.com/harnice/Harnice/pull/1293
* 1291 make scrolling possible in all properties popups by @kenyonshutt in https://github.com/harnice/Harnice/pull/1295
* updated styles dict by @kenyonshutt in https://github.com/harnice/Harnice/pull/1267
* added all-snap rule to group move with objects that need snap by @kenyonshutt in https://github.com/harnice/Harnice/pull/1298
* set up library push to harnice library public by @kenyonshutt in https://github.com/harnice/Harnice/pull/1299
* updatated error message for overconstraining physical mates by @kenyonshutt in https://github.com/harnice/Harnice/pull/1301
* 1241 collapse library folder in harnice general library by @kenyonshutt in https://github.com/harnice/Harnice/pull/1300
* 1259 make the generic rack have depth as a parameter by @kenyonshutt in https://github.com/harnice/Harnice/pull/1302
* added a warning when pasting pngs by @kenyonshutt in https://github.com/harnice/Harnice/pull/1303
* updated trace overlay logic by @kenyonshutt in https://github.com/harnice/Harnice/pull/1305
* builds warn not fail on missing libraries, groups of moving devices s… by @kenyonshutt in https://github.com/harnice/Harnice/pull/1306


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.15...v0.10.16

## [v0.10.15](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.15)

## What's Changed
* updated macro locations in ribbon by @kenyonshutt in https://github.com/harnice/Harnice/pull/1281
* 1255 make delete instance button in the block diagram by @kenyonshutt in https://github.com/harnice/Harnice/pull/1282
* changed color of xyz in triad text fields by @kenyonshutt in https://github.com/harnice/Harnice/pull/1283
* removed bug causing ditched cursor in text field by @kenyonshutt in https://github.com/harnice/Harnice/pull/1284
* corrected mistakes in skills by @kenyonshutt in https://github.com/harnice/Harnice/pull/1285
* block diagram object hitbox updates by @kenyonshutt in https://github.com/harnice/Harnice/pull/1287
* added simple math support to number fields by @kenyonshutt in https://github.com/harnice/Harnice/pull/1288


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.14...v0.10.15

## [v0.10.14](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.14)

## What's Changed
* removed step timestamp rewrite by @kenyonshutt in https://github.com/harnice/Harnice/pull/1273
* removed scroll limits on pdf viewer by @kenyonshutt in https://github.com/harnice/Harnice/pull/1274
* localized git controls to project, removed commit strategy by @kenyonshutt in https://github.com/harnice/Harnice/pull/1275


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.13...v0.10.14

## [v0.10.13](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.13)

## What's Changed
* minor git updates by @kenyonshutt in https://github.com/harnice/Harnice/pull/1269
* 976 make attribute text call actual python by @kenyonshutt in https://github.com/harnice/Harnice/pull/1270


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.12...v0.10.13

## [v0.10.12](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.12)

## What's Changed
* 1250 fix mate connector grievances by @kenyonshutt in https://github.com/harnice/Harnice/pull/1252
* fixed svg write bug by @kenyonshutt in https://github.com/harnice/Harnice/pull/1253
* fixed image attachment bounds by @kenyonshutt in https://github.com/harnice/Harnice/pull/1254


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.11...v0.10.12

## [v0.10.11](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.11)

# Big Changes
* You can now build 3D models of your devices and arrange them into a physical model of your system

## What's Changed
* updated docs to suggest uv if pip doesn't work by @kenyonshutt in https://github.com/harnice/Harnice/pull/1222
* updated button to reinstall new releases by @kenyonshutt in https://github.com/harnice/Harnice/pull/1225
* paste now lands objects under the cursor by @kenyonshutt in https://github.com/harnice/Harnice/pull/1226
* 1096 channels can loop back through passthroughs by @kenyonshutt in https://github.com/harnice/Harnice/pull/1227
* 1223 cable construction in harness 2d viewer by @kenyonshutt in https://github.com/harnice/Harnice/pull/1228
* added channel map console page by @kenyonshutt in https://github.com/harnice/Harnice/pull/1231
* moved channel types out of the harnice repo by @kenyonshutt in https://github.com/harnice/Harnice/pull/1234
* added pull button to library repos by @kenyonshutt in https://github.com/harnice/Harnice/pull/1235
* load source part works properly by @kenyonshutt in https://github.com/harnice/Harnice/pull/1238
* 1232 do loop backs actually show up in harnesses by @kenyonshutt in https://github.com/harnice/Harnice/pull/1239
* edge case examples in docs by @kenyonshutt in https://github.com/harnice/Harnice/pull/1201
* added configuration variables to build instructions banner by @kenyonshutt in https://github.com/harnice/Harnice/pull/1243
* harness build instructions skill and docs overhaul by @kenyonshutt in https://github.com/harnice/Harnice/pull/1100
* updated docs by @kenyonshutt in https://github.com/harnice/Harnice/pull/1244
* 1178 3d arrangement of a system by @kenyonshutt in https://github.com/harnice/Harnice/pull/1245


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.10...v0.10.11

## [v0.10.10](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.10)

## What's Changed
* updated ai docs from prompts to skills by @kenyonshutt in https://github.com/harnice/Harnice/pull/1202
* improved segment dragging behavior by @kenyonshutt in https://github.com/harnice/Harnice/pull/1213
* 1210 channel browser for devices by @kenyonshutt in https://github.com/harnice/Harnice/pull/1214
* 1210 channel browser for devices docs uopdate by @kenyonshutt in https://github.com/harnice/Harnice/pull/1215
* open project now allows opening a pn not just a rev by @kenyonshutt in https://github.com/harnice/Harnice/pull/1216
* fixed issues with editing revision history, added more descriptive wrong project type messaging by @kenyonshutt in https://github.com/harnice/Harnice/pull/1217
* removed strange characters by @kenyonshutt in https://github.com/harnice/Harnice/pull/1219
* allow device flip in block diagram by @kenyonshutt in https://github.com/harnice/Harnice/pull/1218
* attributes now have native curly braces by @kenyonshutt in https://github.com/harnice/Harnice/pull/1220
* added channel trace passthroughs through devices by @kenyonshutt in https://github.com/harnice/Harnice/pull/1180


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.9...v0.10.10

## [v0.10.9](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.9)

## What's Changed
* moved attribute text to config variables or proerties only by @kenyonshutt in https://github.com/harnice/Harnice/pull/1192
* added greyscale by @kenyonshutt in https://github.com/harnice/Harnice/pull/1193
* added better copypaste support by @kenyonshutt in https://github.com/harnice/Harnice/pull/1194
* 1187 git should be more obvious its only committing this project by @kenyonshutt in https://github.com/harnice/Harnice/pull/1195
* opencascade is native; clearer guidance for inkscape installation by @kenyonshutt in https://github.com/harnice/Harnice/pull/1196
* prevented dragging windows off-screen by @kenyonshutt in https://github.com/harnice/Harnice/pull/1197
* setup progress is now saved in appdata by @kenyonshutt in https://github.com/harnice/Harnice/pull/1198
* example connector is added if connector chooser fails by @kenyonshutt in https://github.com/harnice/Harnice/pull/1199
* 1181 ai prompts to ai skills by @kenyonshutt in https://github.com/harnice/Harnice/pull/1200


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.8...v0.10.9

## [v0.10.8](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.8)

## What's Changed
* added auto refdes on harnesses and harness mating connectors by @kenyonshutt in https://github.com/harnice/Harnice/pull/1179


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.7...v0.10.8

## [v0.10.7](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.7)

## What's Changed
* 1158 updates to ai prompt by @kenyonshutt in https://github.com/harnice/Harnice/pull/1175
* primitive updates in system editor by @kenyonshutt in https://github.com/harnice/Harnice/pull/1176
* 1173 harnice library moved to general library by @kenyonshutt in https://github.com/harnice/Harnice/pull/1177


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.6...v0.10.7

## [v0.10.6](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.6)

## What's Changed
* 1168 help setting up should be a list by @kenyonshutt in https://github.com/harnice/Harnice/pull/1169
* updated ctrlz in block diagram symbol editor by @kenyonshutt in https://github.com/harnice/Harnice/pull/1170
* Updates from 10 19 2026 by @kenyonshutt in https://github.com/harnice/Harnice/pull/1171
* * added more glow to channel map glow
* * updated mouse handling of annotations
* * fixed copy bug
* * external git checkout now updates embedded git graph
* * added all and none to selection filter
* * moved magnifying glass search


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.5...v0.10.6

## [v0.10.5](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.5)

## What's Changed
* 1153 handle merge conflicts in revision history natively by @kenyonshutt in https://github.com/harnice/Harnice/pull/1154
* 1151 under hide connectors i want selection filter options by @kenyonshutt in https://github.com/harnice/Harnice/pull/1157
* force map first pass by @kenyonshutt in https://github.com/harnice/Harnice/pull/1155
* 1156 manually writing a signals list from build instructions by @kenyonshutt in https://github.com/harnice/Harnice/pull/1159
* fixed rotation translation mismatch bug by @kenyonshutt in https://github.com/harnice/Harnice/pull/1160


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.4...v0.10.5

## [v0.10.4](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.4)

# Big Changes
* App should now prompt user to update when it detects that a new version is available from git, and handle the update autonomously. 

## What's Changed
* changed ai prompt to clone and run -b directly by @kenyonshutt in https://github.com/harnice/Harnice/pull/1137
* minor updates to cli app @kenyonshutt in https://github.com/harnice/Harnice/pull/1138
* added prompt for cli app to store drawnby by @kenyonshutt in https://github.com/harnice/Harnice/pull/1139
* 1123 export channel map for hierarchical system by @kenyonshutt in https://github.com/harnice/Harnice/pull/1143
* put docs into cli package by @kenyonshutt in https://github.com/harnice/Harnice/pull/1145
* first pass at autoupdates by @kenyonshutt in https://github.com/harnice/Harnice/pull/1146
* 953 add connector icons to symbol editors by @kenyonshutt in https://github.com/harnice/Harnice/pull/1147


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.3...v0.10.4

## [v0.10.3](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.3)

## What's Changed
* Keep the scraped source out of the PyPI upload directory by @kenyonshutt in https://github.com/harnice/Harnice/pull/1136


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.2...v0.10.3

## [v0.10.2](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.2)

## What's Changed
* added copy button to stdout by @kenyonshutt in https://github.com/harnice/Harnice/pull/1133
* Public cli repo by @kenyonshutt in https://github.com/harnice/Harnice/pull/1135


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.10.1...v0.10.2

## [v0.10.1](https://github.com/harnice/harnice-app-releases/releases/tag/v0.10.1)

# Big changes
brought back the command line application and are bringing it back to pip. this is to make it easier to use agentic tools to write build instructions. 

## What's Changed
* Stop device signal prompts from writing an empty signals list. by @kenyonshutt in https://github.com/harnice/Harnice/pull/1129
* subdivisions in 2d networks by @kenyonshutt in https://github.com/harnice/Harnice/pull/1130
* Bring back command line by @kenyonshutt in https://github.com/harnice/Harnice/pull/1132


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.9.6...v0.10.1

## [v0.9.6](https://github.com/harnice/harnice-app-releases/releases/tag/v0.9.6)

## What's Changed
* Stop git checks from flashing a console on Windows by @kenyonshutt in https://github.com/harnice/Harnice/pull/1127


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.9.5...v0.9.6

## [v0.9.5](https://github.com/harnice/harnice-app-releases/releases/tag/v0.9.5)

trying to fix apple codesigning in ci

## What's Changed
* Copy the app into the DMG with ditto and verify the image before nota… by @kenyonshutt in https://github.com/harnice/Harnice/pull/1126


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.9.4...v0.9.5

## [v0.9.3](https://github.com/harnice/harnice-app-releases/releases/tag/v0.9.3)

## What's Changed
* Update docs, smooth out build instructions by @kenyonshutt in https://github.com/harnice/Harnice/pull/1121


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.9.2...v0.9.3

## [v0.9.2](https://github.com/harnice/harnice-app-releases/releases/tag/v0.9.2)

## What's Changed
* 594 git integration by @kenyonshutt in https://github.com/harnice/Harnice/pull/1116
* 1117 reference geometry in the available network context by @kenyonshutt in https://github.com/harnice/Harnice/pull/1119


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.9.1...v0.9.2

## [v0.9.1](https://github.com/harnice/harnice-app-releases/releases/tag/v0.9.1)

## What's Changed
* added beta language to the website by @kenyonshutt in https://github.com/harnice/Harnice/pull/1107
* improved application setup user experience: guidance on git, filepath setup, library installation
    * 1108 startup issues by @kenyonshutt in https://github.com/harnice/Harnice/pull/1110
    * 1108 startup issues 2 by @kenyonshutt in https://github.com/harnice/Harnice/pull/1112
* updated windows menu bar color by @kenyonshutt in https://github.com/harnice/Harnice/pull/1113


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.9.0...v0.9.1

## [v0.9.0](https://github.com/harnice/harnice-app-releases/releases/tag/v0.9.0)

## Big Changes
* Licensing is now required to use the application. I'm starting it at $1/mo. 

I am getting really close to releasing V1.0 which I intend to market and distribute. At this point I will raise the price to the published $50/mo. It guarantees backwards compatibility everywhere. I will keep testing, adding features more slowly now, mostly fixing bugs I find. Stay tuned. 

## What's Changed
* 1092 make git diffs better 2 by @kenyonshutt in https://github.com/harnice/Harnice/pull/1105
* licensing works and is on the website by @kenyonshutt in https://github.com/harnice/Harnice/pull/1106


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.8.0...v0.9.0

## [v0.8.0](https://github.com/harnice/harnice-app-releases/releases/tag/v0.8.0)

## Big changes:
* Multi-channel junctions exist
* This is the last blocking issue that I am aware of that could drive changes to the data model

## What's Changed
* removed all import calls from build instructions by @kenyonshutt in https://github.com/harnice/Harnice/pull/1099
* fully-supported multi-channel junctions by @kenyonshutt in https://github.com/harnice/Harnice/pull/999
* added version number to app by @kenyonshutt in https://github.com/harnice/Harnice/pull/1102


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.7.9...v0.8.0

## [v0.7.9](https://github.com/harnice/harnice-app-releases/releases/tag/v0.7.9)

## What's Changed
* 1073 tests by @kenyonshutt in https://github.com/harnice/Harnice/pull/1080
* fixed issue with drag ghost by @kenyonshutt in https://github.com/harnice/Harnice/pull/1091
* make filepaths shorter by @kenyonshutt in https://github.com/harnice/Harnice/pull/1094
* 1092 reduce needless changes in git diffs of systems by @kenyonshutt in https://github.com/harnice/Harnice/pull/1097


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.7.8...v0.7.9

## [v0.7.8](https://github.com/harnice/harnice-app-releases/releases/tag/v0.7.8)

## What's Changed
* tests shall not run on draft pr's by @kenyonshutt in https://github.com/harnice/Harnice/pull/1089
* 1082 fixed failed windows build in ci by @kenyonshutt in https://github.com/harnice/Harnice/pull/1090


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.7.7...v0.7.8

## [v0.7.6](https://github.com/harnice/harnice-app-releases/releases/tag/v0.7.6)

## Big Changes

* Windows app now exists
* Deleted concept of disconnects: devices now have "passthroughs" as well as "channel endpoints", both of which are eligible for channel mapping. You can now "route" a mapped channel (a "patch") through a passthrough. Note that this feature is not fully vetted. I'm setting up more proper test infrastructure that will be out soon. 

## Commits on Main
* updated docs language by @kenyonshutt in https://github.com/harnice/Harnice/pull/1046
* dev console server by @kenyonshutt in https://github.com/harnice/Harnice/pull/1052
* 1048 fix glow highlight by @kenyonshutt in https://github.com/harnice/Harnice/pull/1055
* 1047 fix toolbar color by @kenyonshutt in https://github.com/harnice/Harnice/pull/1056
* osx app supports multiple windows by @kenyonshutt in https://github.com/harnice/Harnice/pull/1057
* 1058 reveal in finder button by @kenyonshutt in https://github.com/harnice/Harnice/pull/1061
* added signals list console page by @kenyonshutt in https://github.com/harnice/Harnice/pull/1062
* created a windows application by @kenyonshutt in https://github.com/harnice/Harnice/pull/1068
* phase 1 of merging disconnects into devices by @kenyonshutt in https://github.com/harnice/Harnice/pull/1044
* Phase2 by @kenyonshutt in https://github.com/harnice/Harnice/pull/1075
* Phase 4 by @kenyonshutt in https://github.com/harnice/Harnice/pull/1078
* combine disconnect objects into device objects by @kenyonshutt in https://github.com/harnice/Harnice/pull/1069


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.7.5...v0.7.6

## [v0.7.5](https://github.com/harnice/harnice-app-releases/releases/tag/v0.7.5)

## What's Changed
* Update publishing workflows by @kenyonshutt in https://github.com/harnice/Harnice/pull/1045


**Full Changelog**: https://github.com/harnice/Harnice/compare/v0.7.4...v0.7.5
