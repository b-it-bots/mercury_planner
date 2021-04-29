mercury_planner
===============

Mercury planner is a task planner from International Planning Competition 2014 (IPC) created by 
Michael Katz and Jörg Hoffmann from Saarland University, Germany. 
The original planner file was uploaded [here](https://helios.hud.ac.uk/scommv/IPC-14/repo_planners/Mercury-fixed.zip),
but it is not accessible anymore. Thus we provide the copy of it in this repo under the following url:

        https://github.com/b-it-bots/mercury_planner/blob/master/files/Mercury-fixed.zip
        
This package downloads that file, extracts only the sequential satisfactory folder (seq-sat-mercury) and compiles it.

The dependencies of the planner are:

          sudo apt-get install bison flex gawk g++-multilib pypy
          
NOTE: Keep in mind that the script repository.debs at the root of mas_third_party_software installs

those dependencies along with all the mas_third_party_software dependencies for the rest of the packages.


Manual installation of the planner
==================================

If you want to perform a manual installation of the planner, you could follow the instructions under

        manual_installation.md
