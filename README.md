# Natural Language Processing for offensive post detection in Social Media

## Datasets
Dataset1 is a mixed language dataset you can download from:
https://github.com/SilentFlame/AggressionDetection 
A copy of the dataset is placed in this directory as well

Dataset2 is an english langauge dataset you can download from:
https://github.com/SilentFlame/AggressionDetection 

## How to run the code:
There are two Jupyter Notebook files one for each dataset
### File1: For Mixed language Dataset
Filename: project_main_code.ipynb

You may not be able to run the part of the code where there is a transliteration library involved:

Here are the instructions to install this package and then proceed with the rest of the run:

Clone the repository:
git clone https://github.com/libindic/indic-trans.git
------------------------OR--------------------------
git clone https://github.com/irshadbhat/indictrans.git
Change to the cloned directory:
<code>
cd indic-trans
pip install -r requirements.txt
python install .
</code>
Note that this has a Microsoft VC++ Executable version dependency and works only a specific machine where I had to use Windows 10 with the installable

If you want to skip this part, you can directly proceed to the heading in the Jupyter Notebook: "## Read the processed data back to a dataframe"
This will load a local copy of the transliterated dataset
From this point on, you will be able to execute the code in any Jupyter Notebook Python Environment

Note that the transfer learning part will require GPU resources

### File2: For English Language OLID Dataset
Filename: project_main_code_OLID.ipynb

This part of the code will run as usual in any Jupyter Notebook Python environment.
Note that the transfer learning part will require GPU resources



