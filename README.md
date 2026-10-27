Citace a využití umělé inteligence

GitHub. (2026). GitHub Copilot [AI asistent ve Visual Studio Code].

Při úpravách projektu CS50 Web – Project 0: Search jsem využil GitHub Copilot jako AI asistenta. Pomohl mi upravit styly formulářové stránky, doplnit navigaci, přidat HTML a CSS validační odznaky a opravit upozornění validátoru. Návrhy jsem následně zapracoval do souborů projektu.

## Zadání pro AI a provedené úpravy

Následující přehled shrnuje moje zadání v této konverzaci. Jejich znění je mírně zkrácené, nejde o doslovný přepis všech zpráv.

1. **Vytvoření stylů formuláře:** Požádal jsem o CSS pro formulář a uložení stylů do `styles.css`. Byly doplněny styly formulářových polí, popisků, výběrů, tlačítek, rozložení formuláře a responzivního zobrazení. Opravil se také odkaz na `styles.css` v `formular.html`.
2. **Navigace k formuláři:** Požádal jsem o odkaz z hlavní Google stránky na formulář. Do navigace v `index.html` byl přidán odkaz na `formular.html`.
3. **CSS validace na všech stránkách:** Požádal jsem o přidání CSS validačního odznaku na každou stránku a nahrazení případného původního odznaku. Odznak byl přidán na všechny čtyři HTML stránky.
4. **Oprava přístupnosti:** Upozornil jsem na chybu validátoru týkající se `aria-label` na elementu `<div>`. K wordmarkům na hlavní a obrázkové stránce byla doplněna sémantická role `img` a odpovídající popisky.
5. **Odstranění lomítek z prázdných elementů:** Požádal jsem o opravu upozornění na koncové lomítko u prázdných elementů. Lomítka byla odstraněna z validačních obrázků.
6. **HTML validace:** Požádal jsem o HTML validaci na všech stránkách. Textové odkazy byly následně nahrazeny grafickým HTML odznakem vedle CSS odznaku.
7. **Použití dodaného HTML odznaku:** Poslal jsem obrázek W3C HTML 4.01 a požádal o jeho použití místo dosavadního HTML odznaku. Obrázek byl nasazen na všech stránkách a odkazuje na HTML validátor dané stránky.
8. **Změna CSS odznaku:** Poslal jsem nový kód CSS validačního odznaku. Původní CSS odkaz a obrázek byly na všech stránkách nahrazeny dodanou variantou.
9. **Citace AI:** Požádal jsem o vytvoření citace AI včetně promptu. Citace v tomto souboru byla upravena tak, aby uváděla GitHub Copilot, a nyní zahrnuje přehled zadání i provedených změn.

Příklady zadání:

> Udělej mi CSS styly na formulář a dej je do `styles.css`.

> Přidej odkaz, abych se z Googlu dostal na formulář.

> Přidej CSS validaci na každou stránku a případnou existující validaci nahraď dodaným odznakem.

> Přidej HTML validaci na všechny stránky, použij grafický odznak vedle CSS odznaku a nahraď jím dosavadní textové odkazy.

> Oprav chybu validátoru přístupnosti u `aria-label` a upozornění na koncové lomítko u prázdných HTML elementů.
