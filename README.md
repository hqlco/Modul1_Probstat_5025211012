### Praktikum 1 [ Probabilitas & Statistika ]
| Nama                      | NRP           |
|---------------------------|---------------|
|Moh rosy haqqy aminy       |5025211012     |

### Soal 1A 
```R
# 1.A
x <- 3
p <- 0.2
dgeom(x, p)
# hasil : [1] 0.1024
``` 
**Penjelasan**   
Fungsi `dgeom` adalah fungsi yang menerima parameter n dan peluang, akan didapatkan nilai peluang untuk bertemu 3 orang yang tidak menghadiri acara vaksinasi dan akan bertemu keberhasilan pertama dengan peluang 0.2.

**Screenshot**  
![1A](https://user-images.githubusercontent.com/86828535/194808121-cb3a300d-fade-4f07-b4b8-d41894a27280.png)

### Soal 1B  
**Kode Program**  
```R
# 1.B
data <- 10000
p <- 0.2
x <- 3
mean((rgeom(data, p) == x))
# hasil : [1] 0.10014
```  
**Penjelasan**  
fungsi `rgeom` adalah fungsi yang berguna untuk mendapatkan distribusi geometrik dengan variabel acak. Dalam hal ini, variabel acak sejumlah 10000 data dan peluangnya sebesar 0.2.

**Screenshot**  
![Screenshot 2022-10-10 133650](https://user-images.githubusercontent.com/86828535/194808832-ece82eb9-a52d-438f-8aa0-a8caaf046435.png)

### Soal 1C  
**Penjelasan**  
Pada poin a nilainya statis/tetap. sedangkan Pada poin b nilainya dinamis, tetapi mendekati nilai A. Sehingga dapat ditarik kesimpulan bahwa b menggunakan fungsi random, maka tentu hasilnya berbeda beda tetapi nilai poin b selalu mendekati poin a

### Soal 1D
**Kode Program**  
```R
# 1.D
data <- 10000
p <- 0.2
hist(rgeom(data, p), main = "Distribusi Geometrik Peluang X = 3 gagal sebelum sukses pertama")
```  

**Screenshot**  
![asnjdjdjej](https://user-images.githubusercontent.com/86828535/194809368-c2f98777-32bf-4505-a27a-2033482e1bd7.png)

### Soal 1E
**Kode Program**  
```R
# 1.E
p <- 0.2
q <- 1 - p
mean <- 1 / p
variance <- (q / (p^2))
mean
variance
# hasil : [1] 5
# hasil : [1] 20
```  

**Penjelasan**  
rumus `mean = 1/P` dan rumus `varians = Q/P^2`.

**Screenshot**
![Screenshot 2022-10-10 134607](https://user-images.githubusercontent.com/86828535/194809770-baea7419-8ff7-4519-a2a4-ed1c618dde18.png)














































































