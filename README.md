# Tensorflow_Jupyter_CNN
This is an objection detection project,using tensorflow and jupyter notebook.You can  train the model on your own computer（gpu or cpu）.You can also train on server (gpu or tpu) ,like google colab.</p>
<img src="https://i.imgur.com/WK2hjbN.png">

## 1.Tool 
<pre>
tensorflow
python
html js
git
jupyter notebook
chrome
</pre>

## 2.Steps 
<b> 1. </b> Create a new virtual environment
<pre>
python -m venv tfod
</pre>
<b> 2. </b> Activate your virtual environment
<pre>
source tfod/bin/activate # Linux
.\tfod\Scripts\activate # Windows
</pre>
<b> 3.</b> Install dependencies and add virtual environment to the Python Kernel
<pre>
python -m pip install --upgrade pip
pip install ipykernel
python -m ipykernel install --user --name=tfodj
</pre>
<b> 4. </b> Manually divide collected images by Image Collection.ipynb

<b> 5. </b> Train modell and start Detection by Training and Detection.ipynb

<b> 6. </b> open Tensorboard with the following command
<pre>
tensorboard --logdir=.
</pre>
