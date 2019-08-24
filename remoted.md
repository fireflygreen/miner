## here just a setup of remote access to terminal in your local network

in Ubuntu , you can also use the https://tmate.io, 10 hr lasting

### first tmux

sudo apt install tmux

## install gotty
https://github.com/yudai/gotty

```

> wget https://github.com/yudai/gotty/releases/download/v1.0.1/gotty_linux_amd64.tar.gz
> tar xvzf gotty_linux_amd64.tar.gz
> ./gotty -c [user:password] -w tmux 
```

check the running from browser by : http://localhost:8080/

## port forward
download client from https://ngrok.com/docs
```
> ./ngrok http 8080

-region=eu parameter will enable using the server from europe

```
Authtoken may be needed for some function,without it the fowarding may only work less 12hr


### another way is using http://localhost.run/, but not long lasting

## send out the file
after using wget/curl for downloading file 
by ffsend, 
 https://github.com/timvisee/ffsend
 
 

## download file by gdrive

https://github.com/gdrive-org/gdrive



