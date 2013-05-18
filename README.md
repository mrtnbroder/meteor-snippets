# Meteor Snippets for Sublime Text

Some snippets for working with the [Meteor](http://meteor.com) framework. (WIP)

Includes snippets for
 * CoffeeScript
 * HTML
 * JavaScript

## Installation

Currently (until [my pull request](https://github.com/wbond/package_control_channel/pull/1357) for the Sublime Text Package Manager got approved by [wbond](https://github.com/wbond/)) you can only install this manually via git.

##### OS X
```
git clone git://github.com/mrtnbroder/meteor-snippets.git ~/Library/Application Support/Sublime Text 2/Packages/Meteor Snippets
```

##### Linux
```
git clone git://github.com/mrtnbroder/meteor-snippets.git ~/.config/sublime-text-2/Packages/Meteor Snippets
```

##### Windows
```
git clone git://github.com/mrtnbroder/meteor-snippets.git %userprofile%\AppData\Roaming\Sublime Text 2\Packages\Meteor Snippets
```

## Snippets

__tp__
```html
<template name="main">
	...
</template>
```

__mr__
```javascript
Meteor.render(function () {
	...
});
```

__mp__
```javascript
Meteor.publish("name", function () {
	...
});
```

__if__
```html
{{#if guyIs "male"}}
	...
{{/if}}
```

__ea__
```html
{{#each player}}
	...
{{/each}}
```