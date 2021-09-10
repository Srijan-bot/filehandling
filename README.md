# filehandling
<br>

## What is data file?
<br>
<p>The files that store data pretaining to a specfic applicatoion for later use.</p>
<br>

## Type of data files =>

1. **Text File**
   1. _RTF(Regular text files)_
   1. _DTF(Delimited text files)_
    * > TSV files(tab seprated value)<br>
    * > CSV files(comma seprated value)
<br>

2.**Binary Files**

**_ lets see the code itself :grin: _**
<br>

[Sample file](https://github.com/Srijan-bot/filehandling/blob/main/sample.txt)
<br>

[Code File](https://github.com/Srijan-bot/filehandling/blob/main/one.py)
<br>
<!-- 1. Item 2 -->


<br>

 **Opening & Closing of file**

 > *syntax:* <file_objectname>=open(<file_name>)

```
f=open("sample.txt","r")
f.close()
```
> Type of function for opening a file.

Symbol | Symbol(Binary) | Name | Function
------------ | ------------ | ------------- | -------------
`r` | `rb` | Read mode | allow file to read-only.
`w` | `wb` | Write mode | allow file to edit in overwrite.
`a` | `ab` | Append mode | allow file to edit **without** overwriting it.

# Read mode (r)

> note! read is **Default** mode means f=open("sample.txt","r") & f=open("sample.txt) are exatly same!.

```
f=open("sample.txt","r")
```
/\ This will open sample file in `f` object.

```
f=open("1.txt","r")
```
/\ This will genrate error shown as follow:
> FileNotFoundError: [Errno 2] No such file or directory: '1.txt'

