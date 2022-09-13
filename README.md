# sulipySQL_3

1. Feladat
Írj SQL utasítást amely az online tesztadatbázis 'Categories' táblájában

a, beszúr egy rekordot, amelyben CategoryName és a Description értékek is meg vannak adva (CaregoryID automatikusan jön létre),

  INSERT INTO Categories (CategoryName, Description)
  VALUES ('Sushi', 'Finom');
  
b, beszúr egy rekordot, amelbyen csak a CategoryName értéke van megadva (CaregoryID automatikusan jön létre),

  INSERT INTO Categories (CategoryName)
  VALUES ('Pizza');
  
c, lekérdezi azokat a rekordokat (az összes adatával), ahol a Description értéke NULL!

  SELECT CategoryID, CategoryName, Description FROM Categories WHERE Address is NULL;
