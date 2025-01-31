---
title: 📄 Eksempler på grenser
---

> [!question] Spørsmål
> Hva er 
> 1. $$\lim_{x\longrightarrow  \infty}\frac{3x^5+3x^2}{2x^5}?$$
> 2. $$\lim_{x\longrightarrow   \infty} \frac{x^2}{\sqrt{x^4+x}}?$$

> [!abstract] 1

Typisk "triks" når vi har $x\longrightarrow \infty$ på rasjonale funksjoner: trekk ut høyeste potens:

$$
\begin{aligned} 
  \lim_{x\longrightarrow  \infty}\frac{\cancel{ x^5 }\left( 3+\frac{3x^2}{x^5} \right)}{\cancel{ x^5 }(2)} =\lim_{x\longrightarrow  \infty}\frac{3+\frac{3}{x^3}}{2} = \frac{3+0}{2}=\frac{3}{2}
\end{aligned} 
$$
fordi $\frac{3}{x^3} \longrightarrow \frac{3}{\text{noe veldig stort}} = \text{veldig lite}\longrightarrow  0$.

> [!abstract] 2

Ideen er veldig lik som den over. Vi ser at hvis det bare hadde stått $\sqrt{x^4}$ så ville ting vært veldig håndterbart. Siden $x^4+x$ oppfører seg praktisk talt som $x^4$ bare $x$ er stor nok prøver vi på samme triks som i 1.

$$
\begin{aligned} 
  \lim_{x\longrightarrow   \infty} \frac{x^2}{\sqrt{x^4+x}} & = \lim_{x\longrightarrow  \infty}\frac{x^2}{\sqrt{x^4\left( 1+\frac{x}{x^4} \right)}} \\ &= \lim_{x\longrightarrow  \infty} \frac{\cancel{ x^2 }}{\cancel{ x^2 }\sqrt{1+\frac{1} {x^3}}} \\ &= \lim_{x\longrightarrow  \infty}\frac{1}{\sqrt{1+\frac{1}{x^3}}} = \frac{1}{\sqrt{1}}=1.
\end{aligned}
$$
Flere eksempler kan dere finne ved å se på ukesoppdrag [[Ukesoppdrag og forelesningsnotat/🧠 Uke 36|🧠 Uke 36]].

Grenseverdier er verktøyet som gjør oss i stand til å snakke presist om egenskaper vi ønsker i funksjoner når vi studerer de. Et nøkkelbegrep vi skal bruke er [[Kapittel 1 - grenser og kontinuitet/5 Intro til kontinuitet|kontinuitet]].