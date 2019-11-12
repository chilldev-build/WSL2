# WSL2
Items of note using WSL 1 and WSL 2 in DigitalCrafts August 2019 Cohort

## For binding 127.0.0.1 3000 see bin/www on back_end_project repo
server.listen(port, "127.0.0.1"); </br>
https://github.com/chilldev-build/back_end_project/tree/dev </br>

## For binding 127.0.0.1 3000 see app.js on expressapi repo
    //binding the port for WSL 2 </br>
app.listen('3333',"127.0.0.1", function() { </br>
    console.log('Listening on port 3333'); </br>
});</br>
https://github.com/chilldev-build/expressapi/tree/routes </br>

## WSL2 and Cypress 

https://nickymeuleman.netlify.com/blog/gui-on-wsl2-cypress </br>

### This is the libs to overcome errors.

sudo get-apt update </br>
sudo apt-get install libxtst6 libgconf-2-4 libnss3 libasound2 </br>
sudo apt-get install libgdk-pixbuf2.0-0 </br>
sudo apt-get install libgtk-3-0 </br>
sudo apt-get install libx11-xcb-1 </br>
sudo apt-get install gconf-service libasound2 libatk1.0-0 libc6 libcairo2 libcups2 libdbus-1-3 libexpat1 libfontconfig1 libgcc1 libgconf-2-4 libgdk-pixbuf2.0-0 libglib2.0-0 libgtk-3-0 libnspr4 libpango-1.0-0 libpangocairo-1.0-0 libstdc++6 libx11-6 libx11-xcb1 libxcb1 libxcomposite1 libxcursor1 libxdamage1 libxext6 libxfixes3 libxi6 libxrandr2 libxrender1 libxss1 libxtst6 ca-certificates fonts-liberation libappindicator1 libnss3 lsb-release xdg-utils wget </br>
