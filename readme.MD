<div align="center">

# Pengantar Deep Learning Dengan PyTorch
<a href="https://www.python.org/"><img alt="Python" src="https://img.shields.io/badge/-Python 3.7+-blue?style=for-the-badge&logo=python&logoColor=white"></a>
<a href="https://pytorch.org/get-started/locally/"><img alt="PyTorch" src="https://img.shields.io/badge/-PyTorch 1.8+-ee4c2c?style=for-the-badge&logo=pytorch&logoColor=white"></a>
</div>

> **Tentang Repositori Ini:**
> Repositori ini memuat kumpulan bahan belajar tentang implementasi Deep Learning menggunakan PyTorch berbahasa Indonesia. Saran dan masukan sangat dibutuhkan bagi pengembang demi meningkatkan kualitas bahan belajar ini.

## Daftar Isi

<table class="tg">
  <tr>
    <th class="tg-yw4l"><b>No</b></th>
    <th class="tg-yw4l"><b>Topik</b></th>
    <th class="tg-yw4l"><b>Deskripsi</b></th>
    <th class="tg-yw4l"><b>Notebook</b></th>
  </tr>

  <tr>
    <td class="tg-yw4l">1</td>
    <td class="tg-yw4l">Pengantar Tensor</td>
    <td class="tg-yw4l">Memberikan gambaran singkat tentang tipe data tensor dan operasi-operasi aritmatika sederhana menggunakan PyTorch</td>
    <td class="tg-yw4l"><a href="IPYNB Code/01_tensorbasic.ipynb">Tensorbasic</a> </td>
  </tr>

<tr>
    <td class="tg-yw4l">2</td>
    <td class="tg-yw4l">Autograd</td>
    <td class="tg-yw4l">Membahas tentang proses menghitung gradien secara otomatis dengan fungsi autograd</td>
    <td class="tg-yw4l"><a href="IPYNB Code/02_Autograd.ipynb">Autograd</a> </td>
  </tr>

<tr>
    <td class="tg-yw4l">3</td>
    <td class="tg-yw4l">Forward Pass, Backpropagation, Computational Graph</td>
    <td class="tg-yw4l">Membahas tentang proses forward pass dan back-propagation serta keterkaitan antara keduanya. Pada bagian ini juga dibahas bagaimana proses computational graph.</td>
    <td class="tg-yw4l"><a href="IPYNB Code/03_Backprop.ipynb">Backprop</a>,
<a href="IPYNB Code/03b_ComputationalGraph.ipynb">CompGraph</a> </td>
  </tr>

<tr>
    <td class="tg-yw4l">4</td>
    <td class="tg-yw4l">Gradient Descent</td>
    <td class="tg-yw4l">Membahas tentang perhitungan gradient descent baik menggunakan numpy maupun dengan torch</td>
    <td class="tg-yw4l"><a href="IPYNB Code/04_graddescent.ipynb">GradDesc1</a>,
<a href="IPYNB Code/05_graddescent2.ipynb.ipynb">GradDesc2</a></td>
  </tr>

<tr>
    <td class="tg-yw4l">5</td>
    <td class="tg-yw4l">Training Pipeline</td>
    <td class="tg-yw4l">Proses melakukan training loop dengan pytroch untuk kasus sederhana</td>
    <td class="tg-yw4l"><a href="IPYNB Code/06_training_pipeline.ipynb">Training Pipeline</a></td>
  </tr>

<tr>
    <td class="tg-yw4l">6</td>
    <td class="tg-yw4l">Linear Regression</td>
    <td class="tg-yw4l">Melakukan regresi sederhana dengan deep learning, mengatur hyperparameter, dan melihat hasil prediksi</td>
    <td class="tg-yw4l"><a href="IPYNB Code/07_linearreg.ipynb">Linearreg1</a>,
    <a href="IPYNB Code/08_linearreg2.ipynb">Linearreg2</a></td>
  </tr>

<tr>
    <td class="tg-yw4l">7</td>
    <td class="tg-yw4l">Logistic Regression</td>
    <td class="tg-yw4l">Melakukan logistic regression sederhana dan melakukan transformasi data</td>
    <td class="tg-yw4l"><a href="IPYNB Code/09_logisticreg.ipynb">Logistic Reg</a>
  </tr>

<tr>
    <td class="tg-yw4l">8</td>
    <td class="tg-yw4l">Dataset & Dataloader</td>
    <td class="tg-yw4l">Mempelajari penggunaan dataloader dan proses mempersiapkan dataset pada pytorch</td>
    <td class="tg-yw4l"><a href="IPYNB Code/10_DatasetDataloader.ipynb">DataLoader</a>
  </tr>

