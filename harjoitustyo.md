# Harjoitustyö: Käyttäjäkohtainen sääsovellus

## 1. Idea

Sovellus on käyttäjäkohtainen **sääpalvelu**, jossa käyttäjä voi kirjautua sisään ja tallentaa omia **suosikkikaupunkejaan**.  
Sovellus hakee ajantasaiset säätiedot OpenWeatherMapin rajapinnan (REST API) kautta ja näyttää lämpötilan, sääkuvauksen sekä kuvakkeen.  

Tavoitteena on tehdä käytännöllinen ja helppokäyttöinen sivusto, joka tarjoaa käyttäjälle hyödyllistä tietoa arjessa.

---

## 2. Toteutus ja tekniikat

- **Frontend:** React + TypeScript + Vite  
- **Autentikointi:** Firebase Authentication (sähköposti + salasana)  
- **Tietokanta:** Firebase Firestore  
- **Säädata:** OpenWeatherMap REST API  
- **Tyylit:** kevyt oma CSS (responsiivinen grid-layout)  
- **Hosting:** toimii buildin jälkeen myös GitHub Pagesissa  

Jokaisella käyttäjällä on oma tunnus, ja hänen lisäämänsä kaupungit tallennetaan Firestoreen polkuun:

