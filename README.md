# City Explorer - F1 Edition

Proiect de semestru realizat în cadrul disciplinei Tehnologii Web. 

Acest repository prezintă evoluția unei aplicații web, pornind de la o machetă statică (HTML/CSS) și progresând către o aplicație modernă folosind **Vite**, **React** și **JavaScript ES6+**. Tematica aplicației este axată pe destinații turistice din calendarul competițional Formula 1.

**Autor:** Rosu Gabriel-Christopher

---

## 🏎️ Stadiul Proiectului

### Laboratorul 1: Macheta Statică
* Crearea scheletului semantic folosind HTML5.
* Implementarea unui layout responsiv modern utilizând CSS Grid (pentru cardurile cu circuite) și Flexbox (pentru zona de navigare).
* Stilizarea formularelor și implementarea efectelor vizuale avansate.

### Laboratorul 2: Vite și JavaScript Modern
* Migrarea proiectului către un mediu de dezvoltare susținut de **Vite** și instalarea dependențelor cu `npm`.
* Decuplarea logicii în module separate (`data`, `utils`, `api`).
* Prelucrarea datelor folosind funcții JavaScript pure (`map`, `filter`, `reduce`), respectând principiul imutabilității datelor.
* Implementarea cererilor asincrone (`async/await`, `fetch`) către un API public (`jsonplaceholder`).
* *Notă:* În această etapă, interfața grafică este temporar ascunsă (afișând doar titlul), logica și rezultatele fiind testate și vizualizate exclusiv în **consola browserului**.

---

## 🛠️ Cum se rulează proiectul local (Laboratorul 2)

Pentru a rula stadiul curent al proiectului, este necesar Node.js.

1. Deschide terminalul în folderul `app`.
2. Instalează dependențele:
   ```bash
   npm install
