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
Dengan memanfaatkan fungsi `dgeom` yang menerima parameter n dan peluang, akan didapatkan nilai peluang untuk bertemu 3 orang yang tidak menghadiri acara vaksinasi dan akan bertemu keberhasilan pertama dengan peluang 0.2.

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
# hasil : [1] 0.1054
```  
