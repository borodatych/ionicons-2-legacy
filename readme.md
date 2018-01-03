# Ionicons 2 Legacy

Ionicicons 2 Legacy allows you to use Ionicons 2.0.1 alongside Ionicons 3+ in Ionic 2/3+ projects.

The premium icon font for [Ionic](http://ionicframework.com/). Designed by [@benjsperry](https://twitter.com/benjsperry).

Note: All brand icons are trademarks of their respective owners. The use of these trademarks does not indicate endorsement of the trademark holder by Drifty, nor vice versa.

Visit [ionicons.com](http://ionicons.com) and  check out the search feature, which has keywords identifying common icon names and styles. For example, if you search for “arrow” we call up every icon that could possibly be used as an arrow. We’ve also included each icon’s class name for easy copy/pasting when you’re developing!

We intend for this icon pack to be used with [Ionic](http://ionicframework.com/), but it’s by no means limited to it. Use them wherever you see fit, personal or commercial. They are free to use and licensed under [MIT](http://opensource.org/licenses/MIT).

## Adding to an Ionic 2/3+ project

Install Ionicons 2 Legacy:

    npm install ionicons-2-legacy

Add to copy.config.js:

    copyIonicons2LegacyFonts: {
        src: ['{{ROOT}}/node_modules/ionicons-2-legacy/fonts/**/*'],
        dest: '{{WWW}}/assets/fonts'
      },
    copyIonicons2LegacyCss: {
        src: '{{ROOT}}/node_modules/ionicons-2-legacy/css/ionicons-2-legacy.css',
        dest: '{{BUILD}}'
    }

Add to index.html:

    <link href="build/ionicons-2-legacy.css" rel="stylesheet">


## HTML Example

You can use [ionicons.com](http://ionicons.com) to easily find the icon you want to use. Once you've copied the desired icon's CSS classname, simply add the `icon` and icon's classname, such as `ion-2-home` to an HTML element.

    <i class="icon ion-2-home"></i>


## License

Ionicons 2 Legacy is licensed under the [MIT license](http://opensource.org/licenses/MIT).
