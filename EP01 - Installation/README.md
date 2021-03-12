# Installation

Python is very easy to install as compared to some other languages and also it is very easy to add it to the path.

## 1. How to Download Python
- Visit the Official Website of Python i.e. [python.org](https://www.python.org)
- Go to the [Download](https://www.python.org/downloads/) Section.
- Go to the `Looking for a specific release` and choose either the **Latest Release** i.e **Python 3.9.2** or you can choose any other version but make sure that it is **stable** and **3.7+**.

![image](https://user-images.githubusercontent.com/39031660/110851483-1b263380-82d7-11eb-96b9-6c85b90e1e28.png) |
------------ |
[Looking for a specific release?](https://www.python.org/downloads/) |

- I'll be downloading the **Python 3.9.2** [(Link)](https://www.python.org/downloads/release/python-392/) which is the lastest version on this date.
- Now headover to the buttom of the page where you will see the **Files** section and there you need to select the file/installer according to your system/PC.

![image](https://user-images.githubusercontent.com/39031660/110852413-5aa14f80-82d8-11eb-9c9b-10121b78f9c7.png) |
------------ |
Files Section of Python 3.9.2 |

- Since I have Windows, I will download the `Windows installer (64-bit)` installer which is default recommendation by Python.
- Click on the **Version** and let the file download in your system.

![image](https://user-images.githubusercontent.com/39031660/110852901-f0d57580-82d8-11eb-933c-254390c4526c.png) |
------------ |
Click on the encircled part to download the required version |

<hr>

## 2. Installation

Bravo, you have successfully downloaded the executable file of Python in your system. 🎉
Now its time to **install** Python in your system.

- Go to the download section where you have downloaded the executable format of Python.
- Open the **executable** file of Python that you have downloaded.
- An **installation wizard** will open.

![image](https://user-images.githubusercontent.com/39031660/110965228-ffc03480-8379-11eb-8fb6-ab61a0783c5c.png) |
------------ |
Installation Wizard |

- Before clicking the **Install Now** or **Customize Installation**, make sure to **TICK THE "ADD PYTHON 3.9** (your version number) **TO PATH"**.

![image](https://user-images.githubusercontent.com/39031660/110965827-98ef4b00-837a-11eb-9cc3-17ebca4a435e.png) |
------------ |
Select ADD Python 3.9 to PATH |

- Now click the **Install Now** or **Customize Installation** (according to your requirement).
    - Make sure to keep *DEFAULT* everything to avoid any further problem. You may change it when you need after proper knowledge.
    - Click *NEXT* and *INSTALL* afterwards to Install the Python in your system.
- After all proper setup you will able to complete the installation process of Python.

![image](https://user-images.githubusercontent.com/39031660/110972086-9f34f580-8381-11eb-8ff3-7e0c4dbe1798.png) |
------------ |
Installation Complete Prompt |

<hr>

## 3. Testing Python on Terminal / Command Prompt

In the previous step, we have successfully installed Python in our system and now we have to check if our process was right or not.
For that we will run some python commands in our terminal / command prompt.

- Search CMD on your PC (Windows) and open it.

![image](https://user-images.githubusercontent.com/39031660/110976073-782cf280-8386-11eb-89f3-c6e183fe4114.png) | ![image](https://user-images.githubusercontent.com/39031660/110976296-bcb88e00-8386-11eb-84d3-14705ef14b92.png)
------------ | ------------ |
Searching CMD on Windows | CMD Interface

- So, this is the CMD or Command Prompt interface and we will test the Python here.
- Type `python` or `py` and press **Enter**.
    `C:\Users\saswa>python`
        OR
     `C:\Users\saswa>py`
- It will return a result like this

    ```
    Python 3.9.2 (tags/v3.9.2:1a79785, Feb 19 2021, 13:44:55) [MSC v.1928 64 bit (AMD64)] on win32
    Type "help", "copyright", "credits" or "license" for more information.
    ```
- So, if you get the output as this, then the Python is successfully installed in your system and is successfully executed.
    - Note that here, `Python 3.9.2` is the installed version in my system. It may vary if you have installed other versions. So, don't panic.

- Now let's run some simple Python snippets and test the execution

    ```
    >>> print("Hello, World!")
    Hello, World!
    >>> print(5+10)
    15
    >>> a=10, b=109
    File "<stdin>", line 1
    a=10, b=109
      ^
    SyntaxError: cannot assign to literal
    >>> a = 10
    >>> b = 201
    >>> print(a+b)
    211
    >>> print("Thank You!")
    Thank You!
    >>>
    ```
- So all our code snippets are working properly. And hence the installation of Python in our system is successfull now with testing in CMD.

