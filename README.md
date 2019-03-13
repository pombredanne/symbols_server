# symbols_server
Provide http server for symbols (PDBs) and a way to manage them

Currently, it is making available symbols through _symbols_ folder.
We can add new symbols using _/cgi-bin/add.py_. There is an example how to use it in _index.html_.

The server is doing an itegration test at startup.

## To do:
- remove symbols
- list symbols (but already accessible through _/symbols/00Admin/server.txt_, symstore format)

## Microsoft documentation around symtore tool

[SymStore Command-Line Options](https://msdn.microsoft.com/fr-fr/library/windows/desktop/ms681378(v=vs.85).aspx) - Full command line documentation

[Using SymStore](https://msdn.microsoft.com/en-us/library/windows/desktop/ms681417(v=vs.85).aspx) - Examples and other information about the usage of Symstore.exe

[Windows SDK for Windows 8.1](https://developer.microsoft.com/en-us/windows/downloads/windows-8-1-sdk) - Page to download the SDK