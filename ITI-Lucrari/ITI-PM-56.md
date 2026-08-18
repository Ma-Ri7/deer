**ITI - PM -56**

1. **Denumirea lucrării**: Probe, verificări, revizii și remedieri ale deranjamentelor în instalațiile de teleconducere (SCADA)

Prezenta instrucțiune reglementează modul de executare a probelor, verificărilor, reviziilor și a remedierilor de deranjamente în instalațiile de teleconducere (SCADA) aferente stațiilor electrice de transformare.

Ele se referă atât la echipamentele de la punctele centrale de comandă (dispecer, ture pentru exploatarea centralizată a mai multor stații de transformare, ture la subunitatea de exploatare pentru rețelele electrice de distribuție sau de comandă din stații cu personal permanent de exploatare) cât și la echipamentele SCADA montate în stațiile electrice de transformare.

În conformitate cu acest ITI-PM, se pot executa următoarele lucrări:

a) Revizia tehnică a dulapurilor SCADA (RTU), a stațiilor de lucru de tip PC conectate la RTU (unde este cazul), a echipamentelor de achiziție de date (de tip SAITEL sau altele), împreună cu sursele de alimentare ale acestora și cu releele de execuție și semnalizare conectate la acestea.

b) Revizia tehnică a echipamentelor de comunicație (modemuri, media convertoare, switch-uri) prin intermediul cărora RTU-ul comunica cu echipamentele de achiziție (SAITEL), cu releele digitale de protecție, cu aparatele inteligente de măsură (ION 6200, ION 8800, etc.), împreună cu sursele de alimentare ale acestora și suportul de comunicație utilizat (cablu serial, cablu ethernet, fibra optică, etc.).

c) Revizia tehnică a transformatorilor de curent, tensiune, putere, etc., împreună cu sursele de alimentare ale acestora.

d) Montarea și demontarea aparatelor de măsură (ampermetre, voltmetre, ION 6200, ION 8800, etc.), a releelelor (de timp și intermediare), a transformatorilor și a modulelor (cartelelor) care alcătuiesc echipamentele de teleconducere și de comunicație montate în stație.

e) Revizia tehnică a serverelor SCADA, ale calculatoarelor de comunicație (Front-End), ale switchurilor și ale celorlalte echipamente de comunicație (modemuri, media convertoare) montate la punctul central de teleconducere, care asigură comunicația cu echipamentele SCADA din stațiile de transformare (RTU) și cu stațiile de lucru ale dispecerilor și ale celorlalți utilizatori, împreună cu sursele de alimentare ale acestora.

f) Revizia tehnică a stațiilor de lucru SCADA montate la dispeceri și la ceilalți utilizatori.

g) Revizia tehnică a echipamentelor de electroalimentare (UPS-uri, invertoare, etc.) montate la punctul central de teleconducere.

h) Inlocuirea unor module sau inlocuirea completă a unor echipamente în cazul remedierii defecțiunilor.

i) Montarea de echipamente și module noi în vederea extinderii sau modernizării.

1. **Condițiile în care lucrarea se poate executa pe baza acestei forme organizatorice**:

Lucrările care fac obiectul prezentului ITI-PM se execută fără scoaterea de sub tensiune, respectându-se măsurile tehnice specifice metodei de lucru sub tensiune, în contact.

Formația nu are acces la circuitele primare de înaltă tensiune ale instalațiilor aflate sub tensiune.

Lucrările la instalațiile de teleconducere, care impun apropierea față de instalațiile primare aflate sub tensiune, la distanțe mai mici decât cele de vecinătate, se vor executa pe baza unei autorizații de lucru, cu scoaterea de sub tensiune a instalațiilor primare.

Lucrările se execută de către personalul de întreținere și reparații specializat în lucrări în instalațiile de teleconducere din formațiile centrului PRAM, care să fie examinat cu privire la cunoștințele necesare care se referă la prevederile de securitate a muncii specifice lucrării și să aibă mențiunea în fișa de examinare pentru autorizare **"execută lucrări pe bază de ITI-PM"**.

Lucrările se execută în instalațiile interioare, la sol.

1. **Formația minimă de lucru**:

- 2 electricieni (sau personal tehnic) având minim grupa a III-a și respectiv a I-a de autorizare.

Șeful de lucrare poate cumula și funcția de admitent pentru instalațiile fără personal de servire operativă, dacă deține grupa de autorizare corespunzătoare (minim IV).

În cazul în care se lucrează simultan în două puncte de lucru diferite, formația va cuprinde minim 3 persoane. Persoana care lucrează independent va avea minim grupa a IV-a de autorizare, având preoghativele șefului de lucrare.

1. **Măsurile tehnice de securitate a muncii specifice lucrării**:

- **Identificarea instalației (zonei) la care urmează a se lucra** — răspunde șeful de lucrare;
- **Delimitarea materială a zonei de lucru și montarea indicatoarelor de securitate** — răspunde admitentul;
- **Luarea măsurilor pentru evitarea accidentelor de natură neelectrică** — răspunde șeful de lucrare.

La executarea lucrărilor în instalațiile de teleconducere, pe baza prezentei ITI-PM, se impun următoarele restricții:

