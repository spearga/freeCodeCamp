---
title: Static Variables
---
## Static Variables

In Python approach any static variables which are assigned a value in class declaration are class variables. Variables that are assigned inside class methods are instance variables.

    class Time: 
      seconds = 60                  # Class Variable 
      def __init__(self,min,hour): 
          self.min = min            # Instance Variable 
          self.hour = hour           # Instance Variable 
  
