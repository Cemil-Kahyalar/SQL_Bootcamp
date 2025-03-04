SORU 1) -- görmek istediğimiz bilgileri aralarında virgül kullanarak yazmamız lazım  
Select FirstName, LastName , Salary from Employees 
SORU 2) -- DISTINCT ile benzersiz bir sıralama yaparız  
Select Distinct Department from Employees 
SORU 3) --  Departmanı  IT olanın bilgilerini getir 
Select * from Employees where Department = ‘IT’ 
SORU 4) -- desc büyükten küçüğe asc küçükten büyüğe sıralar  
Select * from Employees Order BY Salary desc  
SORU 5) -- isim ve soyismi aralarında boşluk bırakıp birleştirdim görünen tabloya da isim ismini verdim 
Select Concat(FirstName, ' ', LastName) AS isim from Employees
