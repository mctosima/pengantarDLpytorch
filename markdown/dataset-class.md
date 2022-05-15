<div align = "center">

# Custom Dataset Class
[Kembali ke halaman awal](cheatsheet.md)
</div>

<br>

### **Import**
```python
from torch.utils.data import Dataset
```

### **Tiga Fungsi Basic**
Ada tiga fungsi yang harus disertakan pada kelas dataset di pytorch:
- `__len__`: menghitung jumlah data yang ada
- `__getitem__`: mengambil data yang diinginkan
- `__init__`: inisialisasi data

### **Cara Penggunaan**

```python
class CustomImageDataset(Dataset):
    def __init__(self):
        pass

    def __len__(self):
        return len(self.img_labels)

    def __getitem__(self, idx):
        return image, label
```

---
Referensi:
- https://pytorch.org/tutorials/beginner/basics/data_tutorial.html