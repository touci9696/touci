# touci
#!/data/data/com.termux/files/usr/bin/bash
#Downloading the req dependencies to run a script without error
#################################
#    Project : T-all tool's   #
#       author : touci        #
#################################
clear

#updating terminal
echo 
echo -e "\e[32m[\e[34m*\e[32m]\e[36m Installing T-all tool's \e[m "
echo
apt-get update -yq --silent
apt-get upgrade -y
apt-get install python -y
apt-get install ruby -y
pip install install lolcat
gem install lolcat 
pkg install ncurses-utils -y

cp -R m-pkg /data/data/com.termux/files/usr/bin
echo

echo -en "\e[92m Do you wish listen  to soufiane stories (القصة 53 عصابة الهاكر الصغير) (y/n)? \e[m "
read answer
   if [ "$answer" != "${answer#[Yy]}" ] ;then
        am start -a android.intent.action.VIEW -d https://youtu.be/loahQznL8MQ >> /dev/null 2>&1
  else
	echo
   fi

echo 
echo -e "\e[33m Run \e[32m m-pkg \e[33m From anywhere to install T-all tool's  \e[m "
echo
cd $HOME
rm -rf T-all tool's
echo
cd $HOME
exec bash
