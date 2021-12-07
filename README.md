# Pacemaker AI

## Table of contents
- [Preface](https://github.com/MathijsTak/Pacemaker-ai#preface)
- [introduction](https://github.com/MathijsTak/Pacemaker-ai#introduction)
- [Description of what is already known](https://github.com/MathijsTak/Pacemaker-ai#description-of-what-is-already-known)
- [Own research](https://github.com/MathijsTak/Pacemaker-ai#own-research)
- [Product](https://github.com/MathijsTak/Pacemaker-ai/blob/main/README.md#product)
  - Installation
  - How to use
  - Available datasets
  - Settings
- [Conclusion](https://github.com/MathijsTak/Pacemaker-ai#conclusion)
- [Reflexion](https://github.com/MathijsTak/Pacemaker-ai#reflection)
- [Citation](https://github.com/MathijsTak/Pacemaker-ai#citation)

## Preface
With this program we try to predict heart failure. 

## Introduction
Heart failure is one of the most common causes of death. Those affected often aren't aware they are at risk. With this program we try to show people whether it is likely that they will develop heart failure or not.   

## Description of what is already known
- You know how an AI is trained

## Own research

## Product

### Installation
- Download the latest realease
- Extract the zip file on your computer

### How to use
- Open the file named 'Pacemaker AI.exe'
- When the program starts for the first time you need to select the dataset (csv file) you want to use. (This has to be one of the datasets given below)
- To create an AI go to File and select New File
- Here you can set differend parameters for the AI
- When the parameters are set, you can train the AI by going under Train and selecting Train
- When done, you can predict with unknown data and save the file located under the File section
- If you want more information on how to use the program see the Wiki

### Available datasets
- https://www.kaggle.com/fedesoriano/heart-failure-prediction
- https://www.kaggle.com/sulianova/cardiovascular-disease-dataset
- https://www.kaggle.com/andrewmvd/heart-failure-clinical-data
- Note: You can [add other datasets](https://github.com/MathijsTak/Pacemaker-ai/wiki/settings.json) in 'Settings.json'

### Settings
- In settings.json are all the available datasets listed and it is posible to add a dataset yourself.
- You can do this by sorting all the lines. I use a VS Code extension for this, and then add your dataset with the input_values, label and mapping
- To change the default save folder and the dataset you can either edit the settings.json or inside the application under Settings and then Other Settings.

[Project board](https://github.com/MathijsTak/Pacemaker-ai/projects/1?fullscreen=true)


## Conclusion

## Reflection

## Citation
- scikit-learn (new BSD) https://pypi.org/project/scikit-learn/
- pandas (BSD 3-Clause License) https://github.com/pandas-dev/pandas/blob/master/LICENSE
- matplotlib (Python Software Foundation License (PSF)) https://pypi.org/project/matplotlib/3.4.3/
- numpy (BSD License (BSD)) https://github.com/numpy/numpy/blob/main/LICENSE.txt
- zeroone-ai (MIT) https://github.com/MathijsTak/ZeroOneAi
- PySimpleGUI (GNU Lesser General Public License v3.0) https://github.com/PySimpleGUI/PySimpleGUI/blob/master/license.txt
