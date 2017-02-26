# \<alto-timeline\>


<!--
```
<custom-element-demo>
  <template>
   <script src="../webcomponentsjs/webcomponents-lite.js"></script>
   <link rel="import" href="alto-timeline.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<alto-timeline time="09:00 - 10:00" title="Speaker One" icon="icons:book" status="done">Here is some cool
        description
    </alto-timeline>
    <alto-timeline time="10:00 - 11:00" title="Speaker Two" icon="icons:announcement" status="done"> Some text with
        <br/> a breakline to see the border in action
    </alto-timeline>
    <alto-timeline time="11:00 - 12:00" title="Speaker Three" icon="icons:build" status="progress"> Here is also a lnk:
        <a href="https://google.com">Go to Google</a></alto-timeline>
```

<custom-element-demo>
  <template>
    <alto-timeline time="09:00 - 10:00" title="Speaker One" icon="icons:book" status="done">Here is some cool
        description
    </alto-timeline>
    <alto-timeline time="10:00 - 11:00" title="Speaker Two" icon="icons:announcement" status="done"> Some text with
        <br/> a breakline to see the border in action
    </alto-timeline>
    <alto-timeline time="11:00 - 12:00" title="Speaker Three" icon="icons:build" status="progress"> Here is also a lnk:
        <a href="https://google.com">Go to Google</a></alto-timeline>
  </template>
</custom-element-demo>
```
-->
```html
<other-element></other-element>
<my-element></my-element>
```


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