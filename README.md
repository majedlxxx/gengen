current=$(pwd)
cd 
home=$(pwd)
cd $current
chmod +x fileModifier 
./fileModifier $home
chmod +x 1gengen newgen
sudo cp 1gengen /bin/gengen
sudo cp newgen /bin 
sudo cp -r genFiles $home
echo ****To remove the unnecessary files: 
echo cd ..
echo rm -r gengen
