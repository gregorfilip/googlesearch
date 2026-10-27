Citace a využití umělé inteligence

GitHub. (2026). GitHub Copilot [AI asistent ve Visual Studio Code].

Při úpravách projektu CS50 Web – Project 0: Search jsem využil GitHub Copilot jako AI asistenta. Pomohl mi upravit styly formulářové stránky, doplnit navigaci, přidat HTML a CSS validační odznaky a opravit upozornění validátoru. Návrhy jsem následně zapracoval do souborů projektu.

## Prompty a provedené úpravy

Níže jsou v chronologickém pořadí uvedena všechna zadání z této konverzace, včetně dodaných kódů a chybových hlášení. Drobné překlepy v běžném textu jsou zachovány.

1. **Styly formuláře**

   > udělej mi css styly na formular a dej je to styles.css

   Doplnil jsem styly formulářových polí, popisků, výběrů, tlačítek, rozložení, patičky a responzivního zobrazení. Opravil jsem také odkaz na `styles.css` v `formular.html`.

2. **Odkaz z Google stránky na formulář**

   > a das tam úrosim jesre odkaz, at se z googlu dostanu na ty formulare?

   Do navigace v `index.html` jsem přidal odkaz na `formular.html`.

3. **CSS validační odznak na každé stránce**

   > dej tuto validaci na kazdou stranku a kdyz uz tam nekdew je, nahrad  ji timto

   ```html
   <p>
       <a href="https://gregorfilip.github.io/googlesearch/">
           <img style="border:0;width:88px;height:31px"
                src="https://jigsaw.w3.org/css-validator/images/vcss-blue"
                alt="Ověřit CSS!" />
       </a>
   </p>
   ```

   Přidal jsem odznak na všechny čtyři HTML stránky a nahradil jím předchozí CSS validaci.

4. **Oprava chyby přístupnosti**

   > 1. **Error**: The `aria-label` attribute must not be specified on any `div` element unless the element has a `role` value other than `caption`, `code`, `deletion`, `emphasis`, `generic`, `insertion`, `paragraph`, `presentation`, `strong`, `subscript`, or `superscript`.
   >
   > From line 16, column 5; to line 16, column 46
   >
   > `ain">↩    <div class="wordmark" aria-label="Google"><span `
   >
   > oprav prosím tuto vhybu

   K wordmarkům na hlavní a obrázkové stránce jsem doplnil `role="img"` a popisky.

5. **Odstranění koncových lomítek z prázdných elementů**

   > 1. **Info**: Trailing slash on void elements [has no effect](https://github.com/validator/validator/wiki/Markup-%C2%BB-Void-elements#trailing-slashes-in-void-element-start-tags-do-not-mark-the-start-tags-as-self-closing) and [interacts badly with unquoted attribute values](https://github.com/validator/validator/wiki/Markup-%C2%BB-Void-elements#trailing-slashes-directly-preceded-by-unquoted-attribute-values).
   >
   > From line 29, column 231; to line 29, column 354
   >
   > `esearch/"><img style="border:0;width:88px;height:31px" src="https://jigsaw.w3.org/css-validator/images/vcss-blue" alt="Ověřit CSS!" /></a></` i toto prosim

   Odstranil jsem koncová lomítka z validačních obrázků.

6. **HTML validace na všech stránkách**

   > pridej jeste tuto validaci na html, popripadme existujici timhle nahrad

   Po upřesnění jsem použil standardní W3C HTML Validator. Odkaz na každé stránce směřuje na validaci příslušného HTML souboru.

7. **Grafický HTML odznak vedle CSS odznaku**

   > to obereni htlml ale udelej stejne jako obrazekm u css, a vymen stavajici veci timto + dej ikonky  alicdace ccs i html k sobe

   Textové odkazy jsem nahradil grafickým HTML odznakem a umístil jej vedle CSS odznaku.

8. **Použití dodaného obrázku HTML odznaku**

   > tento obrazek vymen za ten sta vajici u html vsude

   ```html
   <img src="https://www.w3.org/Icons/valid-html401" alt="Ověřit HTML!" style="border:0;width:88px;height:31px">
   ```

   Dodaný obrázek jsem použil na všech stránkách a ponechal odkaz na HTML validátor konkrétní stránky.

9. **Změna CSS validačního odznaku**

   > tohle zaaam dej jako validaci na css

   ```html
   <a href="https://jigsaw.w3.org/css-validator/validator?uri=https://gregorfilip.github.io/googlesearch/">
     <img src="https://jigsaw.w3.org/css-validator/images/vcss" alt="Valid CSS!">
   </a>
   ```

   Dodaný odkaz i obrázek CSS validátoru jsem nasadil na všechny stránky.

10. **Citace AI**

    > udelej mi citaci ai i s promptem

    Doplnil jsem citaci GitHub Copilotu a popis jeho využití.

11. **Rozšíření citace o zadání a provedené úpravy**

    > az to je delsi, vsechny prompty, co jsi vse udelal apod

    Rozšířil jsem citaci o přehled provedených úprav a zadání z konverzace.

12. **Doplnění všech promptů místo příkladů**

    > vsechny prompty, ne jen priklady

    Tato část README nyní obsahuje všechna zadání v konverzaci, jejich dodané HTML kódy a související přehled změn.
