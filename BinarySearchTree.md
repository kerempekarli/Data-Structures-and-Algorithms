# Proje 1
###   -------- ---------   [22,27,16,2,18,6] -> Insertion Sort

* Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

* Big-O gösterimini yazınız.

* Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması,
     Best case: Aradığımız sayının dizinin en başında olması.

* Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


> [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

#  CEVAPLAR 

1. Aşama => İlk olarak en küçük değeri yani 2 sayını alırız ve en başa yazarız. 22 sayısınıda 2 nın yerine yani en sona yazarız.
Elimizde [2,27,16,22,18,6] değeri olur.

2. Aşama => 2 den sonraki en küçük sayıyı bulmak için arama yaparız ve 6 sayını buluruz daha sonra 6 sayını 27 nin yerine yazar ve yerlerini değiştiririz. Elimizde [2,6,16,22,18,27] değeri oldu.

3. Aşama => [2,6,16,18,22,27] ve bitti. 


> ### Sürekli (n-1) sayıda denediğimiz için birden n'ye kadar olan sayıların toplamı kadar yani (n+(n+1))/2 => (n2+n)/2 sayıda işlem yapmış oluruz. 

# İKİNCİ SORUNUN CEVABI 

#### 1. ADIM => [2,3,5,8,7,9,4,15,6]
#### 2. ADIM => [2,3,5,8,7,9,4,15,6]
#### 3. ADIM => [2,3,4,8,7,9,5,15,6]
#### 4. ADIM => [2,3,4,5,7,9,8,15,6]
#### 5. ADIM => [2,3,4,5,7,8,9,15,6]
