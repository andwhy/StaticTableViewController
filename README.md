
[![CocoaPods](https://img.shields.io/cocoapods/v/StaticTableViewController.svg?maxAge=2592000)](muyexi)
[![Carthage Compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)
[![license](https://img.shields.io/github/license/mashape/apistatus.svg?maxAge=2592000)](https://muyexi.im)

Swift Port of [StaticDataTableViewController](https://github.com/peterpaulis/StaticDataTableViewController)

## Installation

### CocoaPods

```
pod 'StaticTableViewController'
```

### Carthage

```
github "muyexi/StaticTableViewController"
```

## Usage

Show/hide cells with outlet connections

```
cell(outletStaticCell1, hidden: true)
cells([outletStaticCell1, outletStaticCell2], hidden: true)

reloadDataAnimated(true)
```

## License

StaticTableViewController is released under the MIT license. See LICENSE for details.
