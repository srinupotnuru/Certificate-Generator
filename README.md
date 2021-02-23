# Certificate-Generator
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

[Use this repo](https://github.com/srinupotnuru/Certificate-Generator/archive/main.zip) :innocent:
### Requirements
```
    >Python 3.8
    >pip
    >opencv
```
### Code to be executed before you proceed
```
    python -m pip install --upgrade pip
    pip install opencv-python
```
### Step 1
Name your template certificate as certificate.png and replace it with the certificate.png in this project. Now run the `getcoodinates.py` . You can see your template certificate like below.

![alt text](https://github.com/srinupotnuru/Certificate-Generator/blob/main/assets/cord.png)

Now **double click** on the template where you wanted to add custom name to get the coordinates. Here i will double click at certificate holders  name blank and event name blank. Press `esc` button to escape from template.
Now coordinates.txt will automatically get generated.

### Step 2
Write the list of names in `certificatenames.txt` in new lines for which you wanted to generate certificate.

### Step 3
Run the `app.py` file in order to get the output certificates.After you run this file target certificates which are generated will be present in **output** folder.
You will get output like below.

![alt text](https://github.com/srinupotnuru/Certificate-Generator/blob/main/assets/output.png)
