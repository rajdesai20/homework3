Cloud Homework 3 Creating UI 

This is a html page for showing the forecast data in an interactive way. Also ajax and jquery is used to receive the forecast data, so that there is no need to refresh the page.
Flask application is used here and a html template is used for showing data.

URL of instance: http://ec2-18-219-181-67.us-east-2.compute.amazonaws.com/

Installation process for installing apache server and wsgi server:
$ sudo yum update
$ sudo yum install httpd
$ sudo pip install flask
$ sudo youm install mode_wsgi-python27.x86_64

How to use the application:
1. Enter the url of the instance.
2. Enter the date for which forecast is required. 
3. The data will be shown in tabular format with date, tmax and tmin.

If wrong date is entered than a alert will be displayed.







