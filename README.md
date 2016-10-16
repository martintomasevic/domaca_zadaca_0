# JMBAG
0036465350
#Pitanje 1
Primjećujem dodatne datoteke ClassLibrary1.dll i ClassLibrary1.pdb. Ako maknem ClassLibrary1.dll javlja mi Exception System.IO.FileNotFound jer KonzolnaAplikacija.exe u izvođenju ovisi o ClassLibrary1.dll zbog linije MyConsole.PrintHelloWorld();. Da bi se aplikacija uspješno izvela, poslati ću datoteke KonzolnaAplikacija.exe i ClassLibrary1.dll
#Pitanje 2
Aplikacija je koristila staru verziju class library assemblija jer joj je on jedini bio "vidljiv" iz njezinog okruženja (pošto novi .dll file još nije bio generiran).
#Pitanje 3
Pero: Hello World
#Pitanje 4
Dodana je datoteka PeroClassLibrary.dll
#Pitanje 5
Aplikacija radi jer KonzolnaAplikacija.exe i dalje ima gdje dohvatitiu PeroClassLibrary.dll, a build je i dalje moguć jer traži PeroClassLibrary.dll u istom direktoriju gdje se nalazi KonzolnaAplikacija.exe i ostale datoteke koje je generirao.
#Pitanje 6
Build je uspio. NodaTime se ponovno pojavio u packages direktoriju.
