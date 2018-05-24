# NLP-Information-Extraction    
     
[Check out the detailed report and source code](https://github.com/DataSorcerer/NLP-Information-Extraction/blob/master/NLP_Information_Extraction.ipynb)    

Information extraction (IE) is the task of automatically extracting **<font color="green">structured information</font>** from **<font color="brown">unstructured and/or semi-structured</font>** machine-readable documents. In most of the cases this activity concerns processing human language texts by means of natural language processing (NLP)    

<b><font color="blue">Objective:</font></b>   
We will consider a collection of text passages having brief descriptions about some of the most popular football players in current generation. The passages have been taken from their respective Wikipedia pages. The task will involve extracting following key information/ relationships from this unstructured data:    
1. Player Name   
2. Country      
3. Teams (Clubs and National)    
4. Birth date   
5. Debut year   
6. Playing positions on the field   

Finally, we create JSON-LD representation of the data, that can be used to build knowledge representation or ontology of football players.    

<b><font color="blue">Note:</font></b>     
We extensively use <font color="brown">*regular expressions* and NLTK</font> functions for implementing various NLP Information Extraction techniques.   
