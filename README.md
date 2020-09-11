# StepAnalysis
This module is dedicated for calculating different Step response analysis factors like  Peak time, Rise time, Settling time, Steady-state value, Overshoot percentage of a specified second order system.

# Requirements
1. This module mandatorily requires Python's Control System library installed and Python version > 3.6.  
1. This module is an extension of Python Control System module and better to use it along with Control System module.
2. Size of Time matrix should be within 5000 to 10000 for better result.
3. Each function defined in this module requires the step response matrix, time matrix and damping factor of the system. Make sure these are properly available.

# Further modification
1. Planning for implementing theoretical calculation and calculating error from it is there. Authors are invited to contribute.

# Installing and importing
1. For Anaconda:
    i) Open Anaconda Prompt.
    ii) Write the following command:
        `pip install -i https://test.pypi.org/simple/ stepanalyser==0.0.1`
    iii) import `stepresponse` to your program.
2. For Jupyter Notebook or Google colab:
    i) Add `pip install -i https://test.pypi.org/simple/ stepanalyser==0.0.1` before writing the program.
    ii) import `stepresponse` to your program.
3. For system installation;
    i) Write the following command in prompt at proper path:
        `pip install -i https://test.pypi.org/simple/ stepanalyser==0.0.1`
    ii) import `stepresponse` to your program.

## For usage example refer `test_example.py` file.
