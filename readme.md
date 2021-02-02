AthenaCL Score generator for Csound (Christopher Ariza, license: GPL)

AthenaCL latest versiuon of AthenaCL can be found here: https://code.google.com/archive/p/athenacl/downloads but the ones i have here are the same.

It uses python 2, and if your machine is still capable to install this old python version and run it, you still have to chance the command in the Blue External Object in order to get the generated score data back into Blue. 

New command:
python2 athenaPipe.py $infile
where athenaPipe.py is installed in the AthenaCL folder.
athenaPipe.py itself can also be found in the examples folder of Blue.

AthenaCL can be installed as a side package of python2, or you can leave it in your home directory and run it from there. In that case, be sure to set the correct PATH.

athenaPipe.py is copyright 2000-2020 Steven Yi, copied here with permission from Steven Yi february 1st 2021.
