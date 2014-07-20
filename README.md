# MediaRouter

## Changes to the original Mediarouter
- Changed references from AppCompat to the ABS version
- Added onMute listener
- Changed resource that shows 'no cast available' icon to a blank (gray) drawable because when using ABS, the `onDeviceAvailable(..)` callback is not called.

## Dependencies
- Android support-v4
- ActionBarSherlock

## Build Note
In Eclipse, make sure you add the three jellybean* directories to the build path. (Right-click > Build Path > Use as Source Folder)

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

#### Thanks for checking this out.
- [Prem Nirmal](https://plus.google.com/u/0/+PremNirmal/posts)
- [@premnirmal88](https://twitter.com/premnirmal88)
