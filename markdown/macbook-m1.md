<div align = "center">

# M1 GPU Support
[Kembali ke halaman awal](cheatsheet.md)
</div>

<br>

> Kode yang dapat anda gunakan untuk melakukan _benchmark_ dapat dilihat [di sini](../IPYNB%20Code/23_testingm1.ipynb)

Markdown ini terakhir diperbaharui tanggal : 18/05/2020

---
Beberapa hari sebelum tulisan ini ditulis, PyTorch mengumumkan bahwa telah mendukung akselerasi training dan testing dengan menggunakan GPU yang terdapat pada Macbook Pro M1 (apple silicon). Cuitannya dapat anda baca [di sini](https://twitter.com/PyTorch/status/1526944876478144512?s=20&t=i_rsP_VDtJS-z258sl5IGA).

Beberapa hal penting terkait penggunaan GPU pada Macbook Pro M1:

<br>

**Mengecek ketersediaan GPU**
```python
print(torch.backends.mps.is_available())
```

Kode diatas akan mengecek ketersediaan GPU M1 yang diberi kode `mps`.

<br>

**Menggunakan GPU**
```python
device = torch.device("mps")

# contoh penggunaan
model = model.to(device)
```
---
Hasil benchmark saya dapat dilihat pada tautan wandb [berikut ini](https://wandb.ai/mctosima/vggcifarm1?workspace=).
