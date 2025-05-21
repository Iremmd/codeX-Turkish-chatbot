
<p align="center">
  <img src="codeXvirtual.png" alt="CodeX Logo" style="width: 200px;">
</p>

<h1 align="center">CodeX: Türkçe Soru-Cevap Asistanı</h1>

<p align="center">
     Belge tabanlı, Türkçe destekli yapay zeka chatbot sistemi  
</p>

---

## 📌 Proje Hakkında

**CodeX**, `soru-cevap.json` dosyasındaki metinleri analiz ederek, kullanıcıdan gelen Türkçe sorulara bağlam tabanlı ve anlamlı cevaplar üreten bir yapay zeka asistanıdır. OpenAI'nin GPT modeli ve LangChain kütüphanesi ile oluşturulmuş, kullanıcı arayüzü ise **Streamlit** ile tasarlanmıştır.
> **Not:** Bu proje Google Colab ortamında geliştirilmiş ve çalıştırılması önerilmektedir.

---

## 🎯 Özellikler

- Türkçe dil desteği
- JSON tabanlı belge analizi
- Streamlit tabanlı sohbet arayüzü
- OpenAI GPT-3.5-Turbo ile doğal dil yanıtları
- ChromaDB ile belge vektörleştirme (RAG mimarisi)

---

## ⚙️ Kullanım ve Proje Yapısı

1. `soru-cevap.json` dosyasını proje klasörüne yerleştirin.  
2. `openai.api_key` alanını kendi API anahtarınızla doldurun.  
3. Uygulamayı başlatmak için terminalde şu komutu çalıştırın:

```bash
streamlit run codeX.ipynb
```

> **Not:** Colab ortamında çalıştırırken, `streamlit` uygulamasını erişilebilir kılmak için `localtunnel` veya `ngrok` kullanabilirsiniz.

Proje klasör yapısı aşağıdaki gibidir:

```
📦 codeX-Turkish-chatbot/
├── codeX.ipynb
├── codeXvirtual.png
├── soru-cevap.json
└── README.md
```


