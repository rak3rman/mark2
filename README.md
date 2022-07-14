# Mark 2

The 2nd iteration of Radison Akerman's personal website, built on Node.js and bare HTML/CSS

## Site Screenshots

Apologies, there seems to be an screenshot issue with the some background images on title sections.

[Home Page PDF (one-pager)](https://github.com/rak3rman/mark2/files/9107212/mark2home.pdf)

## Install and Setup
- Clone the repository from github.com
```
git clone https://github.com/RAK3RMAN/rak3rman-profile.git
```
- Setup Base WebFramework NodeJS
    - Enter the rak3rman-profile folder
        - `cd rak3rman-profile`
    - Install all required packages with root-level access (if needed)
        - `sudo npm install`    
    - Start default application using npm
        - `npm start`
    - If you want a different broadcast port, you can configure these values by proceeding with the:
        - Hardcode option:
            - Enter the `sysConfig.json` file
                - `sudo nano rak3rman-profile/config/sysConfig.json`
            - Edit the `console_port` parameter to your desired configuration
    - If any errors occur, please read the logs and attempt to resolve. If resolution cannot be achieved, post in the issues under this project. 
- Access web application through `localhost:3000`
