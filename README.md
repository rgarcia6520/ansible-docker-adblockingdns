# ansible-docker-adblockingdns
ansible script to install oznu/ad-blocking-dns docker container from a new linux image at ip 192.168.1.10
Run: 

echo "192.168.1.10" >> /path/to/hosts && ansible-playbook -i /path/to/hosts /path/to/site.yml

or put in it's own roles/adblocking-docker-dns/ folder.
