1.


mkdir temp
cd temp
mkdir dom
mkdir nauka	
cd nauka
mkdir c
mkdir logo
mkdir pascal
cd 
mkdir praca
mkdir zlecenia
cd zlecenia
mkdir niezrealizowane
mkdir zrealizowane

2.


cd
cd temp/dom
mkdir wazne-sprawy
cd wazne-sprawy
3.


touch rachunki.txt
4.


cp rachunki.txt/ ~/temp/praca/zlecenia/zrealizowane/rachunki.txt
cd rachunki.txt/ ~/temp/praca/zlecenia/zrealizowane
5.


mv rachunki.txt wykonano.txt
6.


cd temp/praca/zlecenia/zrealizowane
cat >wykonano.txt
12345678901
split -b 5 wykonano.txt
7.


cd temp/nauka/logo
cp ~/temp/praca/zlecenia/zrealizowane/xa* ~/temp/praca/dokumenty
8.


cd temp/praca/dokumenty
cat xaa xab xac >odtworzono.txt
cp odtworzono.txt ../../dom/wazne-sprawy
9.


cd temp/dom/wazne-sprawy
diff odtworzono.txt -s ../../praca/zlecenia/zrealizowane/wykonano.txt
10. 


cal 10 2009
cal 10 2009 -3
cal 11 2009 -3
11.


date -d 1975-05-25 +%a





