# SoraDataEx
**SoraDataEx.ini** for the voice patch project [SoraVoice](https://github.com/ZhenjianYang/SoraVoice), which can add support for *Trails in the Sky* series published by Xseed.     

The latest file is [SoraVoiceEx.ini](https://github.com/ZhenjianYang/SoraDataEx/blob/master/SoraDataEx/SoraDataEx.ini).

## Usage
Copy **SoraDataEx.ini** to `<Game Root>/voice/`.   

## By now, supported games
|Game Title                 |Publisher|Platform        |DX|Timestamp|CRC32 of EXE
|---------------------------|---------|----------------|--|---------|--------
|*Trails in the Sky FC*     |Xseed    |Steam           |8 |20170505 |C5E5289E
|*Trails in the Sky FC*     |Xseed    |Steam/GOG/Humble|8 |20170819 |3BF28D8E
|                           |         |                |  |20170828 |3DA246CF
|                           |         |                |9 |20170819 |D5DBCCBC
|                           |         |                |  |20170828 |65CF4451

**NOTE**: Voice scripts for these games are still needed.   

### About the Timestamp   
The timestamp is the timestamp storded in the exe file's PE header.   
There are many tools can check it.    
**e.g.** Drag **ed6_win.exe** to [EXE Explorer](http://www.mitec.cz/exe.html),
then the timestamp can be found at **Header** -> **File** -> **Timestamp**.   


