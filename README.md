# UML_generator-using-AI
## Pip and version check
1. Go to cmd
   1.1 First check the latest python version : python --version
   1.2 then check java version : java -version
2. If everything is okay then it's time for pip installation:
   2.1 pip libraries:
       pip install spacy
       pip install python-docx
   2.2 nlp model:
       python -m spacy download en_core_web_sm
3. Installation of Graphviz:
   go to the website : https://graphviz.org/download/
   <img width="714" height="164" alt="Screenshot 2026-02-27 105331" src="https://github.com/user-attachments/assets/6fe3008c-526e-4573-895e-02feaa9aa3f0" /><br>
   download the EXE installer as per your system
   run it and keep it ok -> ok -> ok
## Creating the main project
1. Create a folder named: UML_generator using AI
2. There create a .py or .ipynb file as per your suite named : uml_generator.py or uml_generator.ipynb
3. go to the uml_generator.ipynb file and go through the code till 6 cell
4. Now go to the website : https://plantuml.com/download
   <img width="1071" height="122" alt="Screenshot 2026-02-27 110112" src="https://github.com/user-attachments/assets/c9d94657-c21d-400a-878a-c23eb9b14558" /><br>
   download it from the download button
   and keep the jar file inside the UML_generator using AI folder
5. create one sample_srs.txt file where you can direct your given website description
   suppose for a example i have given "Online management system" in the repository sample_srs.txt file 
7. Now execute all the cell after 6 given in the UML_generator.ipynb file
6. you will get the desired output as diagram.puml and diagram,png file

## Common problem that may arise
After installing Graphviz:
1.First go to programs in your C drive
2.Locate Graphviz folder
3.there you can find the bin folder
4.copy the path
5.Now click Windows button
6.go to enviroment variables
7.go to user variables
8.click on path 
9.then edit
10.then add new
11.paste the path
12.shut down the whole system
13.restart and continue
   

   







