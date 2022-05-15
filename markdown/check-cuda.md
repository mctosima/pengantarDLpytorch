<div align = "center">

# Mengecek GPU CUDA
[Kembali ke halaman awal](cheatsheet.md)
</div>

<br>

### **Perintah**
```python
cek_gpu = torch.cuda.is_available()
print(cek_gpu)
```
nilai return:
- `True` jika GPU ditemukan
- `False` jika tidak ditemukan

<br>

### **Pengunaan perintah**
Dapat digunakan sebagai pengkondisian untuk menentukan apakah GPU ditemukan atau tidak dan dilanjutkan dengan memuat `torch.device` ke dalam sebuah variabel
```python
if torch.cuda.is_available():
    device = torch.device("cuda")
else:
    device = torch.device("cpu")
```