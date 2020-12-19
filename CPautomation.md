##                        CP - Automation files.

_Step 1:_ Open a new file and use the param(parameter) For creating a Solution . And create a new Project Name.

Example : Param( 
        [string]$SolutionName="SampleSolution", 
        [string]$ProjetName="SampleProject" 
        )

_Step 2:_ In the second step , use **mkdir** to create a new folder for a solution **mkdir SolutionName**, give the created solution name.

_Step 3:_ And use **cd** for entering the folder **cd ./SolutionName**, To create a folder for new Projects.

_Step 4:_ Name the various Project type like,

Example : $App=$ProjetName+"App" $Lib=$ProjetName+"Lib" $Test=$ProjetName+"Test"

_Step 5:_ Create the folder for Projects

Example : 
        $App=$ProjetName+"App"
        $Lib=$ProjetName+"Lib"
        $Test=$ProjetName+"Test"

_Step 5:_ Create the folder for Projects 

        mkdir ./$App
        mkdir ./$Lib
        mkdir ./$Test

Those Steps for creating a folders for CP.

*  Those Steps for creating a folder for CP.

*  Using System. IO For creating a Script for Automation Tool. 

*  System.IO.DirectoryInfo: 
            This is using for creating, moving through Directories and subDirectories.

*  System.IO.StreamReader : 

            Using a stream reader that reads a character from a byte stream in a particular encoding.
            Rules for using this System.Io.If you didn't close the reader didn't work.

*  System.IO.StreeamWriter :

            Using a stream writer that writes a character from a particular encoding.
            Rules for using this System.Io.If you didn't close the writer didn't work.

*  Directory.CreateDirectory(path)

            Using this to create new directories and subdirectories in the specified path.

 ### Using this combination to creating a script for Competitive Programming.