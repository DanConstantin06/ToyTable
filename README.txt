--Constantin Dan Alexandru--

Aplicatie dezvoltata in Xamarin Forms.
Din lipsa timpului nu am implementat MVVM dar cu mici schimbari la aplicatie se poate rezolva acest pattern.

Paginile de interes sunt:
	- ToyRobotPage.xaml  unde se regaseste designul
	- ToyRobotPage.xaml.cs  unde avem functionalitatile

Avem un grid de 5x5 cu originea in coltul din stanga jos si un "robotel" care se plimba pe mapa dupa comenzile primite.
-Butonul PLACE arunca popup uri pentru introducerea coordonatelor initiale si a directiei robotelului;
-Butonul MOVE deplaseaza robotelul in directia lui
-LEFT si RIGHT rasuceste la stanga/dreapta cu 90 grade directia robotului
-REPORT afiseaza coordonatele si orientarea robotului

La comanda PLACE sunt verificate datele introduse si se arunca o alerta daca acestea nu sunt conforme.
La comanda MOVE se verifica inainte daca robotul nu va iesi din aria de deplasare si va arunca un mesaj de alerta.