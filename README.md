# 🚀 UiPath Actions Auto-Refresh — Powered by a Simple Bookmark

<div align="center">

🌍 [🇹🇷 Türkçe](#-türkçe) • [🇬🇧 English](#-english) • [🇩🇪 Deutsch](#-deutsch)

</div>

---

## 🇹🇷 Türkçe

### 📘 Genel Bakış
**UiPath Actions (Action Center)**, insan onayı gerektiren süreçlerin yönetilmesini sağlayan güçlü bir bileşendir.  
Ancak Inbox bölümüne yeni görevler (task) geldiğinde otomatik yenileme (auto-refresh) özelliği bulunmamaktadır.  

Bu durum, yüksek işlem hacmine sahip veya zaman hassasiyeti olan projelerde yeni gelen işlemlerin anında görünmesini engelleyebilir.  

🧠 Bunun için yalnızca bir **Bookmark (Yer İmi)** ile çalışan, herhangi bir **eklenti veya entegrasyon gerektirmeyen**,  
**hafif, kolay entegre edilebilir ve bağımlılığı düşük** bir çözüm geliştirdim.  

### 💡 Özellikler
- Sadece **Action Center / Inbox (Unassigned)** sekmesinde çalışır  
- Her **10 saniyede bir** görev listesini otomatik yeniler  
- Tarayıcı kapatılana veya sayfa yenilenene kadar çalışmaya devam eder  
- **Chrome, Edge ve Brave** ile uyumludur  
- Tek tıklama ile **aktif / pasif** hale getirilebilir  

---

### ⚙️ Kurulum
1️⃣ Tarayıcınızda yeni bir **Bookmark (Yer İmi)** oluşturun  
2️⃣ Sağ tıklayıp **Düzenle (Edit)** seçeneğini seçin  
3️⃣ Bookmark’a bir isim verin  
4️⃣ **URL** alanına bu depodaki [kodlardan](#kodlar) birini yapıştırın  
5️⃣ Kaydedin ✅  

---

### 🔧 Kullanım
1️⃣ **UiPath Action Center** sayfasını açın  
2️⃣ “**Unassigned**” sekmesi açıkken oluşturduğunuz Bookmark’a tıklayın  
3️⃣ Sol tarafta küçük bir ⚙️ ikon belirecektir  
4️⃣ Bu ikon üzerinden **Auto-Refresh** özelliğini açıp kapatabilirsiniz  

---

### 📜 Kodlar
- [JavaScript (Türkçe)](./scripts/auto-refresh-tr.js)  
- [JavaScript (English)](./scripts/auto-refresh-en.js)  
- [JavaScript (Deutsch)](./scripts/auto-refresh-de.js)

---

### 🧩 Not
Bu çözüm **yalnızca UiPath Action Center sayfasında** çalışır.  
Tarayıcı kapatıldığında veya sayfa yenilendiğinde (F5) işlem durur. Yeniden başlatmak için Bookmark’a tekrar tıklayın.

---

### 🙏 Teşekkür
Bu fikrin olgunlaşmasında destek veren yöneticime teşekkür ederim.  
Geri bildirimlerinizi ve geliştirme önerilerinizi duymaktan memnuniyet duyarım.  

---

## 🇬🇧 English

### 📘 Overview
**UiPath Actions (Action Center)** is a powerful component for managing human-in-the-loop workflows.  
However, it lacks an **auto-refresh** feature for the Inbox section when new tasks arrive.  

This can cause delays in high-volume or time-sensitive projects.  

🧠 This lightweight **bookmark-based solution** enables **live auto-refresh** without extensions or integrations.  
It’s simple, dependency-free, and works instantly.

### 💡 Features
- Works only on **Action Center / Inbox (Unassigned)**  
- Refreshes task list every **10 seconds**  
- Keeps running until browser is closed or page is refreshed  
- Compatible with **Chrome, Edge, and Brave**  
- Toggle **ON/OFF** via on-screen icon  

---

### ⚙️ Setup
1️⃣ Create a new **Bookmark** in your browser  
2️⃣ Right-click → **Edit**  
3️⃣ Give it a name  
4️⃣ Paste the code from this repo’s [scripts section](#scripts) into the **URL** field  
5️⃣ Save ✅  

---

### 🔧 Usage
1️⃣ Open the **UiPath Action Center** page  
2️⃣ Keep the “**Unassigned**” tab active  
3️⃣ Click the saved bookmark  
4️⃣ A small ⚙️ icon will appear on the left side  
5️⃣ Click it to toggle auto-refresh on/off  

---

### 📜 Scripts
- [JavaScript (Turkish)](./scripts/auto-refresh-tr.js)  
- [JavaScript (English)](./scripts/auto-refresh-en.js)  
- [JavaScript (German)](./scripts/auto-refresh-de.js)

---

### 🧩 Note
Works **only** on UiPath Action Center pages.  
If the page is refreshed or the browser closed, simply click the bookmark again to reactivate.

---

### 🙏 Acknowledgment
Special thanks to my manager for their guidance and encouragement.  
Feedback and improvements are always welcome.  

---

## 🇩🇪 Deutsch

### 📘 Überblick
**UiPath Actions (Action Center)** ist eine leistungsstarke Komponente zur Verwaltung von Prozessen mit menschlicher Beteiligung.  
Allerdings verfügt der Inbox-Bereich nicht über eine automatische Aktualisierung, wenn neue Tasks eintreffen.  

🧠 Diese leichte **Bookmark-Lösung** bietet eine Live-Auto-Refresh-Funktion — ganz ohne Erweiterungen oder Integrationen.  

### 💡 Funktionen
- Funktioniert nur im **Action Center / Inbox (Unassigned)**  
- Aktualisiert alle **10 Sekunden**  
- Läuft, bis der Browser geschlossen oder die Seite neu geladen wird  
- Kompatibel mit **Chrome, Edge und Brave**  
- Aktivieren/Deaktivieren über ⚙️ Symbol  

---

### ⚙️ Einrichtung
1️⃣ Neues **Bookmark** im Browser erstellen  
2️⃣ Rechtsklick → **Bearbeiten (Edit)**  
3️⃣ Einen Namen vergeben  
4️⃣ Code aus dem [Scripts-Bereich](#skripte) dieses Repos ins **URL-Feld** einfügen  
5️⃣ Speichern ✅  

---

### 🔧 Verwendung
1️⃣ **UiPath Action Center** öffnen  
2️⃣ “**Unassigned**”-Tab aktiv halten  
3️⃣ Auf das gespeicherte Bookmark klicken  
4️⃣ Links erscheint ein kleines ⚙️ Symbol  
5️⃣ Mit einem Klick kann Auto-Refresh ein- oder ausgeschaltet werden  

---

### 📜 Skripte
- [JavaScript (Türkisch)](./scripts/auto-refresh-tr.js)  
- [JavaScript (Englisch)](./scripts/auto-refresh-en.js)  
- [JavaScript (Deutsch)](./scripts/auto-refresh-de.js)

---

### 🧩 Hinweis
Funktioniert **nur** auf UiPath Action Center Seiten.  
Nach einem Refresh genügt ein Klick auf das Bookmark, um es erneut zu starten.

---

### 🙏 Dank
Vielen Dank an meinen Vorgesetzten für die Unterstützung und Inspiration.  
Feedback und Verbesserungsvorschläge sind jederzeit willkommen.  

---

### 🧠 License
MIT License © 2025 [Hasan Emre Ayyildiz](https://www.linkedin.com/in/hasan-emre-ayyildiz/)
