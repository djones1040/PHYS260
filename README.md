Machine-Learning Notebooks for UHH PHYS260
==========================================

Decision tree and convolutional neural net exercises for PHYS260

Dependencies
- jupyter
- astroML
- scikit-learn
- tensorflow
- matplotlib

To install everything on the lab computers and start up jupyter, run these commands from the terminal app and follow prompts as needed:

```
  conda init bash
  [open new tab in terminal and run future commands from that tab]
  conda create -n ml python=3.10
  conda activate ml
  pip install tensorflow --user
  conda install matplotlib
  conda install jupyter
  pip install scikit-learn --user
  pip install astroML --user
  git clone https://github.com/djones1040/PHYS260.git
  cd PHYS260
  jupyter notebook
```

If you restart or log out/back in, start up your previous environment by running this in the terminal:
```
conda activate ml
cd PHYS260
jupyter notebook
```
