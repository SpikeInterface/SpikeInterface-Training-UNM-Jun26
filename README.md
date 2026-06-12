# SpikeInterface-Training-UNM-Jun26

Material for SpikeInterface Tutorial @ UNM - Jun 2026


## Tutorial

The `notebooks/full-tutorial.ipynb` notebook contains a full tutorial that covers the basics of SpikeInterface, including reading data, preprocessing, spike sorting, and analyzing the results. It is designed to be a comprehensive introduction to SpikeInterface for new users.


## Installation

We recommend that you [install uv](https://docs.astral.sh/uv/getting-started/installation/). This is an unbelievably good new package
management tool for Python.

Open your Terminal app and cd (change directory) to where you like to keep github repos. Then clone this repo, and navigate to the `notebooks` folder of it by entering the following commands into your Terminal:

``` shell
git clone https://github.com/SpikeInterface/SpikeInterface-Training-UNM-Jun26.git
cd SpikeInterface-Training-UNM-Jun26/notebooks/
```

Now open jupyter lab (you don't need to install this - uv will take care of it) using uv:

``` shell
uv run jupyter lab
```

Or if you prefer to use vscode:

``` shell
uv run code .
```

If you like traditional virtual environments, please visit [this page](https://github.com/SpikeInterface/spikeinterface/tree/main/installation_tips) to install on your laptop python+spikeinterface.



# Overview of available datasets

The datasets can be downloaded from Zenodo: https://doi.org/10.5281/zenodo.20662886

## In vivo

### M25_D23_2024-11-11_13-11-10_OF1

Neuropixels 2.0 dataset (384 channels) acquired with the Open Ephys GUI in binary format.
You can use the `spikeinterface.extractor.read_openephys()` function to read the data.

### 1544_2023-04-21_09-55-34_of

Recording with 16 channels organized in 4 tetrodes acquired with the Open Ephys GUI in "openephys" format.
You can use the `spikeinterface.extractor.read_openephys()` function to read the data.