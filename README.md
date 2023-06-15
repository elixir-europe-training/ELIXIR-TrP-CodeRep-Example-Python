# ELIXIR-TrP-CodeRep-Example-Python
The repository for developing the python script that is to be.  
available to all the CodeRep courses and modified to   
demonstrate that courses key concepts.    

Mark took  MCebisis' first version and made a own version consisting of  (codereppyt1.py, plots.py & models.py along with the csv file in datasets folder) to try and create a version that works well for the Containers course and may be of use for the Software Testing group also.

It takes inspiration from FastQC in that it produces graphics & text that can be inserted into an HTML doc that can be viewer in the users browser of choice or further processed e.g. with pandoc to create a PDF file.

codereppy_batch.py is a full "headless" (non-interactive) implementation and codreppy_min_batch.py is a truncated minimal version of that.
Both need the plots.py & models.py files along with the datasets folder.   

html_gen.py contains functions to be incorporated into codereppy1.py (and the batch derivatives) to create html entries for its text and graphics outputs.   
html_test.py (along with test_image.png file) was used to test the functions in html_gen.py.
