## Aug 14 Summary 

Today in Class Today 

&nbsp;
<--------------------------------------------------------------Class Summary-------------------------------------->
Question - How would you go about viewing unstructure data?
Lab 3 
 1.Creating a new github repository and making a file in windows termal
 2.Creating a new folder in Google drive and uploading the dataset 
 3.Creating a new Colab file and renaming the file, connecting the file to your Google drive and  putt the code in
 4.Finally, uploading copy to github repository





&nbsp;
&nbsp;
<-----------------------------------------------------------------Class Summary------------------------------------->
&nbsp;
**Lab 1**: Quick Pratice Summary 
- Creaded U.S-daily-Climate reposity in Github 
- Created a new folder in U.S-daily-Climate folder called ==**data**==
- Moved Normal DLY_Sample dataset into data folder

&nbsp;
 **Lab  2**: Quick Pratice Summary

 1. Go To Google Drive 
 2. Created Project folder ==**'CT Project'**==
 3. Created a new folder called 'Dataset' to hold data
 4. Uploaded U.S Daily Normal Climate Dataset to Dataset
 5. Created new Colab notebook called "U.S Daily Climate"

&nbsp;
**Lab 3**: Assignment :
 - [ x] Create your own repository & put a folder in it with 
1. Start with a question - What do want to study/explore?
2. From a collection of dataset, choose data.gov dataset and download the dataset
3. Create github repository 
   - a. create ReadMe.md File
4. click on the Blue button that says ==**Code**==, click on HTTP tab, copy the address
5. Move to windows termal, navigate to 'codingPro' in documents in the temeral 
6. ==Git clone {address}==...The folder should apprear in explorer
7. (In Termial) 
    - a. make new folder call it ==**romandata**==, this will hold your csv dataset file
8. (In Google Drive)
    - a. Create a new folder in Google drive, call it ==**Roman_dataset**==, upload csv file
    - b. open new colab file, rename the colab file to something
9. (In Google Colab)
    - a. Connect your drive to colab by clicking on the ==**google Drive folder icon**==
    - b. Import pandas, numpy  and  add comments to all cells       < --- He will take off points for it
    ``
    import pandas as pd
    import numpy as n
    ``

    &nbsp;
    - c. Using pandas to read the csv file
    ``
     data = pd.read_csv('romans.csv')
    ``
    &nbsp;

    - d. Display top of dataset
    ``data.head()
    ``
    &nbsp;
    - e. Click on File > Save a copy to Github > a new window will appear > choose where the dataset repository is > make sure the bottom button is checked > Click Okay


---------------------------------------------------------------------------------------------

### Lesson 3 : Exploring Data Definitions


**Dataset** 
- a collection of data either strucuted or unstructure data
  - with variety types of data
    - numbers
     - text 
      - images

**Structured dataset**
- organized in well defined format in table format defined rows & columns


**Unstructured Datasets**
- lacks prefefined formats with no strucuture,
    - includes
      - text 
       - image
      - audio

**Datasets Formats**
- Dataset organized in two differnt formats WIDE & LONG being twon common structures.
- wide Format
    - more rows with few columns
- Long Format 
    - few columns and more rows



**Qualitiative data**
- obtaining non-numerical information used to describe qualities, characteristics and experience
   - Data Types
     - Nominal Data
       - Categories without any order, inherent ranking
     - Ordinal Data
        


Question 
  - How would you go about viewing unstructure data?

**Quantitative data**
- data that can be counted or measure, is expressed using numerial value
  - seems more scientistic driven
  - data types 
    


**Understanding the Difference data type**
- Obtaining data/insight from Qualitative data while your identify trends, patterns & relationship from Quantitative data


&nbsp;
&nbsp;
**Lesson 3 Summary**

<p>In this lesson, we explored the essential concepts of data analysis, focusing on the various types of datasets and data—structured, unstructured, qualitative, and quantitative. By understanding the characteristics and formats of these datasets, as well as their distinctions, you are now better equipped to apply appropriate analytical techniques and derive meaningful insights. Mastering these foundational concepts will empower you to effectively navigate the data landscape, enhancing your ability to make informed decisions and unlock the stories hidden within your data. Keep building on this knowledge as you continue your journey in data analysis! 📊✨</p>



What did you get the Information From 
[Coding Temple Lesson 3](https://codingtemple.disco.co/p/data-analytics-3kv6m/curriculum/overview?u=15dca11d-52c3-4dcc-b02a-43cc96b73534)
