
Bu proje, TikTok için otomatik **Görüntüleme, Beğeni, Takipçi, Paylaşma ve Kaydetme** işlemleri yapabilen bir Python botudur.  
Bot, **Pydroid3** ve **Termux** üzerinde çalışacak şekilde tasarlanmıştır.

---


## ⚙️ Özellikler
- Video linki veya kullanıcı profili linki ile sipariş oluşturur.
- Birden fazla servisi aynı anda çalıştırabilir.
- Sipariş sonuçlarını `tiktok_bot_log.txt` dosyasına kaydeder.
- Sonsuz döngü ile durmadan çalışır.
- Pydroid3 ve Termux uyumlu.

---

## 🛠 Kurulum

### 1️⃣ Python ve pip
Termux:
```bash
pkg update && pkg upgrade -y
```
```bash
pkg install git
```
```bash
pkg install python git -y
```
```bash
git clone https://github.com/ibrahimadaballi/Tiktok
```
```bash
cd Tiktok
```
```bash
ls
```
```bash
pip install -r requirements.txt
```
```bash
tiktok.py
```
paydroid3:

$ pip install -r requirements.txt

$ python tiktok.py





















