Assigment Veridion

EN:
	I started the assignment by analyzing the data using Excel in order to understand its theme and key information. I compared the values for a   few random domains in each dataset so I could observe the differences using a column that had very specific data.
 	After everything was clear, I used Python’s Pandas library in order to create DataFrames with the provided data. I cleaned everything to make the information easier to read. I removed the columns that I thought contained repetitive information that wouldn’t be used in creating the fourth dataset.
 	Once I was happy with the way each dataset looked, I proceeded with merging them. To ensure a quick and efficient process, I brought the data from the smaller datasets into the larger dataset one by one. I selected 'domain' and 'phone' as the linking columns, the former to target businesses and the latter for cases where a domain has multiple phone numbers. This ensures that the data is merged in more specific cases, retaining all important information. For the same reason, I chose the 'outer' join type to preserve all information and create a dataset with as complete rows as possible.  
    In the end, the columns were ordered and renamed for easier readability, and the final DataFrame was converted into a CSV file.  

    
Mention: The datasets were published without content to ensure protection.  


Notes: By merging the data in this manner, multiple uses of a domain can be observed. 
	For example, ‘atriumhealth.org’ can be linked to two different phone numbers, one ending in ‘150’, the other ending in ‘660’.
	It is important to mention that, depending on the analysis that is being made based on this final set, I would suggest keeping only the data that can be found in the website dataset to avoid any conflicts. 



RO:
Primul pas a constat in analiza datelor folosindu-ma de Excel, pentru a intelege tematica acestora si informatii cheie. Am comparat valorile pentru cateva domenii alese la intamplare in fiecare set de date pentru a putea observa diferentele cu ajutorul uneie coloane cu date foarte specifice.
	Dupa asta, m-am ajutat de libraria Pandas din Python pentru a crea DataFrame-uri cu datele oferite. Am curatat datele pentru a fi cat mai usor de privit in ansamblu. Ulterior, am eliminat coloanele care aveau informatii repetitive si care nu urmau sa fie folosite in crearea celui de al patrulea set de date.
	Odata ce seturile de date au fost curatate, m-am ocupat de fuziunea acestora. Pentru ca procesul sa fie rapid si eficient, am adus informatiile din seturile de date mai mici in setul de date mai mare pe rand. Drept coloane de legatura am ales ‘domain’ si ‘phone’, prima pentru a tinti afacerile, iar a doua pentru cazurile in care un domain are mai multe numere de telefon. Astfel se asigura ca informatiile sunt imbinate in cazuri cat mai particulare si see pastreaza toate datele importante. Din acelasi motiv tipul de fuziune ales a fost ‘outer’ pentru a se pastra toate informatiile si pentru a se obtine un set de date cu randuri cat mai complete. 
	In final, coloanele au fost ordonate si redenumite pentru a fi usor de citit si dataframe-ul final a fost convertit in csv.
	
 
Mentiune: Seturile de date au fost publicate fara continut pentru a ma asigura ca acestea sunt protejate.


Observatii: Prin modul in care au fost unite datele se pot observa mai multe intrebuintari ale unui domeniu.
	De asemenea, domeniului ‘brunet.ca’ ii pot fi asociate doua numere de telefon, unul care se termina in ‘441’, celalalt care se termina in ‘456’.
	E important de mentionat faptul ca, in functie de analiza realizata pe baza setului de date final, se pot pastra doar datele comune cu cele din setul de date initial website pentru a se evita eventualele conflicte.
