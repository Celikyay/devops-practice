apt-get update 
apt-get install curl -y 
curl -sL https://deb.nodesource.com/setup_10.x | bash 
apt-get install nodejs -y 
cd opt/ 
mkdir node-app 
cd node-app/ 
echo 'console.log("nodejsapp from ubuntu...");' > index.js
cat index.js 
node index.js