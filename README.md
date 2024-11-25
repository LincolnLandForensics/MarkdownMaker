# MarkdownMaker (MarkdownMaker.py)
Convert documents and files into unified markdown files for use with Obsidian, Notion, Gitub Readme's and other Markdown notebooks.

## installation:

pip install -r requirements_MarkdownMaker.txt

## directions:
pick a folder with files and even subfolders with a variety of different filetypes. 

options:
  -h, --help            show this help message and exit
  -I INPUT folder path (default = current working directory)
  -O OUTPUT folder path (default = ObsidianNotebook)
  -c, --convert         Convert files to markdown
  -b, --blank           create a blank obsidian folder

  
Usage:


```

python MarkdownMaker.py -c (from command prompt) 
```
blank obsidian folder with default settings like dark mode
```
python MarkdownMaker.py -b
```
help
```
MarkdownMaker.exe -H
or
python MarkdownMaker.py -H
```



![sample output](Images/obsidian_sample.png)

