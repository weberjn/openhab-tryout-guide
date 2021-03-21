
## Change the OpenHAB Listen Ports

If you geht the error message that the port is in use, change it for OpenHAB.

Edit `start.sh` and add the variables after the echo line:

    echo Launching the openHAB runtime...
    export OPENHAB_HTTP_PORT=5080
    export OPENHAB_HTTPS_PORT=5083
