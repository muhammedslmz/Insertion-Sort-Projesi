# Insertion-Sort-Projesi
---
Patika Proje Çalışmam 
**1)** [22,27,16,2,18,6] -> [2,27,16,22,18,6] -> [2,6,16,22,18,27] -> **[2,6,16,18,22,27]**

**2)** Big O gösteriminde ise ilk önce n tane işlem yaparak en küçük sayıyı başa yazarız. Ardından (n-1) tane işlem yaparak 2. en küçük eleman bulunur ve bu böyle devam eder. Yapılan toplam işlem sayısı: n+(n-1)+(n-2)+(n-3)....+1= (n.(n-1))/2 = (n^2-n)/2
   *Böylece Big O notation değerimiz:* **O(n^2)** ile O(6^2)= **36**

**3)** Time Complexity: Average Case: Aradığımız sayının ortada olması, Worst Case: Aradığımız sayının sonda olması, Best Case: Aradığımız sayının dizinin en başında olması.  
*Average Case:* **16,18**
*Worst Case:* **27**
*Best Case:* **2**

**4)** Dizi sıralandıktan sonra **18** sayısı **Average Case** kapsamına girer.

---
* "[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız."
[2,3,5,8,7,9,4,15,6] **->** [2,3,5,8,7,9,4,15,6] **->** [2,3,4,8,7,9,5,15,6] **->** [2,3,4,5,7,9,8,15,6]
   
