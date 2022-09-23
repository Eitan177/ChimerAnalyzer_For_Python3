# ChimerAnalyzer_For_Python3
## This is a repository for code originally authored by Jon Young (https://github.com/young-jon/chimeranalyzer) for bone marrow graft chimerism assessment.
### Jon appears to have built it using Python2.7. Here I have tweaked it very modestly so that it can be built with Python3.
### Peaks that are close together and that present interpretation difficulties are not automatically removed in this code. Rather, a warning appears indicating there is a peak with potential interpretation issue and the option to keep or remove the peak is provided. The code is not othererwise changed.

## To build the code on a windows machine:
#### pip install pyinstaller
#### Python3 -m pyinstaller ChimerAnalyzer_JY.py
