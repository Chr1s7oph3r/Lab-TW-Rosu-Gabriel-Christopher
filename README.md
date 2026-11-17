# City Explorer - F1 Edition

Proiect de semestru realizat în cadrul disciplinei Tehnologii Web. 

Acest repository prezintă evoluția unei aplicații web, pornind de la o machetă statică (HTML/CSS) și progresând către o aplicație modernă folosind **Vite**, **React** și **JavaScript ES6+**. Tematica aplicației este axată pe destinații turistice din calendarul competițional Formula 1.

**Autor:** Rosu Gabriel-Christopher

---

## 🏎️ Stadiul Proiectului

### Laboratorul 1: Macheta Statică
- Crearea scheletului semantic folosind HTML5.
- Implementarea unui layout responsiv modern utilizând CSS Grid (pentru cardurile cu circuite) și Flexbox (pentru zona de navigare).
- Stilizarea formularelor și implementarea efectelor vizuale avansate.

### Laboratorul 2: Vite și JavaScript Modern
- Migrarea proiectului către un mediu de dezvoltare susținut de **Vite** și instalarea dependențelor cu `npm`.
- Decuplarea logicii în module separate (`data`, `utils`, `api`).
- Prelucrarea datelor folosind funcții JavaScript pure (`map`, `filter`, `reduce`), respectând principiul imutabilității datelor.
- Implementarea cererilor asincrone (`async/await`, `fetch`) către un API public (`jsonplaceholder`).
- *Notă:* Interfața grafică a fost temporar ascunsă, rezultatele fiind vizualizate în consola browserului.

### Laboratorul 3: Componente React, Props și State
- Reconstruirea interfeței utilizatorului prin modularizare în componente React independente (`App`, `Rezumat`, `ListaDestinatii`, `DestinatieCard`, `FormularDestinatie`).
- Gestionarea datelor interactive folosind hook-ul `useState` (starea listei de circuite și a câmpurilor din formular).
- Transmiterea datelor și a funcțiilor de actualizare între componentele părinte și copil prin intermediul `props`.
- Implementarea funcționalităților complete de UI: adăugarea unui circuit nou din formular, marcarea acestuia ca vizitat, ștergerea unui card și randarea condiționată a mesajelor (ex: când calendarul este gol).

---

## 🛠️ Cum se rulează proiectul local

Pentru a rula stadiul curent al proiectului, este necesar Node.js instalat pe sistem. 

1. Deschide terminalul în folderul aplicației:
   
   cd LABTW/app
   Instalează dependențele (necesar doar la prima rulare):

   npm install
   
Pornește aplicația web Vite:

   npm run dev
   
Deschide în browser linkul afișat de Vite (de regulă http://localhost:5173) pentru a interacționa cu interfața React.
