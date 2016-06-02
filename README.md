# Flexbox Grid

This is a super light weight flexbox grid system. It's based on Bootstrap grid and maintains an almost identical class naming structure to make
swapping it in / out of projects that bit easier and make using it a lot less of a mental burden as flexbox is enough of that already. 

Pull the project in via Bower and include the `grid.less` file in your project. 

## Changes

* To make changes clone this project and run `npm install`
* Run `npm run build:css` to build your changes
* Preview changes in `index.html` file and update accordingly
* Make your changes and run the tests to make sure it still works (coming soon hopefully some tests)
* Commit and tag

## Usage

This uses Bootstrap grid classes to make switching to this super simple:

```
<div class="row">
	<div class="col-xs-4"></div>
	<div class="col-xs-4"></div>
	<div class="col-xs-4"></div>
</div>
```

## Modifiers

Each breakpoint has grid modifiers for vertical alignment and column spacing:

```
.align-bottom-xs, .align-middle-xs, .align-top-xs
```

```
.around-xs or .between-xs
```