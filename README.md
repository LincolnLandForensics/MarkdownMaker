# MarkdownMaker (MarkdownMaker.py)
Convert documents and files into unified markdown files for use with Obsidian, Notion, Gitub Readme's and other Markdown notebooks.
Can also be used to create a basic Obsidian notebook install, with some settings set. 


## installation:

pip install -r requirements_MarkdownMaker.txt

## directions:
pick a folder with files and even subfolders with a variety of different filetypes. 

## options:

-h, --help            show this help message and exit
-I INPUT, --input INPUT
                        Input folder path
-O OUTPUT, --output OUTPUT
                        Output folder path
-T TEMPLATE, --Template TEMPLATE
                        template path
-c, --convert         Convert files to markdown
-b, --blank           create a blank obsidian folder
-t, --template        copy templated obsidian files/folders

  
## Usage:


```
python MarkdownMaker.py -c (from command prompt) 
```

## Example
```
python MarkdownMaker.py -c -I c:\scripts\python\test_files -O c:\scripts\python\ObsidianNotebook
```


create a blank obsidian folder with default folders and settings
```
python MarkdownMaker.py -b 
```

or

create a blank obsidian case from a template folder (2 folders have been included : Template_2ndBrain & Template_Cases
```
python MarkdownMaker.py -b -t -T Template_Cases
```

## help

```

python MarkdownMaker.py -H
```


Supported images with exif data will have that displayed under the image


![sample output](images/ScreenshotExifData1.jpg)


Scripts will be added to the scripts folder and get added markup language for scripts like python


![sample output](images/python_sample1.jpg)

 
Documents will be added to the documents folder and get added markup language for files like .pdf, .html, .docx, .rtf and more.
There is often a link to the orginal file.

html sample

![sample output](images/html_sample1.png)


eml sample

![sample output](images/eml_sample1.png)




