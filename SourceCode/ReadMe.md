# Easiest Way to Run (Suggested)

#### Just go to URL mentioned below. This link points to running instance of this project

#### on Google Colab. No setup needed.

#### https://colab.research.google.com/drive/1a6ZOYe1Z2nmkTQLxs_yoYdgBcRKHXEjK

**You have been given viewing rights.**

#### 1. Just click on "Open in Playgroud" button on top left.

#### 2. Go to Runtime Menu and Click on "Run All" to all cells.

#### 3. It will take some time to finish. But, You can see results after 1 epoch in 2nd last cell.


# To Run Locally

#### There is only one file as Jupyter Notebook named " Pokemon2Pokemon. ipynb " with

#### multiple cells. Tu run this notebook you will need following dependencies. Running on CPU

#### is not possible. GPU is needed.

### Dependencies

### Using Conda

#### # CUDA 10.

```
conda install pytorch==1.2.0 torchvision==0.4.0 cudatoolkit=10.0 -c pytorch
# Jupyter
conda install -c conda-forge jupyterlab
```
### Using pip

#### # CUDA 10.

```
pip install torch==1.2.0 torchvision==0.4.0 -f
https://download.pytorch.org/whl/torch_stable.html
# Jupyter
pip install jupyterlab
```

### Other Dependencies

```
numpy
matplotlib
PIL
```

