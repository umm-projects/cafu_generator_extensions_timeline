# CAFU Generator Extensions / Timeline

## What

* CAFU Generator Extensions for [CAFU Timeline](https://github.com/umm-projects/cafu_timeline)

## Requirement

* Unity 2018
* CAFU Generator

## Install

```shell
yarn add "umm-projects/cafu_generator_extensions_timeline#^1.0.0"
```

## Usage

* Open CAFU Generator
  * `Menu` &gt; `Window` &gt; `Script Generator`

### Generate script set

* You can create scripts necessary for using CAFU Timeline all together
  * `TimelineName` (enum)
  * `TimelineDataStore` (DataStore)
  * `TimelineEntity` (Entity)
* Of course you can also create it individually

![image](https://user-images.githubusercontent.com/838945/41533160-ceb391d2-7334-11e8-9117-eca56ec41d16.png)

* Select `ScriptSet` &gt; `Timeline`
* Press `Generate` button

### Generate Presenter (implement `ITimelinePresenter` )

![image](https://user-images.githubusercontent.com/838945/41533364-789b0fd6-7335-11e8-9e82-0955944b0124.png)

* Select `Presentation` &gt; `Presenter`
* Select scene name
* Check `implements ITimelinePresenter`
* Press `Generate` button

## License

Copyright (c) 2018 Tetsuya Mori

Released under the MIT license, see [LICENSE.txt](LICENSE.txt)