<tr>
    <td class="tg-yw4l">9</td>
    <td class="tg-yw4l">Dataset Transform</td>
    <td class="tg-yw4l">Mentransformasikan dataset dengan bantuan fungsi transforms dari pytorch</td>
    <td class="tg-yw4l"><a href="IPYNB Code/11_DatasetTransform.ipynb">Data Transform</a>
  </tr>

<tr>
    <td class="tg-yw4l">10</td>
    <td class="tg-yw4l">Softmax Cross-Entropy</td>
    <td class="tg-yw4l">Mendemonstrasikan fungsi softmax baik dengan pytorch maupun tanpa pytorch. Menghitung loss dengan cross-entropy</td>
    <td class="tg-yw4l"><a href="IPYNB Code/12_SoftmaxAndCrossEnt.ipynb">SoftMax CrossEnt</a>
  </tr>

<tr>
    <td class="tg-yw4l">11</td>
    <td class="tg-yw4l">Activation Function</td>
    <td class="tg-yw4l">Mencoba beberapa fungsi aktivasi yang disediakan pada PyTorch serta teknik implementasinya</td>
    <td class="tg-yw4l"><a href="IPYNB Code/13_activationfunc.ipynb">Act Function</a>
  </tr>

<tr>
    <td class="tg-yw4l">12</td>
    <td class="tg-yw4l">Feed Forward Neural Network</td>
    <td class="tg-yw4l">Mencoba melakukan training dan testing menggunakan dataset tulisan tangan MNIST)</td>
    <td class="tg-yw4l"><a href="IPYNB Code/14_feedforward.ipynb">FFNN MNIST</a>
  </tr>

<tr>
    <td class="tg-yw4l">13</td>
    <td class="tg-yw4l">CNN dengan CIFAR</td>
    <td class="tg-yw4l">Mencoba melakukan training dan testing menggunakan metode konvolusi pada dataset CIFAR</td>
    <td class="tg-yw4l"><a href="IPYNB Code/15_CNNCIFAR.ipynb">CNN-CIFAR</a>
  </tr>

<tr>
  <td class="tg-yw4l">14</td>
  <td class="tg-yw4l">Menyimpan dan Memuat Model & Checkpoint </td>
  <td class="tg-yw4l">Pada tutorial ini akan dibahas secara komprehensif cara-cara untuk menyimpan dan memuat model, serta menyimpan checkpoint ketika melakukan training. Juga akan dibahas cara-cara untuk menyimpan parameter secara online menggunakan wandb.</td>
  <td class="tg-yw4l"><a href="IPYNB Code/25_checkpoint.ipynb">CNN-CIFAR</a>
  </tr>

<tr>
    <td class="tg-yw4l">15</td>
    <td class="tg-yw4l">Transfer Learning</td>
    <td class="tg-yw4l">Pada percobaan ini dilakukan proses transfer learning dari model Resnet18 untuk mengklasifikasikan citra pada dataset hymenoptera (lebah atau semut). Pada modul ini juga dipelajari tentang scheduler.</td>
    <td class="tg-yw4l"><a href="IPYNB Code/16_TransferLearning.ipynb">Transfer Learning</a>
  </tr>

<tr>
    <td class="tg-yw4l">16</td>
    <td class="tg-yw4l">Tensorboard</td>
    <td class="tg-yw4l">Pada modul kali ini, dibahas penggunaan tensorboard untuk meninjau metrik performa dari proses training, testing, serta menggunakan fitur-fitur dasar yang ada pada tensorboard..</td>
    <td class="tg-yw4l"><a href="IPYNB Code/17_tensorboard.ipynb">Tensorboard</a>
  </tr>

<tr>
  <td class="tg-yw4l">17</td>
  <td class="tg-yw4l">Weight & Bias</td>
  <td class="tg-yw4l">Mencoba untuk merekam log proses training, menyimpan dan menampilkannya di platform Weight & Bias</td>
  <td class="tg-yw4l"><a href="IPYNB Code/24_wandb.ipynb">Wandb</a>
</tr>

<tr>
  <td class="tg-yw4l">18</td>
  <td class="tg-yw4l">Sequence Model</td>
  <td class="tg-yw4l">Membahas tentang prediksi terhadap data yang masuk secara sequence dalam rentang waktu. Materi ini menjadi pengantar untuk pembahasan topik Recurssive Neural Network (RNN).</td>
  <td class="tg-yw4l"><a href="IPYNB Code/18_rnn_seq.ipynb">Sequence Model</a>
</tr>

</table>

Juga terdapat kumpulan tulisan cheatsheet (contekan) terkait pytorch yang dapat anda baca pada [tautan berikut ini](/markdown/cheatsheet.md)

