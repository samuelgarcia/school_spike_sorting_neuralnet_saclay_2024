# Mini school GDR neuarlnet - Saclay 2024 - spike sorting

Material for the spike sorting/SpikeInterface training day, part of the [Neuralnet meeting 2024](https://neuralnet2024.sciencesconf.org/).


**To do before the training:**

1. Install SpikeInterface, using the [installation guide](#installation) below
2. Download the [dataset for the tutorials](#dataset)



## Schedule


Tuesday 12th November

15:00-16:00 Introduction to spike sorting (Pierre)
16:00-16:30 Coffee/tea break
16:30-17:30 Overview of SpikeInterface + demo (Samuel)

Wednesday 13th November

09:00-12:00 Tutorials

* Object interaction cookbook
* Probe handling
* Preprocessing
* Drift with generated data
* Postprocessing
* Visualization (Sortingview, Sigui)
* Metrics & Curation (Automerge, etc.)

Given the limited time, the hands-on session is more a follow-along guided tutorials.
You can download all notebooks on this [repo](https://github.com/samuelgarcia/school_spike_sorting_neuralnet_saclay_2024).

If we have time, we can try on your own dataset.







## Installation

This procedure use the new [uv fast installer for python](https://github.com/astral-sh/uv).

**Procedure for Windows/Apple/Linux:**



1. On macOS and Linux. Open a terminal and do $ curl -LsSf https://astral.sh/uv/install.sh | sh
1. On windows. Open a powershell and do powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
2. exit session and log again.
3. Go to this page https://github.com/samuelgarcia/school_spike_sorting_neuralnet_saclay_2024
4. Click on **"code"** (green button) and download the zip. Etxract the zip.
5. open terminal or powershell
6. Go to the correct folder `cd C:/users/myusername/where_the_zip_is`
7. Create an empty env `uv venv si_env --python 3.11`
8. Activate the env `source si_env/bin/activate` (you should have (si_env) in your terminal)
9. `uv pip install -r requirements_tutorial.txt`

**Do not wait to do this during the tutorial, it can be time consuming**


## Dataset

Please download datasets from this link and unzip them:

https://drive.google.com/drive/folders/17RlgsMLheW82IMLMgmTFifVACebDZ8X5?usp=sharing
