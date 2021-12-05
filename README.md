# ScratchFW 0.2
![title](http://lstv.ml/cdn/dock/uploads/KBj0Gzz1Aesfw_b.png)
### About
This is an completly custom text-based Scratch 3.0 GUI.
It is made from complete scratch and can load and edit the project.json files.

You can write scripts with text (like goto(x,y);) and it will automatically convert to the Scratch block.
Features (in beta) an preview feature to preview your project, running on the [TurboWarp Scratch VM](https://github.com/TurboWarp/scratch-vm).

It provides a script that can manipulate with the project simply, like add blocks to it with JS.
That is usefull for automations. Also may be usefull to fix broken projects beacuse of an broken extension.

### Current features
- Can open the project.json
- Loads list of sprites, variables, costumes and sounds and can switch between them for edit
- Can load the list of blocks and modify them
- Has an text editor for scripts where you can type blocks with code to convert to JSON
- Direct JSON editor
- More (like assets support, custom blocks (like from custom extensions) detection) comming soon

### How to use
You can try the full GUI [here](http://lstv.ml/experiments/scratch_fw/s3tb.html)

Or clone everything in the scratch_fw into your server and simply navigate to index.html
Feel free to edit and share. But its recomended to wait until the V1.0 comes because this verzion may be super unstable and does only have few basic features.

The goal si to make a GUI, that is not based on the Scratch's default GUI and is code-based.
Its not meant to fully replace the Scratch editor, just to do some quick edits with big amounts of operations and share code faster.
