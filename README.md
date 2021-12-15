# Personal-Information-Scanner
## Introduction
* This is an automatic web personal information scanner.
* This tool is mainly used in the Primary Education Unit in Taiwan, but it can also works well on general web pages.
* By entering the URL, the program can scan all subpage in this url domain,find out the personal information (e.g. Name, ID number, Phone number...) which is hidden in webpage. Finally save all scan results and summarized them as a csv file.

## Download
* Download with zip.
* Download with command.
   ```python=
  sudo git clone https://github.com/Wizard84723/Personal-Information-Scanner.git
  ```
  
## Install
* Request
  * Python 3 ( Optimal 3.9 )
  * requirements.txt

* pip
  ```python=
  pip install -r requirements_pip.txt
  ```
* conda
  ```python=
  conda install -c conda-forge --file requirements_conda.txt
  ```

## I/O
* Input
  * Scan target URL
  * Scan condition
* Output
  * All target subpage files
  * result.csv

## System Model
> The stage has exception handling is marked with a star symbol.

![0000](https://user-images.githubusercontent.com/71222731/146163051-67f00d75-1c96-4977-9317-19503281d26d.png)
