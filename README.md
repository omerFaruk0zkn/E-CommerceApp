# 🛒 E-Commerce Store

**E-Commerce Store**, kullanıcıların ürünleri görüntüleyip satın alabileceği, modern ve tam işlevsel bir e-ticaret web uygulamasıdır. Uygulama, kullanıcı kimlik doğrulaması, ürün yönetimi, alışveriş sepeti ve sipariş işlemleri gibi temel e-ticaret özelliklerini sunar.

🔗 [Canlı Uygulama](https://e-commerceapp-szoe.onrender.com)

---

## 🚀 Özellikler

- **Kullanıcı Kimlik Doğrulama**: Güvenli giriş ve kayıt işlemleri.
- **Ürün Yönetimi**: Ürünleri listeleme, detaylarını görüntüleme ve stok takibi.
- **Alışveriş Sepeti**: Ürünleri sepete ekleme, çıkarma ve toplam tutarı hesaplama.
- **Sipariş İşlemleri**: Sipariş oluşturma ve sipariş geçmişini görüntüleme.
- **Responsive Tasarım**: Tüm cihazlarda uyumlu ve kullanıcı dostu arayüz.

---

## 🛠️ Teknoloji Yığını

- **Frontend**: React, Tailwind CSS, Vite
- **Backend**: Node.js, Express.js
- **Veritabanı**: MongoDB
- **Kimlik Doğrulama**: JSON Web Tokens (JWT)
- **Durum Yönetimi**: Zustand

---

## 📁 Proje Yapısı

```
ecommerce-store/
├── backend/
│   ├── controllers/
│   ├── lib/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── server.js
├── frontend/
│   ├── src/
│     ├── components/
│     ├── lib/
│     ├── pages/
│     ├── stores/
│     ├── App.jsx
│     └── main.jsx
├── .gitignore
├── package.json
└── README.md
```

---

## ⚙️ Kurulum ve Çalıştırma

### 1. Depoyu Klonlayın

```bash
git clone https://github.com/omerFaruk0zkn/ecommerce-store.git
cd ecommerce-store
```

### 2. Ortam Değişkenlerini Ayarlayın

#### Backend (`/backend` dizininde `.env` dosyası oluşturun):

```
PORT=5001
MONGO_URI=your_mongo_uri
ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret
CLIENT_URL=your_client_url
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_secret_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
STRIPE_SECRET_KEY=your_stripe_secret_key
UPSTASH_REDIS_URL=your_upstash_redis_url
NODE_ENV=development
```

### 3. Bağımlılıkları Yükleyin ve Uygulamayı Başlatın

#### Backend:

```bash
npm install
npm run dev
```

#### Frontend:

```bash
cd frontend
npm install
npm run dev
```

---

## 🧪 Test ve Geliştirme

- **Geliştirme Ortamı**: Vite ile hızlı geliştirme ve sıcak yeniden yükleme.
- **Hata Ayıklama**: Hem istemci hem de sunucu tarafında kapsamlı hata ayıklama araçları.
