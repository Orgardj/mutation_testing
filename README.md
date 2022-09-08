# Mutation tool settings
This repository contains config files used for the mutation testing tools  [mull](https://github.com/mull-project/mull) and [dextool mutate](https://github.com/joakim-brannstrom/dextool/tree/master/plugin/mutate) in the master thesis [Recommendations for Mutation Testing as Part of a Continuous Integration Pipeline: With a focus on C++](https://hdl.handle.net/20.500.12380/305137).

# Repository structure
In the folder `tool_settings` folders for each tested project can be found. These folders contain the settings used for mutation testing with [mull](https://github.com/mull-project/mull) and [dextool mutate](https://github.com/joakim-brannstrom/dextool/tree/master/plugin/mutate).

Example:  
tool_settings  
__project1  
____.dextool_mutate.toml  
____mull.yml  
__project2  
____.dextool_mutate.toml  
____mull.yml
