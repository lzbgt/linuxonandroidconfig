apt-get update;apt-get upgrade -y;apt-get install -y git-core nodejs npm curl
ln -s /usr/bin/nodejs /usr/bin/node
sed 's/SELINUX=.*/SELINUX=disabled/'/etc/selinux/config
npm i -g npm@latest
npm i -g coffee-script sails
