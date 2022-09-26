
# Control Flow
# Kondisional

Percabangan digunakan untuk membaut sebuah kode yang cara berjalannya kode ditentukan oleh pengetesan pernyataan besyarat.
Sama seperti fungsi pengecekan pada Boolean, pada percabangan ini dilakukan dengan memanfaatkan operator pembanding.

Pentingnya untuk memperhatikan indentasi pada implementasi percabangan. Python memiliki 
tipe data Boolean yang hanya memiliki 2 nilai, yaitu **True** atau **False**.

## Comparison Operation



| Operation | Description |
| :-------- | :-------    | 
| `a == b`      | `a equal to b`    |
| `a < b` | `a less than b` |
| `a <= b` | `a less than or equal to b` |
| `a != b` | `a not equal to b` |
| `a > b` | `a greater than b` |
| `a >= b` | `a greater than or equal to b` |

### IF
**IF** digunakan jika kita hanya ingin menguji satu pernyataan sebagai syarat jika kode kita ingin dijalankan.
Persamaan umum dari pernyataan **if** adalah :

**if "pernyataan uji" :   
kode kita**

Pada saat pernyataan uji bernilai "True" atau syaratnya terpenuhi maka kode kita yang berada di dalam fungsi/pernyataan
if akan dijalankan. Pada saat tidak terpenuhi maka tidak akan terjadi apa-apa.

**nilai = 9    
if nilai >= 8:    
print('lulus')**

**hasil**  
lulus 

Peryataan lulus ditampilkan karena variabel nilai memeuhi syarat, yaitu berada di atas atau sama dengan nilai 8.


### IF - ELSE 
Pernyataan if-else digunakan jika kita hanya mempunyai dua kondisi yang ingin dilakukan.
Kondisi True dan jika False. 
Persamaan umum dari pernyataan if-else adalah :   

**if 'pernyataan uji':   
kode bila true    
else:   
kode bila false**

Pada saat pernyataan uji bernilai "True" atau syaratnya terpenuhi maka kode kita yang berada di dalam fungsi/pernyataan 
if akan dijalankan. Pada saat syaratnya tidak terpenuhi maka kode yang berada di dalam pernyataan else kita yang akan dijalankan.

**nilai = 6  
if nilai >= 8:  
print('lulus')  
else:  
print('tidak lulus')**

**hasil**  
tidak lulus

Pada pernyataan di atas karena syarat tidak terpenuhi atau pernyataan uji bernilai "False"
maka kode di dalam pernyataan else langsung dijalankan tanpa syarat lagi.

### Pernyataan IF - ELIF - ELSE 
Pernyataan if-elif-else digunakan jika kita hanya memiliki banyak syarat yang ingin diuji secara berurutan.
Jadi jika syarat pertama tidak terpenuhi dia akan menguji syarat kedua, dan begitu seterusnya hingga bertemu dengan else.
Persamaan umum dari pernyataan if-elif-else adalah :

**if 'pernyataan uji 1':   
kode bila uji 1 true   
elif 'pernyataan uji 2':   
kode bila uji 2 true   
else:   
kode bila false**

Pada saat pernyataan uji1 bernilai "True" atau syaratnya terpenuhi maka kode kita yang berada di dalam fungsi/pernyataan if akan dijalankan.
Jika ternyata bernilai "False" atau syarat tidak terpenuhi maka sebelum dilempar ke dalam peryataan else akan di uji dulu ke dalam pernyataan elif.
Bila bernilai "True" maka kode di dalam pernyataan elif yang akan dilakukan. 

Pada saat syaratnya tidak terpenuhi maka kode yang berada di dalam pernyataan else yang akan dijalankan.

**usia = 17   
if usia < 14:   
print('anak-anak')   
elif nilai < 20:   
print('remaja')   
else:   
print('dewasa')**   

**hasil**   
remaja 

Pada contoh di atas dilakukan pengujian pada pernyataan pertama. Karena bernilai salah pengujian dilanjutkan pada pernyataan kedua. Karena 
pada pernyataan kedua bernilai benar maka kode yang berada pada pernyataan kedua langsung dijalankan. 

## Referensi 

- [Python Percabangan](https://www.petanikode.com/python-percabangan/)
