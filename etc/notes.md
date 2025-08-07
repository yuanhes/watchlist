#

## commands for running the app (in background)
```
source env/bin/activate
nohup flask run >> nohup.out 2>&1 &
```

## commands for nginx
```
systemctl start nginx
systemctl enable nginx
```

