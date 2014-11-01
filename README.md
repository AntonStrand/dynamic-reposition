Dynamic Reposition
==================

Make it easy to resize a object without having to manually move all the content to keep the margins

![Image of how it works]
(https://www.dropbox.com/s/ka92qmhpzwv7vrc/dynamic-reposition.gif)


##How to install it

###Install manually 

1. [Download the latest release](https://github.com/AntonStrand/dynamic-reposition/releases) and open it
2. Navigate the Sketch menu bar to `Plugins ▸ Reveal Plugins Folder`
3. Place the directory into the revealed plugins directory


##How to use the plugin

1. Select a layer you want to use as an background and rename it to "*background*".
2. Give all the other layers/groups inside of the same group margin properties (see below). 
3. Select the main group.
4. Use the plugin by pressing __cmd+p__* or select _plugins + Dynamic reposition_

* *The shortcut can easily be changed by changing the first row in the plugin* 

You'll need a background. You can either create a layer or a group called "background" or it will take the largest layer in the group and use it as the background. 


###Set properties

You set the margin in the name of the layer. For instance, *t:10:l:50* will position the layer top: 10px and left: 50px.

**You can set properties for:**
 * top      ( *t:* or *top:* )
 * right	( *r:* or *right:* )
 * bottom	( *b:* or *bottom:* )
 * left		( *l:* or *left:* )

 By not setting any properties for top or bottom it will be placed in the middle of the background. If you don't set any properties for left and right it will be centered.


**_Make sure to seperate each property with a semicolon (:)_**


## License
Dynamic Reposition is released under the MIT license. See [LICENSE](LICENSE) for details.