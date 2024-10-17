# MC3DS-Save-Documentation
- A simple documentation for MC3DS SaveGames and Worlds.

## ExtData (Extra SaveData) Structure:
```
icon.smdh
.\boss\
.\user\
  ├── clientId.txt
  ├── options.txt
  ├── achievements.txt
  └── minecraftWorlds\
      └── base64worldId\
          ├── levelname.txt
          ├── level.dat
          ├── level.dat_old
          └── db\
              ├── savemarker
              ├── vdb\
              |    ├── newindex.vdb
              |    ├── index.vdb
              |    ├── slt1.vdb
              |    ├── slt2.vdb
              |    ├── slt3.vdb
              |    └── slt4.vdb
              └── cdb\
                   ├── newindex.cdb
                   ├── index.cdb
                   ├── slt1.cdb
                   ├── slt2.cdb
                   ├── slt3.cdb
                   └── slt4.cdb
```
## Understanding ExtData Structure:
### CDB Files:
- 
