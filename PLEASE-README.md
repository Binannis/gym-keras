# gym-keras
Reinforcement Learning with Open AI Gym's environment and Keras

**For Linux & Anaconda**
1. Open a terminal
2. cd into the cloned directory
3. Create a new environment using the environment.yml:
  - $ conda env create -f environment.yml
4. Active the environment:
  - $ source activate gym-keras
5. Open jupyter:
  - $ jupyter notebook
6. Enjoy!

**For Linux & Pip**
1. Just install the following packages:
  - $ pip install gym
  - $ pip install tensorflow
  - $ pip install keras
  - $ pip install matplotlib
  - $ pip install numpy
  - $ pip install jupyter
2. cd into the cloned directory
3. Open jupyter:
  - $ jupyter notebook
3. Enjoy!  

**For Docker**
1. Given you have Docker installed:
  - $ docker pull jabusch24/force-keras
  - $ docker run -it --rm --user root -p 8888:8888 -e GRANT_SUDO=yes jabusch24/force-keras
2. In your browser, go to:
  - localhost:8888
3. From the terminal you ran the "run" command from, copy the token in the link and insert it into the jupyter browser window
4. Enjoy!
