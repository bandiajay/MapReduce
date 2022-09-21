# MapReduce

# Steps for MapReduce Program Execution

1. Download the .Zip File (Click on Code Tab and select Download Zip)
2. Extract the .Zip file and copy the MapReduceDemo folder to the Eclipse-workspace (You can find Eclipse-workspace in C:\Users\<Your SID>\)
3. Open the MapReduceDemo folder  by  selecting Open projects from FileSystem in Eclipse
4. Change the program arguments by following below steps <br>
    3.1 Right click on project  select properties <br>
    3.2 Select run/Debug settings and  select ViewCount click edit . if you don't find ViewCount click on New select java Application give name as ViewCount in main class search for  "ViewCount-mapreducedemo" click on ok  <br>
    3.3 click on argumnets tab <br> 
    3.4 In program Arguments give path for input file and output file as C:\Users\S546833\eclipse-workspace\MapReduceDemo\data\input\rawViews.txt                    C:\Users\S546833\eclipse-workspace\MapReduceDemo\data\output (This is sample path of my input and output folder . Replace  C:\Users\S546833\eclipse-workspace\MapReduceDemo\ with your local directory path in above given path.
5. Delete the output Folder from the MapReduceDemo folder (Location: C:\Users\<Your SID>\eclipse-workspace\MapReduceDemo\data)
6. Run the viewcount.java file to get desired output
7. To check for output go to data folder inside project an output folder will be generated after successfully executing program 
8. Open part-r-00000 file inside output folder in your project where the output of the program is stored.
