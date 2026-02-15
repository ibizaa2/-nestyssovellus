# Käyttötapaus 1: Äänestä ja näytä äänestyksen tulokset

**Käyttäjät:** Tavallinen käyttäjä  
**Laukaisija:** Käyttäjä haluaa äänestää
**Esiehto:** Käyttäjä on kirjautunut sisään  
**Jälkiehto:** Näytetään äänestykset ja niiden tulokset  

## Käyttötapauksen kulku

1. Käyttäjä valitsee äänestyksen
2. Käyttäjä valitsee vaihtoehdon
3. Käyttäjä painaa "Äänestä"
4. Sovellus näyttää äänestyksen tulokset

**Poikkeuksellinen toiminta:** Ei ole

---

# Käyttötapaus 2: Tee uusi äänestys

**Käyttäjät:** Ylläpitäjä  
**Laukaisija:** Ylläpitäjä haluaa lisätä uuden äänestyksen  
**Esiehto:** Ylläpitäjä on kirjautuneena sisään  
**Jälkiehto:** Uusi äänestys tallennetaan ja se näytetään  

## Käyttötapauksen kulku

1. Ylläpitäjä syöttää kysymyksen ja vaihtoehdot  
2. Ylläpitäjä painaa "Julkaise äänestys"  

**Poikkeuksellinen toiminta:** Jos kysymystä ei ole tai vaihtoehtoja liian vähän, näytetään  
*"Lisää kysymys ja vähintään 2 vaihtoehtoa"*

---

# Käyttötapaus 3: Poista äänestys

**Käyttäjät:** Ylläpitäjä  
**Laukaisija:** Ylläpitäjä haluaa poistaa olemassa olevan äänestyksen  
**Esiehto:** Ylläpitäjä on kirjautunut sisään ja äänestys on olemassa  
**Jälkiehto:** Valittu äänestys poistetaan sovelluksesta ja sitä ei enää näy  

## Käyttötapauksen kulku

1. Ylläpitäjä valitsee äänestyksen, jonka haluaa poistaa  
2. Ylläpitäjä klikkaa "Poista äänestys"  
3. Sovellus poistaa äänestyksen ja päivittää sivun  

**Poikkeuksellinen toiminta:** Ei ole