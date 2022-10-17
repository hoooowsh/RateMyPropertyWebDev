# ratemyhousing-web
RateMyHousing WebApplication client, server and database
This application has been dockerized, to run this application install docker and run the script 'startRMH.sh' as shown below. It's gonna take a while to build the first time. Once installed it will launch quickly. Also be mindful of the space it as it runs in containers ( approx 2.5GB )

1. ```chmod +x rs-init.sh``` <br>
2. ```chmod +x startRMH.sh``` <br>
3. ```./startRMH```


In case of any trouble running the script try this command on the script. (The script was written in Windows and due to that windows adds a extra character at EOL which posix based systems do not do)

```sed -i -e 's/\r$//' scriptname.sh```

Reference: https://stackoverflow.com/questions/14219092/bash-script-and-bin-bashm-bad-interpreter-no-such-file-or-directory
