# Steam-Android-Termux
You can download your steam games directly from your steam library with this!!! best used with winlator or other windows emulators




FIRST STEP

curl -LO "https://raw.githubusercontent.com/TheKingFireS/TermuxDepotDownloader/main/installproot.sh"
chmod +x installproot.sh
./installproot.sh


SECOND STEP

proot-distro login debian


THIRD STEP

curl -LO "https://raw.githubusercontent.com/TheKingFireS/TermuxDepotDownloader/main/installdepotdownloader.sh"
chmod +x installdepotdownloader.sh
. ./installdepotdownloader.sh

4TH STEP

cd depotdownloader


5th Step Change username to your steam username  and Password to your account password |
                                                   v
   
./DepotDownloader -username YourUsername -password YourPassword -remember-password -app 1099170 -depot 1099171 -dir GameSteamer -validate


After u exit and come back
proot-distro login debian

cd depotdownloader

./DepotDownloader -username YourUsername -password YourPassword -app 2360260 -depot 2360261 -dir GameSteamer -validate
