# 💰 Mobile App Expenses

Aplicație Android de gestionare a cheltuielilor, dezvoltată pentru a permite utilizatorilor să își monitorizeze ușor și eficient bugetul personal. Structura aplicației este modulară și include funcționalități precum listarea cheltuielilor, adăugarea/editarea acestora, import de date din API, profil, recenzii și pagină „Despre”.

---

## 📱 Funcționalități

- ✅ Adăugare, editare și ștergere cheltuieli
- 📋 Vizualizare listă cheltuieli în ecranul principal (Home)
- 🔄 Salvare și sincronizare locală cu bază de date (Room)
- ☁️ Import date din API extern (npoint)
- 👤 Pagină de profil cu informații despre utilizator
- 📝 Secțiune pentru review-uri
- ℹ️ Pagina „Despre” cu informații aplicație
- 🧭 Navigație cu meniu drawer
- ➕ Buton flotant pentru adăugare rapidă

---

## 🧰 Tehnologii folosite

- **Java** (Android SDK)
- **Room Database** pentru persistarea datelor
- **Fragments** pentru ecrane multiple
- **DrawerLayout** pentru navigare laterală
- **ActivityResultLauncher** pentru transfer date între activități
- **AsyncTaskRunner + ExecutorService** pentru apeluri de rețea
- **Custom Callback Interface** pentru async networking
- **Json parsing** cu `ExpenseParser`
- **HttpManager** pentru apeluri HTTP către API
