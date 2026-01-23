ANALIZA NIVOA PRIZEMNOG OZONA
(HOUSTON–GALVESTON–BRAZORIA, 1998–2004)

Projekat analizira podatke nivoa prizemnog ozona na području Teksasa, SAD. Cilj analize je ispitivanje odnosa između koncentracije ozona i meteoroloških parametara (temperatura, vetar, pritisak, vlažnost), kako bi se identifikovali faktori koji prouzrokuju povišene nivoe ozona u vazduhu. Projekat obuhvata pripremu i obradu podataka, kao i njihovu analizu primenom klasičnih statističkih metoda, mašinskog učenja i neuronskih mreža.

PODACI

Korišćeni podaci:

- koncentracija ozona (jednočasovni maksimum),
- meteorološki parametri (temperatura, brzina vetra, pritisak, vlažnost itd.).

Ciljna promenljiva je binarna i označava da li je došlo do prekoračenja dozvoljenog ozonskog praga.
Podaci su prethodno očišćeni i pripremljeni za analizu.

METODOLOGIJA

1. EKSPLORATIVNA ANALIZA PODATAKA

- analiza raspodele promenljivih,
- distribucija temperature tokom meseci,
- odnos temperature i vetra i njihova korelacija

2. STATISTIČKA ANALIZA

- test normalnosti (Shapiro–Wilk),
- neparametarski test (Mann–Whitney),
- analiza autokorelacije (ACF / PACF),
- dekompozicija vremenske serije,
- test stacionarnosti (ADF test).

3. REDUKCIJA DIMENZIONALNOSTI

- primena PCA na meteorološke parametre temperature i brzine vetra.

4. MODELI MAŠINSKOG UČENJA I NEURONSKA MREŽA

- Logistic Regression,
- Support Vector Machine (SVM),
- Decision Tree,
- Perceptron,
- Multilayer perceptron (MLP)

Evaluacija modela:

- accuracy, precision, recall, F1-score
- ROC i AUC


REZULTATI

- temperatura i brzina vetra pokazuju značajnu povezanost sa povišenim nivoom ozona,
- izraženi su sezonski obrasci, naročito u letnjem periodu,
- modeli postižu slične rezultate, pri čemu su performanse ograničene zbog neuravnoteženih klasa(mala količina podataka sa povišenim nivoom ozona).