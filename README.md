# insync_manual
instructions for synchronizing google disk with the server, with using insync tool.

curl -L -o insync-headless.deb https://cdn.insynchq.com/builds/linux/insync-headless_3.2.7.10758-buster_amd64.deb
apt-get install ./insync-headless.deb
insync-headless start
insync-headless account add
mkdir google-drive
insync-headless account add -a `Auch Code` -c gd -p ./google-drive -e MS_OFFICE
