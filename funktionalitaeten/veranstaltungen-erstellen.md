# Události

![](../.gitbook/assets/gitbook_news_750x320.jpg)

Programem, který se v [konferenční místnosti](rooms/) koná, jsou události. Ty mohou probíhat v různých místnostech, ale mohou se konat i souběžně v jedné a té samé místnosti. Například v místnosti typu kavárna může být umístěno vícero virtuálních kavárenských stolků a v jedné seminární místnosti se mohou konat dva workshopy zároveň. Vše je kvalitně virtuálně odhlučneno, takže se vzájemně rušit nebudete, slibujeme😉. 

Události jsou obvykle spojeny s funkcí videa. Nelze je však vytvořit v úplně všech [typech místností](rooms/#raumtyp) \(typem místnosti je totiž i seznam účastníků a tzv. výsledková místnost, ve kterých se v podstatě nic neděje\). V místnosti typu lobby události vytvářet můžete, ty ale slouží jen k vyplnění prostoru a nemají funkci videa \(lze je tedy využít například pro účely pauzy v průběhu konference\).

### Přidávání nových událostí

{% hint style="warning" %}
Než vytvoříte událost, musíte mít [založenou místnost](rooms/).
{% endhint %}

Novou událost lze založit dvěma způsoby. Pokud právě zakládáte konferenci, nacházíte se pravděpodobně na [správcovské stránce](admin-page.md). Odtud přejděte na záložku **Správa místností**. 

Tam na pravé straně uvidíte již vytvořené místnosti v pořadí podle jejich číslování. U každé položky můžete kliknutím na šipku vpravo otevřít rozbalovací menu, ve kterém máte možnost upravit či smazat stávající událost nebo vytvořit novou.

Druhá možnost je k dispozici přímo v [náhledu konference](uebersicht/tagungsansicht.md). Jako správci se vám v místnosti pod popisem místnosti zobrazuje tlačítko pro přidání nové akce. Kromě toho zde můžete upravovat a mazat již vytvořené události. Níže naleznete krátký popis toho, co můžete při zakládání nových událostí nastavit. Stejně jako u místností lze všechna nastavení upravovat i dodatečně.

### Nastavení události

#### Název

Název by měl co nevýstižněji odrážet obsah události – alespoň pokud se jedná o událost v seminární místnosti. V kavárně můžete „stolky“ samozřejmě pojmenovat libovolně. Událost se tak může jmenovat například _Přednáška paní Novákové o česko-německých vztazích_ nebo _Skupinová diskuze o demokracii v online prostředí_ apod. Volba je pouze na vás.

#### Přestávka jako událost \(volitelné\)

Jako událost můžete zadat i přestávku. V takovém případě je událost bez videofunkce a slouží pouze jako „vycpávka“. Nazvat ji tedy můžete například jako „polední přestávku“.

#### Datum a čas

Zde události přiřazujete konkrétní dobu. Podle data a času konání se události v rámci konference třídí a seskupují do záložek podle jednotlivých dnů. Aktuálně probíhající události jsou pro účastníky vždy zvýrazněné.

#### Popis \(volitelné\)

V popisu události můžete stručně shrnout její obsah. Popis se pak zobrazí v programu a také u názvu události v dané místnosti. Pro tyto účely je však vhodnější využít [popis místnosti](rooms/#beschreibung), protože v přehledu událostí je málo prostoru pro delší texty.

#### Přednášející / referent / moderátor \(volitelné\)

Událostí se často účastní jeden nebo více přednášejících a/nebo moderátorů. Ti v rámci videokonference někdy potřebují rozšířená práva – např. pro sdílení obrazovky, správu účastníků, vytváření skupinových místností \(„breakout rooms“\) nebo spouštění anket. V nastavení události jim můžete rozšířená práva pro účely dané události udělit tak, že zadáte jejich jména do určeného pole a následně je vyberte z nabízeného menu.

{% hint style="info" %}
Rozšířená práva vybraných osob budou platit pouze pro konkrétní videokonferenci zvolené události. Pokud chcete určit více správců v rámci celé konference, můžete tak učinit ve [správě účastníků](teilnehmendenmanagement/). Správci konference získávají rozšířená práva automaticky pro všechny videokonference.
{% endhint %}

#### Nahrání prezentace \(volitelné\)

DINA nabízí praktickou možnost nahrát do události již před jejím začátkem prezentaci, která se při videokonferenci zobrazí účastníkům a kterou si případně mohou i stáhnout. Podporovány jsou PDF, obrázky a formáty běžných kancelářských souborů. Přednášející a správci mohou prezentace nahrávat i v průběhu videokonference.

{% hint style="warning" %}
BigBlueButton nahrané soubory pro účely zobrazení zkonvertuje do formátu PDF, takže se v powerpointových prezentacích ztratí animace a přechody. Ale žádný strach, prezentaci s animacemi můžete promítnout pomocí funkce sdílení obrazovky😊.
{% endhint %}

Jakmile vyplníte všechna povinná pole, můžete událost uložit. Tím se okamžitě zobrazí v náhledu konference v příslušné místnosti.

### Úprava události

Dodatečně změnit nastavení události \(např. název, čas nebo osobu přednášejícího\) není vůbec žádný problém. Máte opět dvě možnosti:

Z náhledu konference vstupte do místnosti, ve které se událost koná \(či konala, nebo teprve konat bude\). Vpravo uvidíte malý symbol tužky, přes který se dostanete na stránku s nastaveními.

Pokud jste na správcovské stránce, klikněte na záložku „Správa událostí konference“. Stačí vybrat příslušnou událost a dostanete se na stránku s jejími nastaveními.

### Smazání události

Událost můžete smazat podobným způsobem jako ji upravit. Z [náhledu konference](uebersicht/tagungsansicht.md) vstupte do místnosti, ve které se událost koná \(či konala, nebo teprve konat bude\). Vpravo uvidíte malý symbol popelnice, jehož pomocí můžete událost smazat.

Pokud jste na [správcovské stránce](admin-page.md), klikněte na záložku „Správa událostí konference“. Tady jen rozklikněte rozbalovací menu u události, kterou chcete smazat, a zobrazí se vám tlačítko pro její smazání.

{% hint style="danger" %}
Odstranění události je nevratné, proto si dobře rozmyslete, zda ji nechcete pouze upravit.
{% endhint %}

