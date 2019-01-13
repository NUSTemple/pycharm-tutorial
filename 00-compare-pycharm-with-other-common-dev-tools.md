# Comparison between PyCharm, Jupyter, Spyder and Notepad++



|                             | PyCharm | Jupyter | Spyder | Notepad++ |
| --------------------------- | ------- | ------- | ------ | --------- |
| Version Control Integration | Yes     | No^1^   | Yes    | Yes       |
| Syntax Highlight            | Yes     | Yes     | Yes    | Yes^2^    |
| Debug mode                  | Yes^3^  | Yes     | Yes    | Yes       |
| Directly view the plots     | No      | Yes     | Yes    | No        |
| Other Language Support      | Yes     | Yes^4^  | No     | Yes       |
| Deployment                  | Yes     | No      | No     | Yes       |
| Remote Interpreter          | Yes^5^  | No      | No     | No^6^     |

- *1: Jupyter got plugin to enable Git in Jupyter notebook. However, it is not easy to do so for project development. 
- *2: Need to choose language as python in the language 
- *3: PyCharm can view the variable details by using debug mode. However, it cannot see the variable change after you did the code change unless you re-run the code.
- *4: So far bash only for python kernel
- *5: PyCharm needs professional version
- *6: So far I do not find a way to run server side Python interpreter in Notepad++

In Summary:

1. For development, we can use `Jupyter` or `Spyder` to build your code since we need to frequent change and see the result difference immediately. 
2. For project management, we can use `PyCharm` to better manage our code if our code is more or less stable. 