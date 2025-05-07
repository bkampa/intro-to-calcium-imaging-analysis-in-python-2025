# Intro to Calcium Imaging Analysis in Python
iBOTS workshop: 07-09 May 2025 

Main Teacher: Dr. Sangeetha Nandakumar

## Software to Install Before the Workshop

    Visual Studio Code (VSCode): https://code.visualstudio.com/download
    The Conda package manager Miniforge: https://conda-forge.org/download/
    Git: https://git-scm.com/downloads

## Get materials onto your local machine

```sh
git clone https://github.com/ibehave-ibots/intro-to-calcium-imaging-analysis-in-python-2025.git
```

## Topics

### Day 1: Calcium Traces to Spikes

```sh
conda create -n calim python=3.12
conda activate calim
pip install numpy tifffile matplotlib scipy scikit-image pyocclient oasis-deconv
```

- [Spiketime Analysis with Numpy and Matplotlib](day1/01.%20Spiketime%20Analysis%20with%20Numpy%20and%20Matplotlib.ipynb)
- [Single-Pixel Fluorescence in Calcium Imaging](day1/02.%20Single-Pixel%20Fluorescence%20in%20Calcium%20Imaging.ipynb)
- [Spike Inference From Calcium Traces](day1/03.%20Spike%20Inference%20From%20Calcium%20Traces.ipynb)
- [Spike Inference From Classifier](day1/04.%20Spike%20Inference%20From%20Classifier.md)



