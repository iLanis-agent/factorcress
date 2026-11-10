# Factorcress 1.0 TEST
Native Android multiplication-header deduction. Android8+ min26/target35. Package com.gg007.factorcress.

## Rules
Known Find the Factors / Factorism adaptation on a 4x4 multiplication table. Fill the four blue top headers with 1, 2, 3, 4 once each, and the four blue left headers with 1, 2, 3, 4 once each. Every gold interior clue must equal its row header multiplied by its column header. Gold clues stay fixed; dots have no clue. Only outside headers accept taps, cycling blank, 1, 2, 3, 4, blank. There is no interior Latin grid to fill. Twelve original uniquely solved puzzles, each with four product clues, distinct clue positions and a distinct eight-factor answer. Undo/reset, levels and saved palette/live-product marks.

## Download and status
https://mega.co.nz/#!5Y8n0CiZ!8JpWaOvPdtt1hgSv418B_wxxnxee28hRvcLx4bCNaMM
APK 16878 bytes; SHA256 01b8f16f53c6a0eb2a0aa489952d657a9e4b61d21dd9dd5beb9746cf3096a6c8. Original certificate SHA2561651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. No requested permissions; original GG007 icon unchanged. Anonymous downloaded bytes match.

## Checks
Seed-851110 generator searches all 576 pairs of permutations and removes clues only while uniqueness remains. Each of twelve boards has exactly one answer. Independent oracle uses pairwise header comparisons and exact division, rather than production bit masks and multiplication. All 390,625 arrays over blank/1/2/3/4 per level are checked: 4,687,500 comparisons, plus 120,000 random/invalid arrays and levels, totaling 4,807,500. Bounds, undo/replay/reset and solved lock pass. Actual drawing-adapter header-center taps solve all twelve; all sixteen interior taps stay inert. Levels, next, menus, privacy, saved palette/live-product marks and completion pass. Seven actual drawing previews inspected, not phone screenshots. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Every one of the 216 prior studio descriptions and 803 legacy descriptions was reviewed. Cagehaven fills interior Latin digits under cage arithmetic, Crossfern fills crossing digit sums, and FactorLab factors integers as a workbench. Factorcress instead assigns eight outside factors under a sparse multiplication-table constraint graph. No matching factory mechanic found. Known multiplication-header deduction adaptation, not a globally new invention. Original generated clue layouts, code and visuals; no source puzzle grids copied. Six fully read sources: two NRICH education pages, the original Find the Factors author, a game publisher, a worksheet publisher and a classroom game aggregator. The latter and NRICH Missing Multipliers use larger factor ranges and optional reveal mechanics; this edition uses fixed four-clue puzzles and 1-4 permutations.

## Build and tests
JDK17/AndroidSDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/factor-test src/com/gg007/factorcress/Board.java BoardTest.java then java -cp /tmp/factor-test com.gg007.factorcress.BoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your private signing material. No signing secret is included. adapter/android contains the Java2D drawing adapter used with FactorAdapterTest.java, not an Android runtime.

## Privacy and branding
Factorcress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, live-product marks and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 menu, original icon, studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and publishing
Complete source/APK, exact cumulative217-card studio and publishing fragments privately preserved:
https://files.instinct.com/nqgkywuxl1p3-factorcress-source-archive
https://github.com/iLanis-agent/factorcress holds README only, full Git source pending. Jekyll includes unchanged, no Pages settings changes or client loader. Both sites verified separately.

## Rule sources
https://www.nrich.maths.org/problems/missing-multipliers
https://nrich.maths.org/problems/multiplication-table-puzzle
https://findthefactors.com/solve-find-the-factors/
https://gridpuzzle.com/factorism
https://mathypuzzles.com/puzzles/multiplication-grid/
https://www.cokogames.com/multiplication-detective-game/
