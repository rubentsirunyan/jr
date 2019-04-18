# jr | Jump to project root
jr is a simple bash script to jump to the project root from its child directories.

## Installation

* Clone the repo.
  ```
  git clone https://github.com/rubentsirunyan/jr /opt/jr
  ```
* Create an alias that sources the script. 
  * Open your .bashrc file with your favourite editor.
    ```
    vim ~/.bashrc
    ```
  * Add this line to the file.
  ```
  alias jr='/opt/jr/jr'
  ```

## Adding files to match

For now the script uses several file names (like .git, venv, pom.xml) to find the project root directory.
If there are more file names that can be used to identify the project root directory they can be added to `FILE_NAMES` array.
