[README.md](https://github.com/user-attachments/files/27748785/README.md)
# Mfumo wa Usajili wa Masjid Taqwa (Kibaha)

Mfumo huu ni fomu rasmi ya kidijitali kwa ajili ya kusajili watu wanaoingia katika dini ya Kiislamu (Kusilimu) katika Masjid Taqwa - Kibaha, Mailimoja. Mfumo huu unarahisisha ukusanyaji wa taarifa, utunzaji wa kumbukumbu, na utoaji wa namba za usajili za kiotomatiki.

# 🌟 Vipengele Muhimu (Features)

* **Usajili wa Kiotomatiki (Auto-Registration No):** Mfumo unazalisha namba ya usajili (mfano: `MTK/FRK/026/001`) kwa kutumia mwaka husika na namba inayofuata kutoka kwenye kanzidata ya Google Sheets.
* **QR Code Verification:** Kila fomu inayojazwa inatengeneza QR Code ya kipekee papo hapo kwa ajili ya uthibitisho wa usajili.
* **Uraia na Code za Simu:** Sehemu ya namba ya simu inabadilika kiotomatiki kulingana na nchi iliyochaguliwa (Tanzania +255, Kenya +254, Uganda +256, n.k.).
* **Hali ya Ndoa kulingana na Jinsia:** Chaguzi za hali ya ndoa zinabadilika kulingana na jinsia iliyochaguliwa (Mwanaume: Nimeoa/Sijaoa | Mwanamke: Nimeolewa/Sijaolewa).
* **Upakiaji wa Picha:** Inaruhusu kupakia picha ya muombaji na kuiona papo hapo (Image Preview) kabla ya kuhifadhi.
* **Ujumuishaji wa Google Sheets:** Data zote zinahifadhiwa moja kwa moja kwenye Google Sheets kwa urahisi wa usimamizi wa ofisi na ripoti.
* **Muonekano wa Kisasa:** Imetengenezwa kwa Tailwind CSS, ikiwa na muonekano mzuri kwenye simu (Responsive) na inaruhusu kuchapa (Print) fomu kwa urahisi.

## 🛠️ Teknolojia Zilizotumika

* **HTML5 & CSS3** (Tailwind CSS Framework)
* **JavaScript (Vanilla)** - Kwa mantiki ya fomu na utendaji.
* **Google Apps Script** - Kama daraja (API) la kuunganisha fomu na kanzidata.
* **Google Sheets** - Kama kanzidata kuu (Database).
* **QRCode.js** - Maktaba ya kutengeneza QR Codes.

## 🚀 Jinsi ya Kuitumia (Setup)

1.  **Clone Repository:**
    ```bash
    git clone [https://github.com/ramadhanijuma/fomu-ya-kusilimu.git](https://github.com/ramadhanijuma/fomu-ya-kusilimu.git)
    ```
2.  **Google Sheets Setup:**
    * Tengeneza Google Sheet mpya yenye safu (columns) zinazolingana na majina ya kwenye fomu.
    * Nenda kwenye `Extensions > App Script`.
    * Weka kodi ya backend inayopokea data na inayotoa namba ya usajili.
    * Fanya 'Deploy' kama Web App na chagua ruhusa ya "Anyone".
3.  **Unganisha Script URL:**
    * Nakili Web App URL uliyopewa na Google.
    * Iweke kwenye file la `index.html` kwenye sehemu ya:
      `const SCRIPT_URL = 'WEKA_LINK_YAKO_HAPA';`

## 📂 Muundo wa Mafaili

* `index.html`: Faili kuu lenye muundo wa fomu, muonekano, na kodi zote za JavaScript.
* `README.md`: Maelezo ya mradi na maelekezo (Faili hili).

## 📄 Leseni
Mradi huu ni kwa ajili ya matumizi ya Masjid Taqwa - Kibaha na unaweza kuboreshwa kwa ajili ya matumizi mengine ya taasisi za kijamii.

---
**Imeandaliwa na:** Ramadhani J. Ramadhani  
**Mahali:** Kibaha, Tanzania.
