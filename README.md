# Gmail_python_testing  

ref:  
tutorial https://www.thepythoncode.com/article/use-gmail-api-in-python  
code https://github.com/x4nth055/pythoncode-tutorials/tree/master/general/gmail-api    

no fork, only copy the portion of gmail python testing  

download https://www.python.org/downloads/release/python-344/  
install python 3.4.4  
DO NOT upgrade pip, uses 3.4.4 as it is.  

set enviroment   
```  
path=%path%;C:\Python34;C:\Python34\Scripts  
```  

install google Oauth api and watchdog
```
cd c:\python34
pip3 install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib  
pip3 install watchdog  
pip install --upgrade google-api-python-client  
pip install typing
```

create folder  
```  
c:\gmail_python  
```  

copy the project file to this folder,  
```
pip3 install -r requirements.txt
```

edit common.py
```
change ourmail@gnail.con to yours.
```

send mail test.bat   
```
chcp 65001
python send_emails.py your_email@gmail.com "This is a subject中文" "Body of the email中文" --files 1.pdf 2.txt 3.tif
```


