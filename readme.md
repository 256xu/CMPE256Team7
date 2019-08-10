# CMPE 256 2019 Summer

This is a patent recommendation system project repository for Team 7.
You may view the report, app source code and demo video here.

# TEAM 7 - Patent Recommendation System

Team Members:
* Aaron Lee (ID: 009085596)
* Hongfei Xu (ID:011833978)
* Juan Chen (ID: 012483250)
* Xiaoting Jin (ID: 013842192)

# Contents

* [Final Report](https://github.com/256xu/CMPE256Team7/blob/master/CMPE%20256%20Project%20Report.pdf)
* [Demo and Presentation Video](https://youtu.be/c1Gmq4IN48c)
* [Web Application Source Codes](https://github.com/IdleDust/patent-recommend)


* [Jupyter Notebook Codes and Data](https://github.com/256xu/CMPE256Team7/tree/master/jupyter_codes_and_data)
* [Middle & Final Slides](https://github.com/256xu/CMPE256Team7/tree/master/project_slides)


# Instruction of running app locally
## Dependencies
* Python 3.7
* flask
* sqlite
* pandas

1. Download [Web Application Source Codes](https://github.com/IdleDust/patent-recommend)
2. Install packages by

`pip install -r requirements.txt`

3. Download the common stopwords by

`python recommender/download.py`

then select to download the `popular` section.

4. Set the env variable

`sudo ./setenv.sh`

5. Initialize the sqlite db by

`python manage.py initdb`

6. Start the app by

`python manage.py runserver`



