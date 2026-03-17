# 🧠 Derin Öğrenme

**Yapay Zeka Mühendisliği** | Haydar Kılıç

---

## 📚 İçerik

| # | Notebook | Konular |
|---|----------|---------|
| 01 | `Ders1_Giris_Gozetimli_Ogrenme.ipynb` | Öğrenme paradigmaları, gözetimli/gözetimsiz/pekiştirmeli öğrenme, lineer regresyon, gradient descent |
| 02 | `Ders2_Sig_ve_Derin_Aglar.ipynb` | Aktivasyon fonksiyonları (ReLU, sigmoid, tanh), sığ ağ, evrensel yaklaşım teoremi, derin ağ mimarisi |
| 03 | `Ders3_Kayip_Fonksiyonlari.ipynb` | Maksimum olabilirlik (MLE), MSE, MAE, Huber, Binary Cross-Entropy, Softmax + Cross-Entropy |
| 04 | `Ders4_Egitim_Geriye_Yayilim.ipynb` | Geri yayılım (backpropagation), zincir kuralı, SGD, Adam, momentum |
| 05 | `Ders5_Performans_ve_Regularizasyon.ipynb` | Bias-variance dengesi, dropout, L1/L2 düzenlileştirme, erken durdurma, batch normalization |
| 06 | `Ders6_CNN_ResNet.ipynb` | 1D/2D evrişim, padding, stride, max/avg pooling, LeNet mimarisi, residual bağlantılar (ResNet) |
| 07 | `Ders7_Transformers.ipynb` | Dikkat mekanizması (attention), çok başlı dikkat (multi-head), positional encoding, Transformer mimarisi |
| 08 | `Ders8_UretkenModeller_GAN_VAE_Diffusion.ipynb` | Üretici model türleri, GAN, Variational Autoencoder (VAE), Diffusion modelleri |
| 09 | `Ders9_PekistirmeliOgrenme.ipynb` | Markov karar süreci, Q-learning, politika gradyanı, DQN |
| 10 | `Ders10_NedenDerinOgrenme.ipynb` | Derin öğrenmenin avantajları, temsil öğrenimi, hiyerarşik özellikler, ölçekleme yasaları |
| 11 | `Ders11_GNN.ipynb` | Graf Sinir Ağları (GNN), mesaj geçişi, grafik evrişimi (GCN), GraphSAGE |
| 12 | `Ders12_Normallestiren_Akislar.ipynb` | Normalleştiren akışlar (Normalizing Flows), değişken değişimi teoremi, RealNVP, yoğunluk tahmini |

---

## 🚀 Kurulum

### 1. Repoyu klonla

```bash
git clone https://github.com/HAYDARKILIC/derin_ogrenme.git
cd derin_ogrenme
```

### 2. Sanal ortam oluştur (önerilir)

```bash
python -m venv venv
source venv/bin/activate        # Linux/macOS
venv\Scripts\activate           # Windows
```

### 3. Bağımlılıkları yükle

```bash
pip install -r requirements.txt
```

### 4. Jupyter'ı başlat

```bash
jupyter notebook
```

---

## 🛠️ Gereksinimler

Tüm bağımlılıklar `requirements.txt` dosyasında listelenmiştir.  
Python **3.10+** önerilir.

---

## 📁 Repo Yapısı

```
derin_ogrenme/
├── Ders1_Giris_Gozetimli_Ogrenme.ipynb
├── Ders2_Sig_ve_Derin_Aglar.ipynb
├── Ders3_Kayip_Fonksiyonlari.ipynb
├── Ders4_Egitim_Geriye_Yayilim.ipynb
├── Ders5_Performans_ve_Regularizasyon.ipynb
├── Ders6_CNN_ResNet.ipynb
├── Ders7_Transformers.ipynb
├── Ders8_UretkenModeller_GAN_VAE_Diffusion.ipynb
├── Ders9_PekistirmeliOgrenme.ipynb
├── Ders10_NedenDerinOgrenme.ipynb
├── Ders11_GNN.ipynb
├── Ders12_Normallestiren_Akislar.ipynb
├── requirements.txt
└── README.md
```

---

## 📖 Kaynak Kitap

Prince, S.J.D. (2023). *Understanding Deep Learning*. MIT Press.  
🔗 https://udlbook.github.io/udlbook/

