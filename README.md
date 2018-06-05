# Clone-user-ubuntu
sudo bash
cd /home/bob
tar cf - . | (cd ../pete;tar xf -)
chown -R pete:pete /home/pete
exit
