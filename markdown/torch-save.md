<div align = "center">

# `torch.save`
[Kembali ke halaman awal](cheatsheet.md)
</div>

<br>

### **Contoh Penggunaan**
```python
x = torch.tensor([0,1,2,3,4])
torch.save(x, '/lokasipenyimpanan/tensor.pt')
```

# Saving Model
Ada dua jenis cara menyimpan model:
- Menggunakan `model.state_dict()`
- Menggunakan model secara keseluruhan

<br>

## **Menggunakan `model.state_dict()`**
```python
torch.save(model.state_dict(), '/lokasipenyimpanan/model.pt')
```
Jika menggunakan ini, maka model yang disimpan hanya berisi `model.state_dict()` atau informasi-informasi dari isi sebuah model

dan untuk memuatnya:
```python
model = KelasModel(*args, **kwargs)
model.loda_state_dict(torch.load('/lokasipenyimpanan/model.pt'))
```


<br>

## **Menggunakan model secara keseluruhan**
```python
torch.save(model, '/lokasipenyimpanan/model.pt')
```
Jika menggunakan cara ini, maka model yang disimpan berisi seluruh informasi dari model yang dikirimkan.

dan untuk memuatnya:
```python
model = torch.load('/lokasipenyimpanan/model.pt')
```

> Ekstensi yang disarankan oleh pytorch adalah `.pt` atau `.pth`


---
Referensi:
- https://pytorch.org/docs/stable/generated/torch.save.html