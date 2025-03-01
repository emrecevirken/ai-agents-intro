# 🧠 AI Ajanları: Akıllı Sistemler Nasıl Çalışır?

## 🚀 AI Ajanı Nedir?
Bir **yapay zeka ajanı**, belirli bir hedef doğrultusunda çevresiyle etkileşime giren, kararlar alabilen ve aksiyonlar gerçekleştirebilen bir sistemdir. AI ajanları **düşünme, plan yapma ve harekete geçme** yeteneklerine sahiptir.

Bir ajanın iki temel bileşeni vardır:

### **1️⃣ Beyin (AI Modeli)**
- Ajanın karar mekanizmasıdır.
- Çevresinden aldığı bilgileri işler, analiz eder ve en uygun aksiyonu seçer.
- Genellikle **LLM (Large Language Model - Büyük Dil Modeli)** kullanır.

### **2️⃣ Vücut (Araçlar & Yetenekler)**
- Ajanın sahip olduğu **ekstra araçlar (tools)** ve **yetkinliklerdir**.
- Örneğin, bir insanın uçamaması gibi, bir AI modeli de yalnızca sahip olduğu araçlarla sınırlıdır.
- Örnek: **Bir AI modeli e-posta gönderemez**, ancak ona bir **e-posta gönderme aracı** eklenirse bu işlemi yapabilir!

---

## 🔥 Hangi AI Modelleri Kullanılıyor?
AI ajanlarında en sık kullanılan modeller **LLM (Büyük Dil Modeli)**'lerdir:

- **GPT-4** (OpenAI)
- **Llama** (Meta)
- **Gemini** (Google)

Bunlar genellikle **metin bazlıdır**, ancak **VLM (Vision Language Model)** gibi görüntü işleyebilen modeller de ajan olarak kullanılabilir.

---

## ⚙️ AI Ajanları Nasıl Çalışır?
LLM'ler **sadece metin üretir**. Ancak, geliştiriciler **araçlar (tools)** ekleyerek onlara ekstra yetenekler kazandırır.

Örneğin:
- **ChatGPT'nin resim oluşturabilmesi** → Görsel oluşturma aracı kullanır.
- **Bir ajanın e-posta gönderebilmesi** → Python'da "send_email" fonksiyonu kullanır.

```python
# AI Ajanı için e-posta gönderme aracı

def send_message_to(recipient, message):
    """Belirtilen alıcıya e-posta gönderen araç."""
    print(f"E-posta gönderiliyor: {recipient} -> {message}")
    # Gerçek e-posta gönderme kodu buraya gelir.
```

Bir AI ajanı bu aracı kullanarak e-posta gönderebilir:

```python
send_message_to("Manager", "Bugünkü toplantıyı erteleyebilir miyiz?")
```

Bu araçlar ne kadar iyi tasarlanırsa, ajanın performansı da o kadar güçlü olur. 🚀

---

## 🏆 AI Ajanları Nerelerde Kullanılıyor?

### **📱 1️⃣ Kişisel Asistanlar**
Siri, Alexa ve Google Assistant gibi asistanlar, AI ajanlarının en yaygın örneklerindendir.
- Kullanıcıdan gelen sorguları işler.
- Bilgiyi analiz eder ve doğru aksiyonları alır.
- Örneğin: "Beni sabah 7’de uyandır" dediğinizde alarm kurar.

### **💬 2️⃣ Müşteri Hizmetleri Chatbotları**
Şirketler, müşteri desteği için AI ajanlarını kullanır.
- Soru-cevap yapabilir, rehberlik edebilir, hatta işlemleri tamamlayabilir.
- Örneğin: "Siparişim nerede?" sorusuna kargo takibi yaparak yanıt verebilir.

### **🎮 3️⃣ Video Oyunlarındaki NPC'ler**
Geleneksel oyun karakterleri belirli kurallara göre hareket eder. Ancak **LLM destekli NPC'ler** çok daha dinamik olabilir!
- Oyuncuya özel diyaloglar oluşturabilir.
- Gerçek zamanlı olarak oyuna adapte olabilir.

---

## 🔥 Özet
Bir **AI ajanı**:
✅ **Doğal dili anlar.**
✅ **Düşünür, plan yapar ve karar alır.**
✅ **Çevresiyle etkileşime girerek görevleri yerine getirir.**

Gelecekte bu ajanların hayatımıza nasıl entegre olacağını hep birlikte göreceğiz! 🚀
