CP - Automation files.

_Step 1:_ Open a new file and use param(parameter) For creating a Solution . And create a new Project Name .

Example :
    Param(
    [string]$SolutionName="SampleSolution",
    [string]$ProjetName="SampleProject"
      )

_Step 2:_ In second step , use **" mkdir "** for create new folder for solution **" mkdir SolutionName"**, give the created solution name .

_Step 3:_ And use **" cd "** for entering the folder **"cd ./SolutionName"** ,  For create a folder for new Projects.

_Step 4:_ Name the various Project type like,

Example : 
        $App=$ProjetName+"App"
        $Lib=$ProjetName+"Lib"
        $Test=$ProjetName+"Test"

_Step 5:_ Create the folder for Projects 

        mkdir ./$App
        mkdir ./$Lib
        mkdir ./$Test

Those Steps for creating a folders for CP.

*  Using System.IO For creating a Script for Automation Tool. 

* System.Io.DirectoryInfo: 
            This is using for creating ,moving through Directories and subDirectories.

* System.IO.StreamReader : 

            Using a streamreader that reads a character from a byte stream in a particular encoding.
            Rules for using this System.Io .If you didn't close the reader the reader didn't work.

* System.IO.StreeamWriter :

            Using a streamwriter that write a character from a particular ecoding.
            Rules for using this System.Io .If you didn't close the writer the writer didn't work.

* Directory.CreateDirectory(path)
            Using this to create a new directories and subdirectories in specified path.

 Using this combination to creating a script for Competitive Programming.
