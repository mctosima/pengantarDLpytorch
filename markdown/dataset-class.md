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
- `__len__`: mengembalikan jumlah sampel dalam dataset
- `__getitem__`: mengambil sampel sesuai urutan indeks-nya
- `__init__`: konstruktor dataset, dalam implementasinya berisi rutinitas mengumpulkan daftar sampel dalam dataset

### **Cara Penggunaan**

```python
class CustomImageDataset(Dataset):
    def __init__(self):
        # inisialisasi lokasi direktori dataset
        self.data_dir = ..
        # mengumpulkan daftar sampel dataset
        self.img_data = ...
        self.img_labels = ...

    def __len__(self):
        return len(self.img_labels)

    def __getitem__(self, idx):
        image = img_data[idx]
        label = label[idx]
        
        return image, label
```

---
Referensi:
- https://pytorch.org/tutorials/beginner/basics/data_tutorial.html