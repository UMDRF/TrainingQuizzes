The repository holds a number of Research Reactor Theory Exams from NRC Licensing Exams published on the Agency Documents and Management System (https://adams.nrc.gov/wba/). These are a useful resource for anyone studying for a license exam or looking to learn more about reactors.


The questions are in JSON format and can be accessed using the JupyterQuiz (https://github.com/jmshea/jupyterquiz) utility. This program generates an interactive quiz based on questions and answers defined in a JSON document. This will require Jupyter Notebook to be installed. Jupyter Notebook is included in the Anaconda distribution (https://www.anaconda.com/download). 


Download and install the appropriate version of Anaconda Navigator for your computer.
Open Anaconda Navigator and launch Jupyter Notebook.
Create a new Python 3 Notebook
Install the JupyterQuiz Utility with: pip install jupyterquiz
Launch the utility with: from jupyterquiz import display_quiz
Select the path to the desired quiz in the Github repository i.e. git_path="https://raw.githubusercontent.com/UMDRF/TrainingQuizzes/main/NRCExam1_.json"
Display the quiz: display_quiz(git_path)


The quiz questions will now be displayed, you should be able to select your desired answer. You will receive feedback on if your answer is correct; if it is incorrect, reference information showing where the answer can be found will be provided. 


 Anyone is welcome to use these exercises and/or suggest improvements in the form of issues, pull requests, or email. 
