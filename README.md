How to run BDD with  behave  and python in VS code

-Create new Workspace for BDD in VScode

-Create new venv BDD_VENV and activate in terminal

-Goto Extentions and install Behvae VSC pre release version

-Goto python extention settings select workspace tab and change interpreter path to virtual environment venv python path


-First, install behave - pip install behave

-Now make a directory called “features”. In that directory create a file called “tutorial.feature” containing:

Feature: showing off behave

  Scenario: run a simple test
  
     Given we have behave installed
     
     When we implement a test
     
     Then behave will test it for us!
     
     
-Make a new directory called “features/steps”. In that directory create a file called “tutorial.py” containing:
refer https://behave.readthedocs.io/en/latest/tutorial/
