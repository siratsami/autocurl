#!/bin/bash

echo "Automated bash script to grab http resposne banners"
echo "This script grabs the http status code as https, you can edit it"
echo "Usage: bash autocurl.sh host-list.txt"
echo ""

#The cat command prints the url list
#then we use -sI curl flag so we can see only the http response
#and we made an http:// to make an url
#grep works to only print the HTTP/

for host in $(cat $1); do curl -sI https://$host/ | grep -e 'HTTP/' && echo "HOST: $sub" | grep -A1 HOST; done
