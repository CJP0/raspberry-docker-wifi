# raspberry-docker-wifi
create image:
sudo docker build -t hostapd:0.1 ./hostapd/
sudo docker build -t dnsmasq:0.1 ./dns/
run:
sudo docker-compose run -d
