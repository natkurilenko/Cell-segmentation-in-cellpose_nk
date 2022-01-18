# Cell-segmentation-in-cellpose_nk
Create a new environment with conda create --name cellpose python=3.8.
To activate this new environment, run conda activate cellpose
To install the minimal version of cellpose, run python -m pip install cellpose.
To install cellpose, omnipose and the GUI, run python -m pip install cellpose[all]
To upgrade cellpose (package here), run the following in the environment:
python -m pip install cellpose --upgrade
Note you will always have to run conda activate cellpose before you run cellpose. If you want to run jupyter notebooks in this environment, then also conda install jupyter and python -m pip install matplotlib.


For more info (including GPU version) look into "README" in carsen-stringer's cellpose rep. 
