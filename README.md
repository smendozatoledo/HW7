# nbdev-linear-regression-tutorial
Behold, the nbdev tutorial for students of CSCI 435!

### Requirements
___
1. Install JupyterLab
   - conda install -c conda-forge -y jupyterlab **OR** pip install jupyterlab
2. Install nbdev
   - **Mac and Linux**:
      - conda install -c fastai -y nbdev **OR** pip install nbdev
   - **Windows**:
      - pip install nbdev==2.3.7
3. Install quarto
   - nvdev_install_quarto
      - Windows will redirect you to install it at the Quarto website
      - **Make sure to restart your terminal afterwards**
   - pip install jupyterlab-quarto
4. Install the required modules if you don't have them already
   - Use either pip or conda
   - matplotlib and numpy
   - Python has csv and datetime already

### Tutorial Steps
___
1. Clone this repository to your computer
2. Go to the terminal and make sure you're in the repo's directory
3. Run jupyter labs in the terminal
4. Navigate to nbs/00_core.ipynb
5. The Jupyter Notebook will take it from there!

Note: All the files other than the README.md were automatically generated by me running `nbdev_new`. 

### Resources Utilized
___
- https://nbdev.fast.ai/tutorials/tutorial.html
- https://jmp75.github.io/work-blog/posts/20221007-nbdev-windows/
   - npdev isn't actually designed for Windows but this madlad somehow made it work anyways
