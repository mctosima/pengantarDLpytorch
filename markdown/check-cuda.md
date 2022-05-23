<div align = "center">

# Mengecek GPU dengan dukungan CUDA
[Kembali ke halaman awal](cheatsheet.md)
</div>

<br>

### **Perintah**
```python
cek_gpu = torch.cuda.is_available()
print(cek_gpu)
```
nilai return:
- `True` jika framework mendukung komputasi dengan GPU NVIDIA
- `False` jika framework tidak mendukung komputasi dengan GPU NVIDIA

<br>

### **Pengunaan perintah**
Dapat digunakan sebagai pengkondisian untuk menentukan apakah GPU ditemukan atau tidak dan dilanjutkan dengan memuat `torch.device` ke dalam sebuah variabel
```python
if torch.cuda.is_available():
    device = torch.device("cuda")
else:
    device = torch.device("cpu")
```

atau dapat disingkat dengan menggunakan [ternary operator](https://docs.python.org/3.8/reference/expressions.html?highlight=ternary#conditional-expressions)

```python
device = "cuda" if torch.cuda.is_available else "cpu"
```
