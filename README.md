# angular-vertical-resizer
An angular directive for vertical resizing divs or other objects

## Installation

1. Download manually or using bower:

        bower install germanger/angular-vertical-resizer --save

2. Then add to your project:

        <link rel="stylesheet" href="vertical-resizer.min.css" />
   
        <script src="angular.min.js"></script>
        <script src="vertical-resizer.min.js"></script>
   
## Usage example

    <div id="div1" style="background-color: #ffdbdb; padding: 10px; height: 80px;"><p>I'm a resizable div</p></div>
    <vertical-resizer target-min-height="50px" target-max-height="150px" target-selector="#div1"></vertical-resizer>

Check `examples.html` for more examples

## Attributes

 - `target-selector`: A dom selector for the object being resized, eg: `#foo`
 - `target-max-height` (optional): Specify if the target has a max height restriction
 - `target-min-height` (optional): Specify if the target has a min height restriction
 - `class` (optional): If not specified, the default class `.germanger-vertical-resizer` will be used

## Contributing

1. Clone
2. Run `bower install` (installs angular)
3. Run `npm install` (installs grunt, and grunt plugins)
4. Run `grunt` (generates minified versions)

