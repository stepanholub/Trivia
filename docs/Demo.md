---
layout: default
title: "My Page Title"
---

### Záměr 
- Referenční bod pro obor Obecná matematika

- Pojmy, které se 
    - objevují paralelně v různých předmětech 
    - neřeknou nikdy pořádně a studenti se je učí za pochodu

- Umožnit 
   - studentům si zmínky o základních pojmech propojit

    - vyučujícím se na tento zdroj odkázat

- Nejde o to odtranit případné rozdíly, ale 
   
   - upozornit na ně
   
   - vysvětlit, kdy jsou jen zdánlivé/notační, a kdy věcné
   
   - naznčit důvod rozdílů 
   
   - vysvětlit, jak s rozdíly pracovat
 - Obsah by tedy měl být tak široký a liberální, aby umožňoval přístupy všech přednášejících.   

# Pojmy

### Přirozená čísla

Čísla označující počet, značíme $\mathbb N$. 

Na tom, zda je nula přirozené číslo, nepanuje mezi matematiky shoda.
Obě možnosti mají své výhody i nevýhody. 
Tuto dvojznačnost lze řešit explicitním označením $\mathbb N_0$, resp. $\mathbb N_+$. 

Každý matematik (i přednášející), tedy musí ohlásit, zda slovy "přirozená čísla" (a symbolem $\mathbb N$) označuje množinu:
- $\{0,1,2,3,4,5,6,7,8,9,\dots\}$,

nebo
- $\{1,2,3,4,5,6,7,8,\dots\}$.

Přirozená čísla patří mezi nejzákladnější a nejvíce intuitivní matematické objekty, se kterými se setkáváme v útlém dětství. Na tuto intuici se odkazují tři tečky v zápise, což pro většinu bežných situací stačí.

Jako u všech základních pojmů je ovšem přesné vymezení přirozených čísel obtížný až nemožný úkol na pomezí matematiky a filosofie.

### Zobrazení

Zobrazení je klíčový matematický pojem. Jak naznačuje jeho jméno, zachycuje _přiřazení_ nějakého _obrazu_ nějakému _vzoru_, případně proces _transformace_ nějakého _vstupu_ na nějaký _výstup_.

Intuitivní povaha zobrazení vede k používání celé řady dalších neformálních výrazů: zobrazení něco "vrací", "posílá" vstup na výstup, apod. 

Někdy se pro pojem zobrazení používá jako synonymum termín _funkce_, někdy je termín "funkce" vyhrazen jen některým zobrazením.

Existují dva přístupy k zobrazení:
1. zobrazení je primitivní, tedy dále nedefinovaný pojem; jeho matematická povaha je pak dána symbolem, např. $f$, který se chová tak, že pro objekt $a$ vhodného typu označuje zápis $f(a)$ nějaký (obecně) jiný objekt (obecně) jiného typu;  
2. zobrazení je jistý druh _relace_, tedy podmnožina kartézského součinu $A\times B$, tedy množina uspořádáných dvojic $(a,b)$, kde je $a$ vzor, a $b$ jeho obraz. Aby byla relace zobrazením, musí pro každé $a$ existovat nejvýše jedno $b$, které s ním je v dané relaci. (Pokud neexistuje žádné takové $b$, není zobrazení na $a$ definováno.)

Důvody pro přijetí prvního (říkejme mu dále _funkčního_) přístupu, nebo druhého, _množinového_ přístupu jsou dány osobním vkusem, užitečností v daném oboru, ale také (filosofickými) otázkami základů matematiky (totiž zda je primitivním pojmem spíše zobrazení, nebo spíše množina).

Oba přístupy jsou na sebe v praxi každopádně snadno převoditelné:
- první přístup umožňuje reprezentovat zobrazení jako množinu dvojic $(a,f(a))$;
- přístup vycházející z množin také obvykle používá značení $f(a) = b$, nikoli $(a,b) \in f$.

Rozdíly mezi matematiky (i vyučujícími) se (kromě preference pro jedno z uvedených pojetí) mohou týkat konvencí ohledně terminologie a značení.

- Množiny $A$ a $B$, kde $A$ je množina (možných) vzorů a $B$ je množina možných obrazů, mohou, ale nemusí být považovány za součást definice zobrazení. 
     - Např. zobrazení přiřazující reálným číslům jejich druhou mocninu se "chová stejně" nezávisle na tom, zda množina $B$ jsou všechna reálná čísla, nebo jen nezáporná reálná čísla. Záleží tedy na konvenci, zda jsou tato dvě zobrazení považována za stejná (v případě množinového přístupu se to nabízí), nebo za různá (to je obvyklejší u funkčního pohledu).   

 - Záleží na konvenci, zda zobrazení musí být definované na všech prvcích $A$.
      - V množinovém pojetí výše bylo připuštěno, aby funkce na nějakých prvcích $A$ nebyla definovaná. Pak se mluví o "zobrazení _z_ množiny $A$ do množiny $B$". Ve funkčním pojetí se pak obvykle mluví o _částečných_ zobrazeních (v tomto případě častěji "částečných funkcích").   
      - Ve funkčním pojetí se obvykle požaduje, aby bylo zobrazení definované na všech prvcích $A$. V množinovém pojetí se to vyjadřuje vypouštením předložky "z" a mluví se o "zobrazení množiny $A$ do množiny $B$". Téměř bez výjímky platí, že zápis $$f: A \to B$$ označuje, že $f$ je definováno na celém $A$.  



 V každém případě se termínem _definiční obor_ označuje množina prvků, na kterých zobrazení definováno je. 

 _Oborem hodnot_ se stejně tak vždy označuje množina prvků z $B$, které jsou obrazem nějakého prvku z $A$. Matematici se tedy shodnou, že oborem hodnot nemusí být celé $B$.

