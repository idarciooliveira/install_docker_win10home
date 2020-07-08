**_ Guide to install docker in windows 10 Home _**

- Install Hyper-V and Containers :

  1. execute installHyperV.bat as adminstrator
  2. execute installContainers.bat as administrator
  3. restart your computer

- Edit Windows Version in Registry

  1. Press Windows + R and write regedit
  2. In the Registry Editor, go to \HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion
  3. Right-click on EditionID and Click Modify
  4. Change Value Data to Professional
  5. Press OK.

- Install Docker
  ⚠️ If you restart your computer the EditionID will be reset and you have to set it again.
  Great Job! ⭐️ Now, run the Docker installer again. It should proceed without any problems. After the installation, you can change the EditionID back to Core
  That’s it! I hope you got everything working and are up and running with docker!
  All Credit to hessi9 and mapk from the Docker forum for figuring out this solution. ⭐️

original post
https://itnext.io/install-docker-on-windows-10-home-d8e621997c1d
