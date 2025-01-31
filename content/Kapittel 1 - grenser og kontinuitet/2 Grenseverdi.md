---
title: 📄 Grenseverdier
---
Allerede tilbake til Arkimedes kan vi finne tilfeller der vi kan konkludere med noen litt upresise argumenter der vi bruker utsagn som *så nær vi bare vil*. Det er det som er opphavet til grenseverdier. Vi begynner med en litt mer uformell definisjon som får frem det viktige i definisjonen.  

![[Kapittel 1 - grenser og kontinuitet/defogteo/✍️ Grenseverdi|✍️ Grenseverdi]]

Vi kan tegne dette slik

![[Files/grenseverdi.svg]]
Det gir oss den formelle definisjonen

![[Kapittel 1 - grenser og kontinuitet/defogteo/✍️ Grenseverdi (formell)|✍️ Grenseverdi (formell)]]

### Eksempler

Tenk gjennom følgende.

> [!question] Spørsmål 
> Hva er
> 1. $\lim_{x\longrightarrow a} x$
> 2. $\lim_{x \longrightarrow a} c$, der $c$ er konstant?
> 3. Hva er $\lim_{x\longrightarrow-2 } \frac{x^2 + x -2 }{x^2 + 5x+6 }$?

> [!abstract] 1-2

Jo, det er vel ganske klart at $\lim_{x \longrightarrow a} x = a$. På samme måte er $c$ konstant, så den endrer ikke verdi. Derfor må $\lim_{x \longrightarrow a} c = c$.

> [!abstract] 3

Vi ser at teller kan faktoriseres slik $x^2+x-2 = (x+2)(x-1)$. Tilsvarende kan nevner faktoriseres slik $x^2+5x+6 = (x+2)(x+3)$. Noe som gir
$$
\begin{aligned} 
  \lim_{x\longrightarrow -2 } \frac{x^2+x-2 }{x^2+5x+6 } &= \lim_{x\longrightarrow-2 } \frac{\cancel{ (x+2) }(x-1) }{\cancel{ (x+2) }(x+3) } \\ &= \lim_{x\longrightarrow-2 }\frac{x-1 }{x+3 }  = \frac{-2-1 }{-2+3 } =\frac{-3 }{ 1}=1    
\end{aligned} 
$$

Når vi ser på grenser skal vi se at det er nyttig å undersøke hva som skjer når vi nærmer oss et punkt kun fra venstre eller høyre side. Det gir følgende definisjon

![[Kapittel 1 - grenser og kontinuitet/defogteo/✍️ Ensidige grenser, uformell|✍️ Ensidige grenser, uformell]]

I tillegg til vanlige grenser kan vi jo også tenke oss at en funksjon stabiliserer seg etter hvert, bare vi holder på *lenge nok*. Det er fører også til følgende definisjon.

![[Kapittel 1 - grenser og kontinuitet/defogteo/✍️ Grenser i uendelig (uformell)|✍️ Grenser i uendelig (uformell)]]

Kanskje litt forenklet kan vi forklare definisjonen over slik

> [!warning] Merk 
> 1. $\lim_{x\longrightarrow a+}f(x)$ er grense der vi kun betrakter $x>a$. Grense fra *høyre*.
> 2. $\lim_{x\longrightarrow  a-}$ er grense der vi kun betrakter $x<a$. Grense fra *venstre*.
> 3. $\lim_{x\longrightarrow \infty}f(x)$ er grense der vi betrakter vilkårlige store $x$.

Det er noen intuitive sammenhenger som vi får bruk for, [[Kapittel 1 - grenser og kontinuitet/3 Regler for grenser|3 Regler for grenser]]
