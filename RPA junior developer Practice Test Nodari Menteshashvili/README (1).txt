
# UiPath Task Instructions

Thank you for reviewing my UiPath task submission.

Please note that the following paths are hardcoded for now and should be changed to match your local environment:

!!!!!!!!
So as you see there are 4 Folders here. At first i did all tasks seperate but then i used different practice to do them all together
i kindly ask you to chec "All 3 Task in 1" aswell

as paths i added there as variables
excel files will be saved in default local folder

as python injection i had to hardcode some paths as variables

..python_file- is actual python code "acme.py" location which is in main folder

..path is local python interpreter location for example mine is ""C:\Users\nodar\anaconda3""

..library_path is in same folder as path but you have to add your python version dll file for example "C:\Users\nodar\anaconda3\python312.dll"

..current_folder is location of this project and in case interpretator is set on 64x



!!!!!!!!

1. **Folder Path**
   - Variable/File: "FolderPath" in Main.xaml (or in config)
   - Example value: "C:\Users\Nodari\Documents\MyProject\Data"
   - Replace with: A valid folder path on your machine where data is stored.

2. **Project Path**
   - Used for saving/loading Excel or other project files
   - Change to your local folder if needed

3. **Python Interpreter Path**
   - Used in "Python Scope" activity
   - Current value: "C:\Users\Nodari\AppData\Local\Programs\Python\Python310\python.exe"
   - Replace with your local Python executable path

4. **Python Dependencies**
   - Requires: pandas, numpy (example)
   - Install via pip before running: `pip install pandas numpy`

Let me know if any questions come up, and thank you for your consideration!
