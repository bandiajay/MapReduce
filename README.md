# MapReduce

# Steps for MapReduce Program Execution

1. Download the MapReduceDemo.zip file. To download, click on code button and select 'Download ZIP'
2. Extract the MapReduceDemo.zip file and copy the MapReduceDemo folder to the Eclipse-workspace (You can find Eclipse-workspace in C:\Users\<Your SID>\)(if your system doesn't have Eclipse IDE follow the steps for Eclipse Installation given below)
3. In the Eclipse, File->Open Projects from File System.... Then, click on "Directory" in "Import Projects from File System or Archive" window, then browse the project folder from Eclipse workspace. 
4. Change the program arguments by following below steps <br>
    3.1) Right click on the project select Properties <br>
    3.2) Select Run/Debug settings  in the "Properties for MapReduceDemo" window, and click "New" button. Then, select Java Application, click OK. Give name as "ViewCount". Under the 'Main' tab, and in the "Main class:" search for "ViewCount-mapreducedemo", select it and click OK.  <br>
    3.3 Select the ViewCount and click on 'Edit' button <br>
    3.4 Select the "Arguments" tab, and in the Program Arguments give path for input file and output file as 
    C:\Users\S546833\eclipse-workspace\MapReduceDemo\data\input\rawViews.txt                    
    C:\Users\S546833\eclipse-workspace\MapReduceDemo\data\output 
    (This is sample path of my input and output folder . Replace  C:\Users\S546833\eclipse-workspace\MapReduceDemo\ with your local directory path in above given path.
5. Delete the output Folder from the MapReduceDemo folder (Location: C:\Users\<Your SID>\eclipse-workspace\MapReduceDemo\data)
6. Run the viewcount.java file to get desired output
7. To check for output go to data folder inside project an output folder will be generated after successfully executing program 
8. Open part-r-00000 file inside output folder in your project where the output of the program is stored.


# Steps for Eclipse Installation
1.Eclipse: https://www.eclipse.org/ <br>
2.Download and install the latest version of Eclipse installer. <br>
3.Get the Installer for your platform (student/faculty laptops are windows-x64). <br>
4.Install Eclipse IDE for Enterprise Java and Web Developers from the installer menu. <br>
