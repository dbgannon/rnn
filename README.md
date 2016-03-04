## rnn
This contains the code and some model data for the rnn blog.
There are two sets of files here.   The first set is for the cntk lstm example.   it contains

rnn-experiments-for-github.ipynb -- a ipython notebook that explores the embedding space and its properties.

rnn-lstm-for-github.ipynb -- an ipython notebook that demonstrates the financial news halucinator.

The model data is stored in oneDrive.   Here is a link http://1drv.ms/1SmzzB2   (it is 50MB so too big to upload to github.)

The second set of files relate to the tensowflow french translator example.

It does not do the training but it is designed to allow you to interactivly poke and prod the model. To use this you need to run the tranlate.py program with

python translate.py --data_dir [your_data_directory] --train_dir [checkpoints_directory] --size=256 --num_layers=2 --steps_per_checkpoint=50

then set the paths to your_data_directory and the checkpoints_directory in mydata_dir and my_traindir variables below.

this program is effectively the same as running translate.py in decode mode.

python translate.py --decode --data_dir [your_data_directory] --train_dir [checkpoints_directory]

See the copyright for translate.py 
