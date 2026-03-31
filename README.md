# 🧬 Biology Trainer

Εφαρμογή προετοιμασίας για τις **Πανελλαδικές Εξετάσεις 2026** στη Βιολογία Γ' Λυκείου.

Αναπτύχθηκε από την **EisatoponAI** | [eisatopon.gr](https://eisatopon.gr)

---

## 📱 Χαρακτηριστικά

- 📖 **57 ερωτήσεις** από το επίσημο σχολικό βιβλίο
- 🧬 **Τεύχος Α'** — Πρωτεΐνες, Κύτταρο, Ένζυμα, Μίτωση & Μείωση
- 🔬 **Τεύχος Β'** — Γενετικό Υλικό, DNA, Βιοτεχνολογία, Κληρονομικότητα
- ✅ Ερωτήσεις τύπου **MCQ** και **Ανοιχτής Απάντησης**
- 🏆 **Τεστ Αξιολόγησης** με τυχαίες ερωτήσεις από όλα τα κεφάλαια
- 💡 Hints και αναφορές σελίδας βιβλίου
- 🎯 Badge δυσκολίας (Εύκολο / Μέτριο / Δύσκολο)
- 📊 Αποτελέσματα στο τέλος κάθε κεφαλαίου

---

## 🗂️ Δομή Περιεχομένου

Οι ερωτήσεις αποθηκεύονται στο GitHub repo:
[biology-trainer-content](https://github.com/Eisatopon/biology-trainer-content)

| Αρχείο | Περιεχόμενο |
|--------|-------------|
| `Biology a ch1.json` | Πρωτεΐνες |
| `Biology a ch2.json` | Κύτταρο: Πυρήνας & Οργανίδια |
| `Biology a ch3.json` | Ένζυμα |
| `Biology a ch4.json` | Μίτωση & Μείωση |
| `Biology ch1.json` | Το Γενετικό Υλικό |
| `Biology ch2.json` | Αντιγραφή & Έκφραση |
| `Biology ch3.json` | Ένζυμα (Τεύχος Β') |
| `Biology ch4.json` | Ανασυνδυασμένο DNA |
| `Biology ch5.json` | Μενδελική Κληρονομικότητα |
| `Biology ch6.json` | Μεταλλάξεις |
| `Biology ch7.json` | Αρχές Βιοτεχνολογίας |
| `Biology ch8.json` | Βιοτεχνολογία στην Ιατρική |
| `Biology ch9.json` | Γεωργία & Κτηνοτροφία |

---

## 🛠️ Τεχνολογίες

- **Flutter** — Cross-platform mobile framework
- **Dart** — Programming language
- **GitHub Pages** — Hosting JSON content
- **shared_preferences** — Local storage
- **http** — Network requests

---

## 🚀 Εγκατάσταση

```bash
git clone https://github.com/Eisatopon/biology_trainer.git
cd biology_trainer
flutter pub get
flutter run
```

---

## 📋 Μορφή JSON Ερωτήσεων

```json
{
  "chapter": "A1",
  "title": "Πρωτεΐνες: Διαδεδομένες, Πολύπλοκες και Εύθραυστες",
  "subject": "Βιολογία Προσανατολισμού",
  "units": [
    {
      "id": "A1_Q01",
      "topic": "Δομικά συστατικά πρωτεϊνών",
      "type": "mcq",
      "question": "Ερώτηση...",
      "options": ["α. ...", "β. ...", "γ. ...", "δ. ..."],
      "correct": "β",
      "answer": "Πλήρης απάντηση...",
      "hint": "Υπόδειξη...",
      "difficulty": "Easy",
      "page": 22,
      "source": "Βιβλίο"
    }
  ]
}
```

---

## 👨‍🏫 Δημιουργός

**Σωκράτης Ρωμανίδης** — Μαθηματικός 

🌐 [eisatopon.gr](https://eisatopon.gr) | EisatoponAI

---

*Καλή επιτυχία στις Πανελλαδικές 2026! 🎓*
