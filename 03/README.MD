# AWS VSCODE Setup

* URL https://awsacademy.instructure.com/
* Course TELE36058 Software Defined Networks - AWS Academy Learner Lab - Foundation Services [13522]

## How to Log in 
1. Log into the https://awsacademy.instructure.com/ portal
2. ![image1](image1.png)
3. Start the Lab "Start Lab"
4. ![image2](image2.png)
5. Get the details for VSCode > click on AWS Details
6. ![image3](image3.png)
7. Download and install AWS CLI https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html 
8. Configure AWS ```aws configure ``` add your 
9. Edit your aws profile to add the "aws_session_token" 


### Example aws profile
* Once you have install aws cli you can edit your profile manually using vscode or notepad
* credential file is located in a hidden folder ```~/.aws/credentials```

```
[default]
aws_access_key_id = ASIASD5C6ZVXTDCYIM5P
aws_secret_access_key = OLDok4bHy3EyukxhFsLxspCEitLkDvCuIJJuXvUx
aws_session_token = FwoGZXIvYXdzEOb//////////wEaDDFC7xYeqC8cDKV6UCK9AZp7anDBoqByKlGFhoaHSTX5EMQntGFuYi6D04aLyV6vPvBXT6kVUngzA0HjivQRiKbuEHEHbsNLuEA3F/NlyO6mL8OPymkzUoDIYaY0EOwXAMVwch9KTEgTm72JVI7xcXqX58hYgc7buQUxlaguMDqIOonFjVaJO9pLpgzR98gmG4tYsV9r3V1zFvKL3oLFrexFd+qlbqqF/Wlmb2O6ygQo/rRU6s9OvPpHtN6c9r2DTVtVDgvRrj71i/JYsijdgaCPBjItZ3mLOg9HctQrKzwlqd7L/RilXUWb73ZjLcjmy9Uy1OTxFKvlAHGVUHtnAuZe
```

### Example on how to set your variables using Windows PowerShell

```
$env:aws_access_key_id += "ASIASDdYIM5P"
$env:aws_secret_access_key += "OLDokdxhFsLxspCEitLkDvCuIJJuXvUx"
$env:aws_session_token += "FwoGZXIvYXdzEOb//////////wEaDDFC7xYeqC8cDKV6UCK9AZp7anDBoqByKlGFhoaHSTX5EMQntGFuYi6D04aLyV6vPvBXT6kVUngzA0HjivQRiKbuEHEHbsNLuEA3F/NlyO6mL8OPymkzUoDIYaY0EOwXAMVwdBjItZ3mLOg9HctQrKzwlqd7L/RilXUWb73ZjLcjmy9Uy1OTxFKvlAHGVUHtnAuZe"
```


### Example on how to set your variables using Linux Bash

```
export aws_access_key_id=ASIASD5dCYIM5P
export aws_secret_access_key=OLDok4dhFsLxspCEitLkDvCuIJJuXvUx
export aws_session_token=FwoGZXIvYXdzEOb//////////wEaDDFC7xYeqC8cDKV6UCK9AZp7anDBoqByKlGFhoaHSTX5EMQntGFuYi6D04aLyV6vPvBXT6kVUngzA0HjivQRiKbuEHEHbsNLuEA3F/NlyO6mL8OPymkzUoDIYaY0EdjdgaCPBjItZ3mLOg9HctQrKzwlqd7L/RilXUWb73ZjLcjmy9Uy1OTxFKvlAHGVUHtnAuZe
```
