# p53DatabaseSite
The p53 database driven by the community project

All python codes are writen under the environment of Python 2.7, MySQL5.7 and Django 1.8. in the platform of Ubuntu 16.

I run the project by the following steps on the Ubuntu terminal:
kun@kun-Lenovo-Y50-70:~$ cd tp53v0

kun@kun-Lenovo-Y50-70:~$source tp53v0_env/bin/activate

kun@kun-Lenovo-Y50-70:~$python manage.py makemigrations tp53_network

kun@kun-Lenovo-Y50-70:~$python manage.py migrate

kun@kun-Lenovo-Y50-70:~$python manage.py runserver

Then type the web arrdess on the IE or Google Chrome web browser: http://127.0.0.1:800/index/ to access the Home Page.

Note: the LSSA and STSFA code are unfinished.

