# TaskBoardApp
Task Board is an app for organizing tasks. Users can create tasks and assign them to specific boards. Also ,they can view, edit and search for tasks based on keywords.

<p align="center">
  <img 
    alt="Software University Logo"
    src="https://vizia.sofia.bg/wp-content/uploads/2018/11/software-university-logo.png"
    width="300"
  >
</p>

> _🧪 A source code of a .NET Core application to be tested, provided by Software University - Bulgaria_

## Test cases
Written test cases by me for this appliation can be found on [this link](https://docs.google.com/spreadsheets/d/13SU_3rEFU_LCW3LDiKVlA823Y8k3MAxC/edit?usp=drive_link&ouid=101865710122533479047&rtpof=true&sd=true). 

My tests improved the quality of the software by:

**1.Catching critical bugs** - critical defects were caught and reported as they would have been costly if they reached production.

Bugs found:

1.API & Edit page cannot be accessed 
2.Tasks are deleted after they have been created

**2.Increasing code reliability** - features were tested under various negative conditions, which made software proner to errors.

Bugs found:

1.Pages cannot be accessed through side bar
2.Empty task can be created 
3.Counter does not display the total number of tasks found when search is performed

**3.Fixed bug in design for documentation** 

Bug found:

Missing requirements for Create Task page in the documentation
