# GBF-DIME-1980
Code to facilitate work with the U.S. Census Bureau's GBF/DIME 1980 files

The following description comes from the [Summary on ICPSR's study homepage:](https://www.icpsr.umich.edu/icpsrweb/ICPSR/studies/8378/summary) 
> A Geographic Base File is a map in machine-readable form, and Dual Independent Map Encoding is the method used for this collection to encode map features in data files. These files have been created for most metropolitan areas. GBF/DIME does not contain individual house addresses, names, or other means of identifying individuals, and it does not contain statistical information. This collection provides a means to structure, compare, and display data, and relate this information to small geographic areas. ICPSR also has the Special Program Information Tape (SPIT) produced by the Census Bureau (See ICPSR 8372), which contains several computer programs designed for use with the GBF/DIME files.

The code presented here pulls the 324 ASCII data files from their individual directories, combines them into one tall text file, and then parses the text file into a CSV file.
