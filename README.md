Mapping EERD 1 
==============
Album(ID,Data,Tide,Musician Id
Musician(Id,Name,Phone,Stret,City,Song Tile
Instrument(Name,Key,Musician Id
Song(Tile,Author,AlbumId

======================================

Mapping EERD 2
==============
Employee(ID,Name,Sales Office Num
Sales Office(Num,.Loc,Employee Id
Prperty(Id,Add,City,State,Zip
Owner(Id,Name,Prperty Id

======================================

Mapping EERD 3
==============
Consultant(Id,Name)
Patient(Id,Name,BOD,Consultant Id,Ward Id)
Ward(ID,Name)
Nurse(Id,Name,Ward Id)
Drug(Code,Rec Dosage)
Drug Brande(Code,Brand)
Examiens(Consultant Id,Patient Id)
Gives(Drug Id,Nurse Id,Patient Id,Data,Time,Dosage0
