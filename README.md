# retrowave-scene
A Retrowave/Synthwave/Vaporwave inspired scene using Three.js

The scene doesn't include any of its dependencies.

## How to install
The following guidelines are targeted towards non-npm based projects (no webpack/browserify, vanilla JS). However it does require npm in order to get the scene dependencies.

You can add this scene to your project using git submodules, running the following command :\
``git submodule add https://github.com/Moukrea/retrowave-scene.git your/desired/directory/retrowave-scene``

Then, you have to get this scene dependencies (three.js) through npm :\
``cd your/desired/directory/retrowave-scene``\
``npm install``

After that, all you have to to is to import retrowave_scene.js into your JavaScript file (at top level) like this :\
``import { RetrowaveScene } from "./retrowave_scene.js";``\
and make sure you include your JavaScript file into your HTML as a module\
``<script type="module" src="your_javascript_file.js"></script>``\
Check the demo for a working exemple.

Being module based, you have to launch it through a server (being localhost, Wamp, Mamp or whatever else) in order to get it working.
