#commands

Connect to device
```ssh root@XXX.XXX.X.XXX```

Download templates.json from your reMarkable
```scp root@IP_ADDRESS:/usr/share/remarkable/templates/templates.json ./templates.json```

Upload your new template to your reMarkable
```scp ./NEW_FILENAME root@IP_ADDRESS:/usr/share/remarkable/templates```

Upload templates.json to your reMarkable
```scp ./templates.json root@IP_ADDRESS:/usr/share/remarkable/templates/templates.json```



resources

https://www.simplykyra.com/2021/02/24/how-to-make-template-files-for-your-remarkable/

