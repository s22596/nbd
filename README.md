# 📁 Zarządzanie Plikami Uczelnianymi z Wykorzystaniem MongoDB

## 📖 Spis Treści
1. [📜 O Projekcie](#-o-projekcie)
2. [⚙️ Wymagania](#️-wymagania)
3. [🛠️ Wykorzystane Technologie](#️-wykorzystane-technologie)
4. [🚀 Sposób Działania](#-sposób-działania)
5. [✨ Możliwości Programu](#-możliwości-programu)
6. [🎥 Demo](#-demo)

---

## 📜 O Projekcie

Projekt ten umożliwia **zarządzanie, wyszukiwanie i pobieranie plików** znajdujących się na dyskach sieciowych **P** i **Z**.  
Dzięki zastosowaniu **GridFS** w połączeniu z bazą **MongoDB**, możliwe jest przechowywanie dużych plików z dysku P w zmapowanym systemie plików.  
Z powodu ograniczonego miejsca na lokalnym komputerze, zmapowany został wyłącznie dysk **P**.

---

## ⚙️ Wymagania

Aby program działał poprawnie:  
1. Należy być podłączonym do **VPN uczelni**.  
2. W pliku `AppConfig` należy ustawić zmienną `PJATK_STUDENT_NUMBER` na swój numer studenta.

---

## 🛠️ Wykorzystane Technologie

- **Java** z użyciem **Spring Boot**
- **MongoDB** z implementacją **GridFS**

---

## 🚀 Sposób Działania

Po uruchomieniu aplikacji, program:  
1. Tworzy w **MongoDB** bazę danych o nazwie `nbd`.  
2. W bazie znajdują się foldery:  
   - `fs.chunks`  
   - `fs.files`  
3. Baza przechowuje strukturę i zawartość dysku **Z**.  

Przykładowa zawartość bazy danych:

---

## ✨ Możliwości Programu

- 📂 **Pobieranie plików**  
- 🔍 **Wyszukiwanie plików i folderów**  
- 📁 **Nawigacja między folderami**  
- 🖥️ **Intuicyjny i estetyczny interfejs graficzny**

---

## 🎥 Demo

Poniżej znajduje się film przedstawiający działanie programu:  
➡️ [Link do filmu](https://youtu.be/FatvxuNfioE)  

---

💡 *Zachęcam do zgłaszania uwag i propozycji ulepszeń w sekcji Issues!*
