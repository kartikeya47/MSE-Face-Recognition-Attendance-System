# MSE-Face-Recognition-Attendance-System

## Steps for Running the Web-App on any Remote Device:

1. If Python is not installed on the machine, install Python from this [link](https://www.python.org/downloads/).

![Screenshot](Screenshots/1.png =250x250)

2. It's recommended to add Python to the path. By doing this, it would be directly added to the Environment Variables and then could be accessed from anywhere.

![Screenshot](Screenshots/2.png)

3. If Git is not installed on the machine, install Git from this link [link](https://git-scm.com/downloads).

![Screenshot](Screenshots/3.png)

4. Now, go to the [repo](https://github.com/kartikeya47/MSE-Face-Recognition-Attendance-System), and click on **Code**.

![Screenshot](Screenshots/4.png)

5. Now, click on the **Copy** symbol.

![Screenshot](Screenshots/5.png)

6. Go to the Desktop, and right click. Click on **Git Bash Here**.

![Screenshot](Screenshots/6.png)

7. Type the following line in the git bash terminal:
```
git clone https://github.com/kartikeya47/MSE-Face-Recognition-Attendance-System.git
```

![Screenshot](Screenshots/7.png)

8. Now, it's observable that a folder named **MSE-Face-Recognition-Attendance-System** has been created in the Desktop.

![Screenshot](Screenshots/8.png)

9. Type in the following commands in the git bash terminal now:
```
cd MSE-Face-Recognition-Attendance-System
```
```
cd Scripts
```
```
source activate
```
```
cd ..
```

![Screenshot](Screenshots/9.png)

![Screenshot](Screenshots/10.png)

The above steps have activated the **Python Virtual Environment**.

10. Now, it's time to install the necessary Python Packages that are required to run the Web App:

```
pip install -r requirements.txt
```

![Screenshot](Screenshots/11.png)

11. Now, all the major steps have taken place. Type the following command in the Git Bash Terminal to run the Web App:

```
python wsgi.py
```

![Screenshot](Screenshots/12.png)





