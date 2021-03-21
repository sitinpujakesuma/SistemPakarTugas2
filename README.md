# SistemPakarTugas2
Class Graph mendefenisikan grafik menggunakan representasi daftar kedeketan. 
variabel self.graph digunakan untuk menyimpan grafik 
fungsi addEdge untuk menambahkan tepi pada grafik 
fungsi BFS untuk mencetak BFS grafik 
variable visited untuk menandai node yang belum pernah di cek 
variable queue.append digunakan untuk menandai node yang telah di cek
variable s digunakan untuk mengeluarkan node dari antrian
```
g = Graph()
g.addEdge(0, 1)
g.addEdge(0, 2)
g.addEdge(1, 2)
g.addEdge(2, 0)
g.addEdge(2, 3)
g.addEdge(3, 3)
```
merupakan driver code untuk grafik yang diberikan pada diagram 
