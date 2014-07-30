Installation:-
------------

How I Installed MongoDB on My  development Machine(Windows 7):-
--------------------------------------------------------------
1.Extract the mongodb-win32-x86_64-2008plus-2.6.3.zip in d:\MongoDB-2.6.3
2.Create a directory 'data' in d:\MongoDB-2.6.3
3.Create a directory 'log' in d:\MongoDB-2.6.3
4.Create a directory 'db' in D:\MongoDB-2.6.3\data
5.Create a file startmongo.conf in D:\MongoDB-2.6.3\bin
6.Open command prompt and go to d:\MongoDB-2.6.3\bin
  Run the command mongod  --dbpath d:\MongoDB-2.6.3\data (This starts mongodb server)
  if every thing is ok 
	open another command prompt and go to d:\MongoDB-2.6.3\bin
   run the command mongo.exe it should open the shell

Helpful URLs For Troubleshooting the installation:-
--------------------------------------------------
http://stackoverflow.com/questions/23726684/mongodb-on-a-windows-7-machine-no-connection-could-be-made
http://stackoverflow.com/questions/2404742/how-to-install-mongodb-on-windows



Helpful URLS for creating Github readme.md:-
-------------------------------------------
https://stackedit.io/







