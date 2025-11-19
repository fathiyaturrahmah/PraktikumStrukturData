QUEUE
Queue = antrian
Queue menggunakan metode  fifo atau first in first out yaitu yang masuk  duluan dia yang keluar terlebih dahulu.

queue = []
code diatas artinya membuat queue (antrian) kosong dengan tipe list.

ENQUEUE yaitu menambah elemen atau data batu di belakang antrian.
queue.append('A') menambah elemen A di belakang queue
queue.append('B') menambah elemen B
queue.append('C') menambah elemen C
print("Queue: ", queue) menampilkan isi queue saat iniSS
maka hasil yang akan keluar adalah [‘A’, ‘B’, ‘C’]

DEQUEUE yaitu menghapus elemen atau data di bagian depan antrian.
element = queue.pop(0) menghapus elemen pertama yaitu 0 
print("Debueue: ", element) akan menampilkan elemen yang dikeluarkan tadi

PEEK yaitu memunculkan elemen atau data tapi tidak menghilangkan data tersebut
frontElement = queue[0] mengembil elemen pertama, disimpan di fronElement
print("peek: ", frontElement) menampilkan isi variable frontElement

ISEMPTY yaitu untuk melihat apakah  element kosong atau tidak
isEmpty = not bool(queue) jika true bila queue kosong
print("isEmpty: ", isEmpty) akan tersimpan di isEmpty

SIZE yaitu menghitung jumlah elemen
print("size: ", len(queue)) yg dimana menghitung jumlah elemen dalam queue


STACK
stack = []
code diatas artinya membuat stack kosong.

PUSH yaitu menambahkan data ke paling  atas
stack.append('A')
stack.append('B')
stack.append('C')
print("stack: ", stack)
append yg dimn menambah elememn ke ats tumpukan.
Jadi urutan terakhirnya : [ 'A', 'B', 'C' ]

POP yaitu menghapus data ppaling ats
element = stack.pop()
print("pop: ", element)
stack.pop() → menghapus elemen terakhir (paling atas).
Disimpan di variabel element.
Misalnya, jika stack = ['A', 'B', 'C'], 
yang keluar → 'C'

PEEK yaitu meliht ats tumoukan tanpa menghapus
topElement = stack[-1]
print("peek: ", topElement)
stack[-1] mengambil elemen paling atas (index terakhir), tapi tidak menghapusnya.
ISEMPTY yaitu megecek apakah stack kkosong  atua tidak.
isEmpty = not bool(stack) true jika kosong
print("isEmpty: ", isEmpty)

SIZE yaitu jumlah elemen.
print("size: ", len(stack)) menghitung jumlah elemen
