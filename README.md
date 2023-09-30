# SubSquid
Install nvm

Install Nodejs 16 or higher

Install Docker

Install Squid CLI:

npm i -g @subsquid/cli@latest

Sign in to Aquarium, and obtain (or refresh) the deployment key on the account page by clicking at the profile picture at the bottom.

sqd auth -k "DEPLOYMENT_KEY" #replace "DEPLOYMENT_KEY" with your DEPLOYMENT_KEY

sqd init "your-CLI-name" --template evm

sqd deploy --org "your-CLI" ./...

