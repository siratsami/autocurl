# autocurl Automated curl request
## Why automating?
because its better to do things easy and fast and curl is one of the most powerful tools we can use while requesting to a website we can request to a website however we want, i have experience with many tools but i said why not to make own tool? so i can request as i need.
## How is that working?
this is just an automated bash script we are using the commands like cat, curl, grep with only one line script, you can run the script directly in the terminal without saving the script but you can copy this script to /usr/bin then only type autocurl and it works.
## Install
git clone https://github.com/siratsami/autocurl.git; cd autocurl; chmod +x autocurl.sh; sudo cp -r autocurl /usr/bin
## Usage
autocurl hosts.txt
### Note
you can edit the request or add heade or however you want by editing the script
