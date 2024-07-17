
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



## 🤓 Check Out My Excel Add-ins
I've developed some handy Excel add-ins that you might find useful:

- 📊 **[Dashboard Add-in](https://pythonandvba.com/grafly)**: Easily create interactive and visually appealing dashboards.
- 🎨 **[Cartoon Charts Add-In](https://pythonandvba.com/cuteplots)**: Create engaging and fun cartoon-style charts.
- 🤪 **[Emoji Add-in](https://pythonandvba.com/emojify)**: Add a touch of fun to your spreadsheets with emojis.
- 🛠️ **[MyToolBelt Add-in](https://pythonandvba.com/mytoolbelt)**: A versatile toolbelt for Excel, featuring:
  - Creation of Pandas DataFrames and Jupyter Notebooks from Excel ranges
  - ChatGPT integration for advanced data analysis
  - And much more!



## 🤝 Connect with Me
- 📺 **YouTube:** [CodingIsFun](https://youtube.com/c/CodingIsFun)
- 🌐 **Website:** [PythonAndVBA](https://pythonandvba.com)
- 💬 **Discord:** [Join the Community](https://pythonandvba.com/discord)
- 💼 **LinkedIn:** [Sven Bosau](https://www.linkedin.com/in/sven-bosau/)
- 📸 **Instagram:** [sven_bosau](https://www.instagram.com/sven_bosau/)

## ☕ Support 
If you appreciate the project and wish to encourage its continued development, consider [supporting my work](https://pythonandvba.com/coffee-donation).
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://pythonandvba.com/coffee-donation)

## Feedback & Collaboration
For feedback, suggestions, or potential collaboration opportunities, reach out at contact@pythonandvba.com.
![Logo](https://www.pythonandvba.com/banner-img)

