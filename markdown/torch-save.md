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
Pytorch menyarankan untuk menyimpan `state_dict()` model karena alasan [kompatibilitas](https://pytorch.org/docs/stable/notes/serialization.html#saving-and-loading-torch-nn-modules)

```python
torch.save(model.state_dict(), '/lokasipenyimpanan/model.pt')
```
Jika menggunakan metode ini, maka model yang disimpan hanya berisi `model.state_dict()` atau informasi-informasi penting sebuah model seperti parameter-parameter dan *persistent buffer* seperti pada [modul `BatchNorm`](https://pytorch.org/docs/stable/generated/torch.nn.Module.html#torch.nn.Module.register_buffer)

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