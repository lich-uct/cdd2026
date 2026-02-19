# cdd2026



Repository for the subject CDD





\## Requirements

You will need RDKit, scikit-learn. venv or Conda, Jupyter and Git are also very useful.



\### Version control: git

\#### Linux

```bash

sudo apt install git

```



\#### Windows and Apple

Download and install from \[git](https://git-scm.com/downloads)



\### Virtual environment

venv or Conda



\#### venv

Maybe you will need to install it

python3 -m venv ./venv



\#### conda

Linux

```bash

wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86\_64.sh

\# you will need probably to run:

\# chmod u+x Miniconda3-latest-Linux-x86\_64.sh to run this script

./Miniconda3-latest-Linux-x86\_64.sh

```



Windows

Download and install \[miniconda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/windows.html)



Apple

Download and install \[miniconda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/macos.html)





\## Get started with rdkit with jupyter

\### Should work in all consoles

```bash

git clone https://github.com/lich-uct/cdd2024.git

\# create environment with rdkit, preferably updated version

\# cdd is name of the environment, change this for whatever you like, jupyter is for our convenience, otherwise you can use plain python scripts

conda create -n cdd -c conda-forge rdkit scikit-learn pandas seaborn jupyter

conda activate cdd

jupyter notebook # if you want to run it locally

jupyter notebook --ip 0.0.0.0 --port XXXX # ip 0s to see jupyter on the Internet, port XXXX as maybe you don't want to run it on default 8888 port

```



\## What to do

On your part, please try to apply the workflows onto your particular set, and adapt them for your particular cases. Compare your results to the example case, and to those of your colleagues. We can discuss the results directly in your Jupyter notebooks. If you get stuck at any point, or want some additional information, please do not hesitate to ask - this course is for you.



The example jupyter notebooks with the workflows will be uploaded into the /exercises folder of the repository. I will upload the first notebook soon.



Make your own folders in the root of the repository; 'vecerkok' already has one. Place your own data and notebooks and all other things you need in there, and upload them into this repository at your convenience. You already know git, so this should by no problem... git pull, git commit -m "my message", git push , the usual. Please keep the changes within your own directory, having to merge jupyter notebooks is a pain in the ass.



\## Current exercises

&nbsp;- \[exercises/01\_getting\_started](exercises/01\_getting\_started.ipynb): How to parse structures into RDKit, visualize them, run their methods





\## What expect

You will work on your projects, or 'zapoctovy projekt', which will involve roughly the following:

&nbsp;- Picking a set of known biologically active structures, loading and processing it using RDkit

&nbsp;- Performing a basic analysis of the set, descriptors, scaffolds, fingerprints, similarities, etc.

&nbsp;- Comparing the properties of your picked set with other sets

&nbsp;- Trying out some standard cheminformatic methods on the sets

&nbsp;- Preparing set visualizations

&nbsp;- Making a basic classifier related to your picked and prepared dataset



&nbsp;The extent and exact form of all above points will be determined ad-hoc, depending on time, situation, progress, etc.



\## Resources

&nbsp;- \[Getting started with RDKit in Python](http://www.rdkit.org/docs/GettingStartedInPython.html)

&nbsp;- \[RDKit documentation](https://www.rdkit.org/docs/)