## Instalasi dan Prasyarat

Untuk menjalankan skrip pada jupyter notebook yang ada dalam folder [IPYNB Code](IPYNB%20Code/), anda memerlukan instalasi framework PyTorch beserta paket dependensi lainnya. Anda juga disarankan membuat *environment* baru dengan menggunakan `conda`. Petunjuk instalasi conda tidak dijelaskan disini, anda dapat mengikuti petunjuk pada laman [dokumentasi Anaconda](https://docs.anaconda.com/anaconda/install/index.html).

```bash
# clone repositori
git clone https://github.com/mctosima/pengantarDLpytorch.git
cd pengantarDLpytorch

# buat environment baru
conda create -n ptorch python=3.9
conda activate ptorch

# install pytorch (CPU only) untuk arsitektur x86_64
conda install pytorch torchvision torchaudio cpuonly -c pytorch

# install paket dependensi esensial lainnya
conda install --file requirements.txt
```

Jika anda ingin menggunakan GPU NVIDIA dalam proses komputasi (pada beberapa notebook), anda dapat mengikuti perintah berikut untuk instalasi PyTorch berserta paket dependensi lainnya. Perhatikan bahwa GPU NVIDA anda (beserta driver) juga harus mendukung CUDA toolkit 11.3.

```bash
# install pytorch (+GPU) untuk arsitektur x86_64
conda install pytorch torchvision torchaudio cudatoolkit=11.3 -c pytorch
```

Lebih lengkap terkait instalasi framework PyTorch pada mesin lokal anda, kunjungi halaman utama [instalasi PyTorch](https://pytorch.org/get-started/locally/).

## Saran dan Pengembangan

Materi yang ada pada repositori ini bersifat gratis dan akan selalu tersedia secara gratis. Kami berterima kasih apabila ada pihak-pihak yang ingin membantu dan mengoreksi konten dari repositori ini. Silahkan tambahkan [issue baru](https://github.com/mctosima/pengantarDLpytorch/issues) agar kami dapat melacak kesalahan maupun saran perbaikan yang ada

Kami menyadari bahwa konten ini tidak sepenuhnya bersumber dari diri kami sendiri. Atribusi dan pencantuman sumber sebisa mungkin dilakukan untuk memberikan kredit kepada pembuat. Apabila anda sebagai pembuat materi / asset yang digunakan pada repositori ini merasa keberatan, kami dengan senang hati akan memperbaiki dan menghapus materi / asset anda dari repositori ini.

## Lisensi dan Atribusi

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Seluruh kode dan materi yang ada di dalam repositori ini menggunakan lisensi MIT. Anda dapat dengan bebas melakukan:

- Menggunakannya untuk keperluan komersial
- Memodifikasi dan menggunakannya untuk keperluan pribadi
- dan Mendistribusikannya untuk kepentingan luas

Apabila anda menggunakan kode dan materi yang ada di dalam repositori ini untuk keperluan komersial, riset, dan pendidikan, mohon cantumkan atribusi terhadap pemilik repositori:

```angular2html
@misc{mctiww2022,
  title={Pengantar Deep Learning Dengan Pytorch},
  author={Manullang, Martin Clinton Tosima and Wisesa, I Wayan Wiprayoga},
  journal={https://github.com/mctosima/pengantarDLpytorch},
  year={2022}
}
```

## Referensi

- Krizhevsky, A. (n.d.). Learning Multiple Layers of Features from Tiny Images. <https://www.cs.toronto.edu/~kriz/learning-features-2009-TR.pdf>
- MNIST handwritten digit database, Yann LeCun, Corinna Cortes and Chris Burges. (n.d.). Retrieved April 13, 2022, from <http://yann.lecun.com/exdb/mnist/>
- PyTorch documentation — PyTorch 1.11.0 documentation. (n.d.). Retrieved April 13, 2022, from <https://pytorch.org/docs/stable/index.html>
- Activation functions in Neural Networks. (2018, January 29). GeeksforGeeks. <https://www.geeksforgeeks.org/activation-functions-neural-networks/>
- Engineer, P. (2021, February 24). Deep Learning With PyTorch - Full Course. Youtube. <https://www.youtube.com/watch?v=c36lUUr864M>
- Engineer), P. L. (python. (n.d.). pytorchTutorial: PyTorch Tutorials from my YouTube channel. Github. Retrieved April 13, 2022, from <https://github.com/python-engineer/pytorchTutorial>
- PyTorch Tutorial. (n.d.). Retrieved April 13, 2022, from <https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html>
- Dive into Deep Learning, Zhang, Aston and Lipton, Zachary C. and Li, Mu and Smola, Alexander J., from<http://d2l.ai/>
