# This chapter we will create a example project in PyCharm

## Sample Folder Structure

```bash
project_root/

    --- conf/
    --- src/
        --- __init__.py
    --- logs/
    --- data/
    --- sql/
    --- scripts/
    --- test/
    .gitignore
    README.md

```

- `conf`: this folder is to store the configuration files for this project. Based on current experience, yaml is 
easy-to-use format and easy-to-read format
- `src`: this folder is store the project code. Remember to add `__init__.py` in the folder to 
make this as a module
- `logs`: this folder is to store the log file. Remember to put this as git ignore.
- `data`: this folder is to store sample file.
- `sql`: this folder is to store sample query file. `hql` for hive query. `sql` for sql query and `tql` for 
Teradata query.
- `script`: this folder is to store sample script such as scripts to do the log clean and database clean.
- `test`: this folder is to store test code. 
- `.gitignore`: configuration file for git ignore. Suggest to use `.ignore` plugin to generate this file.
- `README.md`: the markdown file to introduce the repo.
    1. This should include the project purpose.
    2. suggest to include the entry point for code.
    3. Better to include some sample test case or test code.
    4. include wiki page or project documentation page link.

## Create a project    
   

## Setup interpreter

In PyCharm, open PyCharm settings. Then choose or add the Python interpreter. 

![Open PyCharm Settings](./img/02-pycharm_settings.png)

![Add the interpreter](./img/03-add_interpreter.png)

## Enable version control



## Create .gitignore File

## Python Module

