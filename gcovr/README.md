## Coverage with gcov
To generate a text report:
```
/apps/venv/bin/gcovr .
```
To generate a HTML report (directory gcovr must exist):
```
/apps/venv/bin/gcovr --html-details -o ./gcovr/main.html
```
or use Terminal -> Run Task... -> gcovr