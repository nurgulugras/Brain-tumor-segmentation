# Beyin Tümörü Tespiti 
Projede görüntü işlemenin temel kavramları olan segmentasyon ve morfolojik işlemlerden oluşmaktadır. Beynin MRI tarama görüntülerinden tümör tespitini python kullanarak yapıldı. 
Algoritmanın iki aşaması vardır, birincisi verilen MRI görüntüsünün ön işlemden geçirilmesi ve bundan sonra segmentasyon ve daha sonra morfolojik işlemler yapılması. Algoritma adımları aşağıdaki gibidir: 
1. Giriş olarak beynin MRI görüntüsünü verildi. 
2. Gri tonlamalı görüntüye dönüştürüldü. 
3. Eşik segmentasyonu yapıldı. 
4. Havza segmentasyonunu uygulandı. 
5. Morfolojik işlemi yapıldı. 
6. Son olarak çıktı bir tümör bölgesi olacaktır. 

Kaynak olarak OpenCv nin kendi dokümanlarından faydalanıldı. 
https://docs.opencv.org/master/d3/db4/tutorial_py_watershed.html