- Se interzice ridicarea sau depășirea îngrădirilor — răspunde șeful de lucrare;
- Personalul executant să se asigure că, în spate sau în părțile laterale, nu sunt elemente de instalații aflate sub tensiune neîngrădite, astfel încât să existe suficient spațiu pentru efectuarea mișcărilor necesare, în condiții de securitate — răspund: șeful de lucrare și membrii formației de lucru;
- Dacă lucrările se execută în condiții de vizibilitate redusă, la locul de muncă se va asigura un iluminat corespunzător — răspunde șeful de lucrare;
- Se va urmări ca transformatorii de curent să nu rămână cu secundarul deschis (în gol) — răspunde șeful de lucrare.

În instalații electrice fără supraveghere se interzice admiterea la lucru în baza ITI-PM, dacă în instalația separată electric lucrează concomitent și alte formații de lucru.

1. **Mijloacele de producție necesare la executarea lucrării**:

a) **Echipamente și dispozitive de lucru**:

- scule electroizolante;
- detector de joasă tensiune;
- degetare electroizolante;
- truse cu aparate de măsură și control, specifice operațiilor ce urmează a se executa;
- laptop.

b) **Echipament individual de protecție**:

- salopetă din fibre de bumbac;
- casca de protecție a capului, cu viziera de protecție a feței;
- mănuși electroizolante;
- încălțăminte electroizolantă sau covor electroizolant;
- degetare electroizolante.

1. **Succesiunea operațiilor tehnologice**:

a. Se iau măsurile organizatorice din IP — 65 în vigoare, cap. 3.2.3.  
b. Se iau și se respectă măsurile tehnice conform punctului 4.  
c. Se echipă personalul executant cu mijloacele de protecție necesare — răspund: șeful de lucrare și membrii formației de lucru.  
d. Șeful de lucrare, înainte de a începe lucrarea, va efectua un instruire membrilor formației de lucru asupra conținutul lucrărilor pe baza FT sau ITL, asupra limitelor zonei de lucru, a instalațiilor sub tensiune din vecinătate, inclusiv asupra măsurilor de securitate a muncii de natură neelectrică.  
e. Se execută lucrările de probe, verificări, revizii sau remedieri ale deranjamentelor în instalațiile de telemecanică, astfel:

- se verifică existența tensiunilor de alimentare și corectitudinea interconexiunilor;
- se urmărește pe interfața utilizator indicațiile referitoare la starea de funcționare a echipamentelor;
- se lansează programe de testare a modulelor echipamentelor (unde este cazul);
- se verifică comunicația;
- se verifică interfața cu procesul;
- se înlocuiesc componentele, modulele, echipamentele găsite defecte, după care se verifică din nou buna funcționare a acestora.

f. Se consemnează rezultatele probelor și verificărilor efectuate, în vederea elaborării (dacă este cazul) a buletinelor de încercări — răspunde șeful de lucrare.  
g. Se strâng sculele, dispozitivele și aparatele folosite la lucrări, prin grija șefului de lucrare.  
h. Se revine la situația normală a instalațiilor de teleconducere — răspunde șeful de lucrare.  
i. Se comunică la sediul subunității de exploatare și la treapta de conducere operativă încheierea lucrărilor.

**Pentru executarea probelor, verificărilor, reviziilor și remedierilor de deranjamente în instalațiile de teleconducere, se fac următoarele precizări**:

În Stațiile electrice de transformare fără personal de servire operativă, lucrările de revizii tehnice periodice și verificări ale echipamentelor de teleconducere se vor face, pe cât posibil, fără deconectarea lor și fără întreruperea legăturii de comunicație cu punctul central de comandă.

Atunci când anumite operații din cadrul reviziilor tehnice necesită oprirea echipamentului sau întreruperea legăturii de comunicație cu punctul central, precum și în cazul remedierii unor defecțiuni, șeful de lucrare are obligația de a anunța **telefonic dispecerii de la punctele de comandă** durata aproximativă a întreruperii legăturii, iar acesta va decide dacă este sau nu necesară prezența în stație a turei de intervenție.

Circuitele de tensiune se vor întrerupe prin scoaterea blocului de încercare, numai pentru aparatele ce urmează a fi verificate. În cazul în care nu există bloc de încercare, întreruperea se va face prin scoaterea conductoarelor către aparat din șirul de cleme, după ce acesta au fost identificate cu certitudine.

Conductoarele scoase din șirul de cleme se vor îndepărta imediat din cleme și între ele, prin deformarea capetelelor, apoi, după verificarea lipsei tensiunii (cu voltmetrul sau detectorul de tensiune), se vor scoate conductoarele de la bornele aparatului.

Se interzice acționarea telecomenzilor întrerupătorilor, separatoarelor, AAR-urilor și RATTurilor.

După efectuarea reviziilor la echipamentele de telemecanică, probele pe viu ale funcționării acestora se vor efectua numai de către personalul operativ al treptei de conducere operativă, la cererea personalului PRAM și a personalului operativ.

**Executanții sunt răspunzători în mod solidar pentru nerespectarea de către oricare dintre ei sau de către șeful de lucrare, a reglementărilor în vigoare, în cadrul lucrării la care participă dacă nu intervin pentru a preveni sau opri nerespectarea acestora.**

**ITI - PM se va afla tot timpul asupra șefului de lucrare.**