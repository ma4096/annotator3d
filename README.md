# annotator3d
Make annotations for &lt;model-viewer>

## Important
This project has been merged with [explore3d](https://github.com/ma4096/explore3d) and I am not working on it anymore, but it should work just fine on its own.

## How it is used/Workflow
1. Add your .glb models (in some folder structure) in the models/ directory.
2. Run makeFileindex.py to index new files and create structure around them.
3. If you want to, you can now add thumbnails (thumbnail.png/.jpg) into the folder _(modelname)
4. start app_annotator.js via node.js (from commandline, go to the directory and type "node app_annotator.js")
5. go to localhost:4000/ to, select a model from the sidemenu and open the options at the bottom.
6. Add your annotations as explained in the options
7. Click the save button (must use a password, which is specified at the top of app_annotator.js)

### Is it safe to use?
I don't know, as I'm not a CS-professional. But I gave it my best :)
