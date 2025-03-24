# Introduction
This project is a simple calculater for adding and multiplying two numbers.

# Creating Vertual Environment
- First we need to know where and which type of python installed use the command `where python3`

```
emmanuel@MacBookPro my-first-repo % where python3
/Library/Frameworks/Python.framework/Versions/3.12/bin/python3
/Library/Frameworks/Python.framework/Versions/3.11/bin/python3
/Library/Frameworks/Python.framework/Versions/3.10/bin/python3
/usr/local/bin/python3
/usr/bin/python3
/Library/Frameworks/Python.framework/Versions/3.12/bin/python3
/Library/Frameworks/Python.framework/Versions/3.11/bin/python3
/Library/Frameworks/Python.framework/Versions/3.10/bin/python3
```

- Secondly, choose one python version and create a virtual environment for it.

```
emmanuel@MacBookPro my-first-repo % /Library/Frameworks/Python.framework/Versions/3.10/bin/python3 -m venv ./ven
```
- Thirdly we need to activate the virtual environment we have created. Copy the file path of the `ven` folder created above and add `bin/activate`
```
emmanuel@MacBookPro my-first-repo % . /Users/emmanuel/Desktop/Project/my-first-repo/ven/bin/activate
``` 
To know the virtual environment was created their should be the name of the envrinment in the bigining i.e
```
(ven) emmanuel@MacBookPro my-first-repo % 
```

# Installing Package In Virtual Environment (Using requirements.txt)
We use the command `pip install -r requirements.txt
```
(ven) emmanuel@MacBookPro my-first-repo % pip install -r requirements.txt
```
# Steps use Git
## Create Github and Create Repository
You needed to create the github account then go to new and creare repository
## Clone The Repository To Local Device
Copy the HTTPS url `https://github.com/ekbarkacha/my-first-repo.git` 
```
git clone https://github.com/ekbarkacha/my-first-repo.git
```
## The Main Steps
- Create `.gitignore` and include in it files/folders you want to ignore while submitting.
- `git pull` if this is not the fist submit
- `git status`
- `git add`
- `git commit -m "message"`
- `git push`






