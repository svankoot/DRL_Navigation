# DRL_Navigation
First project for the Udacity Deep Reinforcement Learning course

##Setup environment
This project was developed with Anaconda and it is suggested to do the same while working with it.

1) To create a new conda environment, run the following
conda create --name drlnd python=3.6 

2) Proceed when prompted. Conda should install all required packages.

3) To activate the environment:
conda activate drlnd

4) Install the correct version of pytorch with: 
```
conda install pytorch=0.4.0 -c pytorch
```

4) The environment we are using is only available as prebuilt need to download it separately.
Download the environment from one of the links below.  You need only select the environment that matches your operating system:
- Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
- Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
- Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
- Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

5) Unzip the environment you just downloaded and place the folder it contains in the same directory as this repository.
For example, on Windows the relative path of the folder with respect to this README should be ../Banana_Windows_x86_64.
The Navigation.ipynb notebook was run on Windows, so if you are on another platform you will need to change the code
to point to the corresponding folder.

6) You will need to install a few packages contained in the udacity/deep-reinforcement-learning repository. Clone the
repository and install the required packages with the following commands.
```
git clone https://github.com/udacity/deep-reinforcement-learning.git
cd deep-reinforcement-learning/python
pip install .
```

7) To launch the Jupyter notebook demonstrating Agent training and performance:
```
jupyter notebook Navigation.ipynb
```

8) You can now explore the notebook and train the agent yourself.