Celá množina $B$ nemá v češtině zavedené jméno. V angličtině se používá termín _codomain_.

Je-li oborem hodnot celé $B$, nazývá se zobrazení _surjektivní_ nebo mluvíme o _zobrazení na_. (Tato formulace působí v češtině dojmem nedokončené věty, proto se často dává slovo "na" do uvozovek.)

Nic nebrání tomu, aby se dva různé prvky definičního oboru zobrazovaly na stejný obraz. Pokud se to nestane, říkáme, že je zobrazení _prosté_ či _injektivní_.

Zobraazení, které je prosté a "na", se nazývá _vzýjemně jednoznačné_ čili _bijektivní_ (neboli _bijekce_).

Rovnost $f(a) = b$ často zapisujeme jako
  $$f: a \mapsto b, $$
  což je třeba odlišovat od $f: A \to B$. Jedná se o jiný typ šipky. Záppis $f: a \to b$, by tedy znamenal, že $a$, $b$ jsou množiny (které z nějakých důvodů označujeme neobvyklými malými písmeny).

_Obraz podmnožiny definičního oboru_

 Pojem _obrazu_ zobrazení $f: A \to B$, či  $f \subseteq A \times B$, se rozšiřuje i na podmnožiny definičního oboru. Je-li tedy $M\subseteq A$ píšeme    
 $$ f(M) = \{b \in B \mid \exists a \in A. f(a) = b \} = \{f(a) \mid a \in M\}.$$
Jedná se tedy o množinu obrazů všech prvků z $A$. Toto značení i termín obraz je tedy dvojznačné, a je typickým příkladem tzv. "zneužití značení". To je situace, kdy používáme nějaké značení formálně nesprávně, ale věříme, že to nejen nepovede k nedorozumění, ale dokonce to pomůže vyjádřit skutečný záměr.

Skutečně platí, že pokud je jasné, že $f$ je definované na $A$ a že $M$ je podmnožina $A$ (což naznačuje velké písmeno), je asi také jasné, co rozumíme obrazem takové množiny. Přesto se někdy používá pro rozlišení značení $f[M]$, namísto $f(M)$.

_Inverzní zobrazení_

Je-li $f: A \to B$ bijekce, definujeme pro ně _inverzní zobrazení_ $f^{-1}: B \to A$ tak, že prvek $b \in B$ zobrazíme na ten jediný prvek $a$, pro který platí $f(a) = b$. 

_Vxor podmnožiny codomainu_

Vzor můžeme, podobně jako obraz, definovat také pro libovolnou podmnožinu codomainu $B$. I v tomto případě obvykle zneužíváme notaci a vzor množiny $K \subseteq B$ značíme také $f^{-1}(K)$. 

Zatímco inverzní zobrazení je definováno pouze pro bijekci, vzor podmnožiny je definován vždy a lze ho zapsat jako
$$f^{-1}(K) = \{a \in A \mid \exists b \in K. f(a) = b \} = \bigcup _{b \in K} \{a \in A \mid f(a) = b\}.$$

Rozdíl mezi inverzním zobrazením a vzorem je dobře vidět na jednoprvkové podmnožině. Zatímco pro $b\in B$ je $f^{-1}(b)$ definováno jen pro bijekci, je $f^{-1}(\{b\})$ definováno vždy. Pokud $b$ neleží v definičním oboru $f$, je $f^{-1}(\{b\}) = \emptyset$ (prázdná množina). 

Značení svádí k tomu, aby se namísto $f^{-1}(\{b\})$ psalo $f^{-1}(b)$. To už ovšem vede k nepříjemným dvojznačnostem a je lepší se tomu vyhnout.

Značení $f^{-1}$ je nebezpečné i v jiném smyslu. V případech, kdy na definičním oboru je definován inverz prvků, je třeba rozlišovat mezi inverzním zobrazením $f^{-1}$ a zobrazením
$$ x \mapsto f(x)^{-1}.$$
Možná zmatení ilustrujme na zobrazení sinus, tedy 
$$\sin: \mathbb R \to \mathbb R.$$
- inverzní zobrazení $\sin^{-1}$ ve zde definovaném smyslu zobrazuje např. prvek $0$ na množinu 
$$\{k \pi \mid k\in \mathbb Z\}$$
- zápisem $\sin^{-1} x$ nicméně obvykle míníme 
$$\frac 1 {\sin x}$$
- ještě jiným kandidátem na inverzní funkci je $\arcsin$

_Třídová zobrazení_

Problematický může být fakt, že zobrazení může působit na souborech objektů, které dohromady netvoří množinu (ale tzv. vlastní třídu, proto hovoříme o "třídových zobrazeních"). Příkladem je otázka, zda chceme za zobrazení považovat operaci _potence_
$$A \mapsto \mathcal P (A),$$
která je definovaná na vlastní třídě všech množin.
