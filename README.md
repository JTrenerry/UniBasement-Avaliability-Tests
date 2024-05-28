# UniBasement-Avaliability-Tests
Seperate Repo to keep my pi nice and smol :)

## Overview
A cron job was setup on a raspberry pi to run `script/script.sh` every 5 minutes.   

The k6 test:
* sends a `GET` request to the UniBasement frontend homepage to verify the user facing site is accessible
* sends a `GET` request to the UniBasement backend courses route and checks the response body to verify the backend and database are both running
