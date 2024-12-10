This repository demonstrates a subtle bug in ActionScript 3 related to default parameter values.  Default parameters, while generally functional, can exhibit unexpected behavior in specific scenarios such as class definitions. The example showcases the issue and provides a corrected approach.

**Problem**: In ActionScript 3, attempting to assign default values to function parameters within a class definition can lead to runtime errors or unexpected results. 

**Solution**: The resolution involves separating the parameter value assignment from the function signature in the class definition.