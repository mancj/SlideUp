 
 # 2.2.7 (13.07.2017)
  - Added definition info for [AboutLibrary](https://github.com/mikepenz/AboutLibraries) (MikePenz)
 # 2.2.6 (13.07.2017)
  - fixed problems with clicks onto `view` with `SlideUp`-effect
  - `SlideUp.Builder` was moved into separated class and renamed to `SlideUpBuilder`
  #### SlideUp
  - method `setTouchebleArea(float touchableArea)` was split to two methods: 
     - `setTouchebleAreaDp(float touchableArea)`
     - `setTouchebleAreaPx(float touchableArea)`
  - method `getTouchebleArea()` was split to two methods:
     - `getTouchebleAreaDp()`
     - `getTouchebleAreaPx()`
  #### SlideUpBuilder
  - method `withTouchebleArea(float touchableArea)` was split to two methods: 
     - `withTouchebleAreaDp(float touchableArea)`
     - `withTouchebleAreaPx(float touchableArea)`
