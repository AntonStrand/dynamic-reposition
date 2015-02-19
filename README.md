Dynamic Reposition
==================

Make it easy to resize an object without having to manually move all the content to keep the margins

![How to img](http://i.imgur.com/mQlfsni.gif)


##How to install it

First of all you need to have [Sketch 3](http://bohemiancoding.com/sketch/) installed.

###Use Sketch Toolbox (recommended)
Use [Sketch Toolbox](http://sketchtoolbox.com/) to search for `Dynamic Reposition` and click install.

###Install manually

1. [Download the latest release](https://github.com/AntonStrand/dynamic-reposition/releases) and open it
2. Navigate the Sketch menu bar to `Plugins ▸ Reveal Plugins Folder`
3. Place the directory into the revealed plugins directory


##How to use the plugin

1. Select a layer you want to use as an background and rename it to "*background*".
2. Give all the other layers/groups inside of the same group margin properties (see below).
3. Select the main group.
4. Use the plugin by pressing `cmd p` or select `plugins ▸ Dynamic reposition`

*The shortcut can easily be changed by changing the first row in the plugin*

You'll need a background. You can either create a layer or a group called "background" or it will take the largest layer in the group and use it as the background.


###Set properties

You set the margin in the name of the layer. For instance, `My button t:10:l:50` will position the button `top: 10px` and `left: 50px`.

**You can set properties for:**
 * top `t:` or `top:`
 * right `r:` or `right:`
 * bottom	`b:` or `bottom:`
 * left `l:` or `left:`

By not setting any properties for `top` or `bottom` it will be placed in the middle of the background. If you don't set any properties for `left` and `right` it will be centered.

By setting properties for both `top` and `bottom` or/and `left` and `right` the object will be stretched out to keep the right distance to the background. Make sure to _not_ have locked proportions otherwise it wont work as it is supposed to. To have more control over resizing objects make sure to try out my other plugin, [Sketch Resize](https://github.com/AntonStrand/Sketch-Resize)

**You can set size properties for:**
 * width `w:` or `width:`
 * height `h:` or `height:`
 * fontSize `fs:` or `fontSize:`

**_Make sure to seperate each property with a semicolon_** `:`


## License
Dynamic Reposition is released under the MIT license. See [LICENSE](LICENSE) for details.
