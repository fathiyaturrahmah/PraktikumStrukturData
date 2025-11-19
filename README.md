##  QUEUE  
Queue = antrian  
Queue menggunakan metode **FIFO (First In First Out)** → yang masuk duluan, keluar duluan

## ## 1️ Membuat Queue

```python
queue = []
```
Membuat queue kosong dengan tipe list.
```
queue.append('A')
queue.append('B')
queue.append('C')
print("Queue: ", queue)
```
append() menambah elemen di belakang antrian.

Hasil output:
```
['A', 'B', 'C']
```

```
element = queue.pop(0)
print("Dequeue: ", element)
```
pop(0) menghapus elemen pertama (index 0).
Nilai yang dihapus disimpan di variabel element.

```
frontElement = queue[0]
print("Peek: ", frontElement)
```
queue[0] mengambil elemen paling depan tanpa menghapusnya.

```
isEmpty = not bool(queue)
print("isEmpty: ", isEmpty)
```
not bool(queue) → True jika queue kosong.

```
print("Size: ", len(queue))
```
len(queue) menghitung jumlah elemen dalam queue.

