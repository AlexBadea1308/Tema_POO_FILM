FireFoxStudios
the place where stories transform into movies

Sala de cinema este plină și întreaga audiență așteaptă să vadă unul dintre cele mai recente filme lansate. Printre cei din audiență, te numeri și tu, care aștepți cu nerăbdare să vezi produsul obținut în urma folosirii aplicației dezvoltate cu câteva luni în urmă. După o serie de previzualizări ale unor producții care vor urma să fie lansate în viitorul apropiat, noul film începe, iar sub titlul acestuia este afișat mesajul “Produced by FireFoxStudios”. Acest lucru îți aduce aminte de momentul în care ai început să lucrezi pentru prima dată la aplicația de producție a filmelor, folosită de FireFoxStudios, și a cerințelor pe care le-ai primit de la aceștia.

Propunerea lor ți se păruse puțin ciudată la început, însă, după ce ai analizat cerințele primite, ai putut identifica o soluție. Fluxul principal al aplicației implică transformarea unei Povești într-un Film, prin parcurgerea următoarelor etape:

citirea Poveștii dintr-un fișier și organizarea acesteia într-un Scenariu, reprezentând o colecție de Scene și un Fir narativ. Povestea este furnizată sub forma unui text care conține personajele principale și atributele lor, precum și o serie de acțiuni și dialoguri sau descrieri de peisaje;
completarea scenelor cu elemente adiționale pentru îmbogățirea scenariului;
crearea Filmului, prin rearanjarea scenelor în funcție de firul narativ și prezentarea acestuia de către Director, prin afișarea în consolă.
Există o serie de roluri pe care le au persoanele implicate în producerea filmului:

Scenaristul primește Povestea și creează Scenariul, prin adăugarea unor adnotări care să permită stabilirea elementelor specifice fiecărei Scene. De exemplu, o scenă poate fi considerată fie o imagine statică în care sunt prezente mai multe personaje, fie o imagine dinamică care cuprinde un dialog dintre cel puțin două personaje. Totodată, Scenaristul va marca personajele între care are loc un dialog și va adnota fiecare replică, asignând-o unui anumit personaj.
Regizorul primește Scenariul și va lucra cu colecția de scene. Mai exact:
pentru scenariu regizorul va asigna Actori dintr-o listă de actori (fiecare actor va avea predefinită o stare de spirit și un tip - Principal sau Figurant);
pentru fiecare scenă regizorul va:
adăuga un cadru specific compus din o serie de informații despre mediul înconjurător, alese aleator dintr-o colecție de elemente naturale (copaci, arbuști, flori, etc.), momentul din zi (răsărit, dimineață, prânz, amurg, noapte, etc.), starea vremii (ploaie, ceață, soare, ninsoare, etc.).
defini replicile aferente fiecărui personaj, prin identificarea vorbitorilor pe baza adnotărilor făcute de Scenarist;
stabili gradul de compatibilitate dintre aceștia, la nivelul Scenei, pe baza următoarei formule: [ ∑ (StareSpiritActori) * 0.5 ] / NumărPersonajeÎnScenă;
va solicita Producătorului generarea unor EfecteSpeciale.
Producătorul va genera EfecteSpeciale, la solicitarea Regizorului. Aceste EfecteSpeciale vor fi de 2 tipuri (Vizuale și Sonore) și vor fi generate în funcție de gradul de compatibilitate dintre actori și starea vremii. De exemplu: pentru gradul de compatibilitate <2.5 și ploaie, vor fi generate Fulger și Tunet ca efecte speciale vizual, respectiv sonor.
Directorul va primi Scenariul și va realiza Filmul, prin rearanjarea Scenelor în ordinea dictată de FirulNarativ. La final, Directorul va putea reda Filmul, prin afișarea informațiilor specifice (Scene, FirNarativ, etc.).
Pentru administrarea fișierelor, ai creat un nivel intermediar care administra toate fișierele aferente procesului de creare a filmului și expunea metode prin care să poată fi adăugate, căutate, modificate sau șterse informații din acestea.

Informațiile suplimentare pe care le-ai avut la dispoziție:

Actorii sunt de 2 tipuri: Principali și Figuranți. Toți actorii au un nume, un tip de personaj și o stare de spirit, care se va actualiza în funcție de tipul personajului pe care îl va avea asignat de către Regizor (va crește cu 25% dacă actorul figurant primește un personaj principal sau va scădea cu 25% dacă actorul principal primește un personaj figurant).
Personajele principale sunt primele 3 personaje cele mai des întâlnite în poveste.
Scenaristul, regizorul, producătorul și directorul sunt toți angajați ai entității unice FireFoxStudios și au un nume și un cod de identificare. De asemenea, aceștia vor avea metode specifice și comune, care să le permită să realizeze activitățile menționate anterior în cerințe.
Toate listele menționate în cerințe au valori predefinite, însă pot fi actualizate ulterior de către regizor (listele cu actori) și producător (listele cu efectele speciale).
Ai putut defini tu formatul fișierului cu Povestea, astfel încât să îți fie facil de parsat și adnotat în timpul execuției rolului de Scenarist.
Scenele sunt identificate prin paragrafe (scene statice) sau secvențe neîntrerupte de dialog (scene dinamice). În cazul scenelor dinamice, se va avea în vedere propoziția anterioară dialogului, în care vor fi menționate personajele participante în cadrul dialogului. Fiecare replică dintr-un dialog este precedată de caracterul “-”.
Vor fi stocate în fișiere distincte toate rezultatele etapelor prin care va trece Povestea până la transformarea în Film. Suplimentar, se vor expune metode prin care să se poată afișa aceste etape.

Update 1
Adăugăm câteva informații suplimentare referitoare la anumite elemente ale temei:

Personajele din poveste vor fi identificate pornind de la faptul că vor avea nume proprii, prin urmare vor fi scrise cu literă mare, chiar dacă sunt poziționate în interiorul unei propoziții/fraze. Ulterior, pentru identificarea corectă a numărului de apariții ale acestor nume în textul poveștii și stabilirea corectă a calității de personaj principal sau figurant, se vor verifica și aparițiile acestora a început de propoziție/frază.
Fișierul de intrare, care conține povestea, poate avea un format definit de voi, însă am dori ca acesta să fie cât mai apropiat de cum arată o poveste reală. De exemplu, să aveți ca input un capitol dintr-un roman, la care mai adăugați câteva elemente.
