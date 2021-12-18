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
* pip
  ```python=
  pip install -r requirements_pip.txt
  ```
  * Terminal screen
      * Start
         ![q1](https://user-images.githubusercontent.com/71222731/146593733-fc8be585-5cbc-4653-b24f-398d5bb6b17d.png)
      * Terminate
         ![q2](https://user-images.githubusercontent.com/71222731/146593752-9d277695-7daa-4c0f-9893-680eab44ea32.png)

* conda
  ```python=
  conda env create --file requirements_conda.yml
  ```
   * Terminal screen
      * Start
          ![w1](https://user-images.githubusercontent.com/71222731/146593782-f63f7dd9-6a70-41d1-9fc4-83ec7a8462a6.png)
      * Terminate    
          ![w2](https://user-images.githubusercontent.com/71222731/146593809-a4d52828-7651-43ef-af9e-46a1fa2236d6.png)

## I/O
* Input
  * Scan target URL
  * Scan condition
      * Selection criteria
      * Number of occurrences
      * Define the scan range
* Output
  * All target subpage files
  * result.csv

## System Model
> The stage has exception handling is marked with a star symbol.

![0000](https://user-images.githubusercontent.com/71222731/146163051-67f00d75-1c96-4977-9317-19503281d26d.png)

## Reference
* Phone format
   * https://zh.wikipedia.org/wiki/%E4%B8%AD%E8%8F%AF%E6%B0%91%E5%9C%8B%E9%9B%BB%E8%A9%B1%E8%99%9F%E7%A2%BC 
* Address format
   * https://www.post.gov.tw/post/internet/Postal/index.jsp?ID=208
* White list
   * http://technology.chtsai.org/namelist/
* Black list
   * Collect by myself.
