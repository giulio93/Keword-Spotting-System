freezer.py is a script that freezs a checkpoint model converting it in a format usable in the application.
To use it: 
1) change the model file withe corresponding model file architecture, findable in the various model directoryes.
2) insert a model checkpoint in the model directory
3) edit freeze.py changeing the "model architecture" and "start checkpoint" parameter.
4) Run freeze.py and the output file will be in "freeze_model" directory.