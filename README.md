# DataBase
DataBase.h - header file with core of DB.(It's not a header file for DataBase.cpp!!!)

DataBase.cpp - server for DB, uses new threads for every new user

# ToDo
Improve data base's server

# Args
  666 - default port

  -p <port> - specify port for db server(always must be first argument)
  
  If you want to load dbs from dumps just write:
  
  DataBase.exe "path_to_dump\DataBase.data" or
  
  DataBase.exe DataBase.data if DataBase.data in the same folder with DataBase.exe
  
  Ex:
  
  DataBase.exe -p 6969 "path_to_dump\DataBase.data" MyNewSuperDB.data
  
  DataBase.exe MyNewSuperDB.data
  
Now it's only for Windows.
