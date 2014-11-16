# Meteor Snippets for Sublime Text 2/3

Some snippets for working with the [Meteor](http://meteor.com) framework (v1.0).

Includes snippets for

 * CoffeeScript (✔)
 * HTML (✔)
 * JavaScript (✔) - Updated to 1.0

## Installation

You can install them now via [Package Control](http://wbond.net/sublime_packages/package_control) (search for "Meteor Snippets") or manually via git:

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

## Examples

__tp__
```html
<template name='main'>
	...
</template>
```

__Meteor.render__
```javascript
Meteor.render(function () {
	...
});
```

__Meteor.publish__
```javascript
Meteor.publish('name', function () {
	...
});
```

__if__
```handlebars
{{#if guyIs 'male'}}
	...
{{/if}}
```

__ea__
```handlebars
{{#each player}}
	...
{{/each}}
```

... and a whole lot more!

## Todo's

 * remap some tab triggers
 * fix some snippets (missing semicolons, whitespace, tab behaviour etc.)

## Contributing

Got some neat Meteor snippets you want to share?
fork this repro and send me a pull request!
