# Apche_Scripts
echo "installing apache server"
sudo yum -y install httpd

echo "enabling apache server"
sudo systemctl enable httpd.service

echo "starting apache server"
sudo systemctl start httpd.service
