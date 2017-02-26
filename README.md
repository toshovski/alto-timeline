# \<alto-timeline\>

An element used to visualize the timeline

`alto-timeline`
An element used to visualize the timeline


`alto-timeline` is an element which visualizes timelines.
An element used to visualize the timeline.

'alto-timeline' contains the following parameters:

<ul>
 <li> title: The title is shown on the left of the timeline
 <li> icon: icon, shown inside the timeline circle
 <li> status: progress and done
</ul>

Mixins to change the base

|Custom property | Description | Default|
----------------|-------------|----------
`--standard-timeline` | The color for standard status | #2196f3;|
`--progress-timeline` | The color for progress status | #ff9800;|
`--done-timeline` | The color for done status | #93383b;|
`--timeline-time` | Mixin for the time part| {}|
`--timeline-title` | Mixin for the title part| {}|
`--timeline-text` | Mixin for the text part | {}|

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Timeline

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

# Contribution
Feel free to contribute to the timeline component.