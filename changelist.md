### 0.8.0
* Many documentation improvements
* Rename Scenic.Component.Input.Carat to Scenic.Component.Input.Caret. This is a breaking change.
* Rename Scenic.Cache.Hash.compute/2 to Scenic.Cache.Hash.binary/2
* Rename Scenic.Cache.Hash.compute_file/2 to Scenic.Cache.Hash.file/2
* Add Scenic.Cache.Hash.binary!/2
* Rename Scenic.Cache.Hash.compute_file!/2 to Scenic.Cache.Hash.file!/2
* Add ability to put master styles and transforms in a ViewPort config.
* Fold Scenic.Math into the main Scenic project
* Cursor input is now only sent if the mouse is actually over a primitive. This solves
  an inconsistency where sometimes the incoming point would be in local coordinate
  space and sometimes it would be global. If you want to capture that sort of input, either
  cover the space with a clear rect, or capture the input.
* Add the `:direction` option to the `Dropdown` component so can can go either up or down.
* Add specs to functions in components and primitives

### 0.7.0
* First public release