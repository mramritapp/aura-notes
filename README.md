# 📱 Aura Notes — Real Native Android App (Jetpack Compose)

यह एक **100% असली नेटिव एंड्रॉइड ऐप (Native Android Application)** है, जिसे Google के सबसे आधुनिक **Kotlin + Jetpack Compose + Material 3 (Material You)** आर्किटेक्चर के साथ तैयार किया गया है।

---

## 🌟 इस असली एंड्रॉइड ऐप की विशेषताएं (Native Features):

1. **🎨 120Hz मक्खन जैसा स्मूथ Native UI**:
   - Google के सबसे आधुनिक **Jetpack Compose** पर आधारित, कोई वेबव्यू या HTML नहीं।
   - **Staggered Grid Layout**: Google Keep और Apple Notes जैसा खूबसूरत 2-कॉलम कार्ड लेआउट।
   - **Material 3 Dynamic Theming**: डार्क और लाइट मोड का सपोर्ट।

2. **🌈 कलर कोडिंग और पेस्टल पैलेट्स**:
   - हर नोट के लिए अलग-अलग पेस्टल कलर्स (Rose, Mint, Sky, Lavender, Amber) चुनने की सुविधा।

3. **📌 पिन और पसंदीदा**:
   - ज़रूरी नोट्स हमेशा ऊपर पिन रहते हैं।

4. **🏷️ टैग्स और रियल-टाइम फ़िल्टर**:
   - `#काम`, `#विचार` जैसे टैग्स के साथ आसान चिप्स फ़िल्टर।

5. **⚡ ऑटो-सेव और लोकल स्टोरेज**:
   - लिखते ही नोट तुरंत आपके फोन की लोकल मेमोरी में सुरक्षित हो जाता है।

---

## 🚀 इस प्रोजेक्ट को Android Studio में कैसे खोलें और चलाएं:

### 1-क्लिक तरीका:
- इस फ़ोल्डर में मौजूद **`open_in_android_studio.bat`** फ़ाइल पर डबल-क्लिक करें।
- यह सीधे आपके कंप्यूटर पर इंस्टॉल **Android Studio** में इस प्रोजेक्ट को खोल देगा।

### सामान्य तरीका:
1. अपने कंप्यूटर पर **Android Studio** खोलें।
2. **"Open"** पर क्लिक करें।
3. इस फ़ोल्डर को चुनें:  
   `C:\Users\hp\Downloads\anti projects\AuraNotesAndroid`
4. Android Studio प्रोजेक्ट की Gradle फाइलों को लोड करेगा।
5. ऊपर हरे रंग के **Run (▶)** बटन को दबाएं — ऐप आपके फोन या एमुलेटर पर तुरंत इंस्टॉल होकर चल पड़ेगा!
6. **APK बनाने के लिए:** Android Studio के मेन्यू में जाएं: **Build ➔ Build Bundle(s) / APK(s) ➔ Build APK(s)**।

---

## 📂 प्रोजेक्ट का कोड स्ट्रक्चर:

```
AuraNotesAndroid/
├── app/
│   ├── src/main/
│   │   ├── AndroidManifest.xml
│   │   ├── java/com/aura/notes/
│   │   │   ├── MainActivity.kt                (नेविगेशन और एंट्री पॉइंट)
│   │   │   ├── model/Note.kt                  (डेटा मॉडल)
│   │   │   ├── data/NotesRepository.kt        (लोकल स्टोरेज लॉजिक)
│   │   │   ├── viewmodel/NotesViewModel.kt    (स्टेट मैनेजमेंट)
│   │   │   ├── ui/
│   │   │   │   ├── theme/                     (थीम, कलर्स, टाइपोग्राफी)
│   │   │   │   ├── components/NoteCard.kt     (कार्ड डिज़ाइन)
│   │   │   │   └── screens/
│   │   │   │       ├── HomeScreen.kt          (मुख्य स्क्रीन, सर्च, ग्रिड)
│   │   │   │       └── EditNoteScreen.kt      (एडिटर, कलर पिकर, टैग्स)
│   │   └── res/                               (स्ट्रिंग्स, थीम्स, आइकन्स)
├── build.gradle.kts
├── settings.gradle.kts
└── open_in_android_studio.bat
```
