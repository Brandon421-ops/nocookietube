# noCookieTube
Avoid cookies and popups on Youtube by clicking a bookmarklet

See: https://brandon421-ops.github.io/nocookietube
##Background

Trying to keep your privacy footprint as low as possible on Youtube is hard. Not being logged in is actively punished, by multiple popups.

This small player is a simple iframe embed, so you can watch Youtube without popups. It also requests videos from the youtube-nocookie domain, so no cookies are stored.

The Youtube Iframe API initialisation is wrapped inside a promise-resolver, so you can easily boot using 

`youtubeApi().then(() => { 
    player = new YT.Player('player'...
`
# Deployment

Table of contents

- Quick & easy deployment
- Deployment configuration explaination
- how to use email OTP Verification mode
- Advanced Deployment
- Filesystem

## Quick & Easy Deployment Options

[![Deploy to Heroku](https://raw.githubusercontent.com/BinBashBanana/deploy-buttons/master/buttons/remade/heroku.svg)](https://heroku.com/deploy/?template=https://github.com/Brandon421-ops/nocookietube)
<br>
[![Run on Replit](https://raw.githubusercontent.com/BinBashBanana/deploy-buttons/master/buttons/remade/replit.svg)](https://replit.com/github/Brandon421-ops/nocookietube)
<br>
[![Deploy to IBM Cloud](https://raw.githubusercontent.com/BinBashBanana/deploy-buttons/master/buttons/remade/ibmcloud.svg)](https://cloud.ibm.com/devops/setup/deploy?repository=https://github.com/Brandon421-ops/nocookietube)
<br>
[![Deploy to Amplify Console](https://raw.githubusercontent.com/BinBashBanana/deploy-buttons/master/buttons/remade/amplifyconsole.svg)](https://console.aws.amazon.com/amplify/home#/deploy?repo=https://github.com/Brandon421-ops/nocookietube)
<br>
[![Run on Google Cloud](https://raw.githubusercontent.com/BinBashBanana/deploy-buttons/master/buttons/remade/googlecloud.svg)](https://deploy.cloud.run/?git_repo=https://github.com/Brandon421-ops/nocookietube)
<br>
[![Deploy on Railway](https://binbashbanana.github.io/deploy-buttons/buttons/remade/railway.svg)](https://railway.app/new/template/pBzeiN)
<br>
[![Deploy To Koyeb](https://binbashbanana.github.io/deploy-buttons/buttons/remade/koyeb.svg)](https://app.koyeb.com/deploy?type=git&repository=github.com/Brandon421-ops/nocookietube&branch=main&name=nocookietube)
<br>
[![Deploy to Render](https://raw.githubusercontent.com/BinBashBanana/deploy-buttons/main/buttons/remade/render.svg)](https://render.com/deploy?repo=https://github.com/Brandon421-ops/nocookietube)
<br>
[![Remix on Glitch](https://binbashbanana.github.io/deploy-buttons/buttons/remade/glitch.svg)](https://glitch.com/edit/#!/import/github/Brandon421-ops/nocookietube)
