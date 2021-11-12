
# How to Loop Through Folders and Subfolders

Have you ever wanted to work your way through folders and subfolders programmatically? This tutorial will show you how to loop through folders and subfolders using Python and return the list of files. To iterate over all files in a directory (incl. subdirectories), we only need ONE LINE of code. In particular, we will be using Python's Pathlib module. Pathlib comes by default with Python 3.4 and above.  
Additionally, I will show you some practical use-cases, such as merging many Excel files into one master file and manipulating Excel workbooks in bulk.

## Code Snippet

```
from pathlib import Path
INPUT_DIR = Path.cwd() / "Your_Folder_Name"
for file in list(INPUT_DIR.rglob("*.xls*")):
    # Do something
```


## Video Tutorial

[![YouTube Video](https://img.youtube.com/vi/w6-28jcr09Q/0.jpg)](https://youtu.be/w6-28jcr09Q)


## Author

- Sven from Coding Is Fun
- YouTube: https://youtube.com/c/CodingIsFun
- Website: https://pythonandvba.com


## Feedback

If you have any feedback, please reach out to me at contact@pythonandvba.com


![Logo](https://content.screencast.com/users/jubbel3/folders/Snagit/media/c42ea34b-4057-4754-96b0-e8e05c866afb/08.18.2021-19.56.png)

