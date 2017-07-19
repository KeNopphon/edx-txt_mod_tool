Python package dependenies
- lxml, xlrd, xlwt, beautifulsoup4


Workspace folder
- 2 python scripts 
course_struc_extract.py --> this script generates an excel file ‘conversion table’
text_replacement.py --> this script replaces target text components to exported course 
- 4 folders
‘course’ folder --> Unzip an exported edX course and move into this directory 
‘original_course’ --> copy 'course' folder and place it in this directory
‘source’ folder --> Move all translated texts (HTML files) to this directories
'Example' folder --> contain an ‘conversion table’ example files (both before and after filled up contents)


How to run
- Run a python script ‘course_struc_extract.py’ 
   --> excel file ‘conversion_table.xlm’ will be created
- Open the conversion_table 
   --> manually add the path location of translated texts (HTML files) contained inside ‘source’ folder (please see example file for detail)
- Run a ‘text_replacement.py’ 
   --> Original text in 'course' folder will be replaced by the translated texts in 'source' folder
- If program is successfully executed, ready-to-upload course (course.tar.gz) is created inside the 'course' folder



