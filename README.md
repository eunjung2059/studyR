# studyR

Here, I am following [The Data Scientist's Toolbox](https://www.coursera.org/learn/data-scientists-tools) on Coursera using Mac. Feb 8 2020 - 

Here are the solutions of the problems that I encountered following the course: 

## On RSTudio...

* __Probrem:__ `File > New Project... > Version Control > Git` throwed error _"RStudio git was not detected on the system path."_
  
  __Solution:__ 

  1. Update brew and git:
  
      On my terminal, `brew update` then `brew upgrade git`.
  
  2. Change setting on RStudio:

      Tools > Global Options > Git/SVN,
      change __Git executable:__ path from `/usr/bin/git` to `/usr/local/bin/git` 
      because my Git was installed there when I checked it by typing `which git` on my terminal.
      
  3. Restart RStudio
  
  
