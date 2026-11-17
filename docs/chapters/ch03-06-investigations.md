# 3.6 Hva hvis vi endrer forutsetningene?

Når vi utforsker en geometrisk situasjon, er det lurt å endre én opplysning om gangen. Da blir det lettere å se hva som påvirker løsningen.

### En praktisk undersøkelse

En stige står mot en vegg. Stigen er 5 m lang, og avstanden fra veggen er først 3 m.

Vi kan bruke Pytagoras til å finne hvor høyt stigen når. Deretter kan vi undersøke hva som skjer når foten på stigen flyttes lenger fra veggen, mens stigens lengde er den samme.

!!! example "Eksempel 3.6.1 – Stigen flyttes"

    Stigen er 5 m lang. Først står den 3 m fra veggen. Hvor høyt når den opp? Hva skjer hvis avstanden økes til 4 m?

    **Først:** Vi bruker Pytagoras:

    $$
    \begin{aligned}
    h^2+3^2&=5^2\\
    h^2&=25-9=16\\
    h&=4
    \end{aligned}
    $$

    **Deretter:** Avstanden fra veggen økes til 4 m:

    $$
    \begin{aligned}
    h^2+4^2&=5^2\\
    h^2&=25-16=9\\
    h&=3
    \end{aligned}
    $$

    Når foten flyttes lenger fra veggen, blir høyden mindre.

    $$
    \underline{\underline{\text{Høyden går fra 4 m til 3 m.}}}
    $$

### Fra observasjon til algebra

Vi kan også undersøke hva som skjer når én katet økes, mens den andre holdes fast.

En rettvinklet trekant har katetene $a$ og $b$, og hypotenusen $c$. Hvis den første kateten økes med et positivt tall $d$, blir den nye hypotenusen

$$
c'=\sqrt{(a+d)^2+b^2}.
$$

Den opprinnelige hypotenusen er

$$
c=\sqrt{a^2+b^2}.
$$

Vi kan sammenligne kvadratene:

$$
\begin{aligned}
c'^2-c^2
&=(a+d)^2+b^2-(a^2+b^2)\\
&=a^2+2ad+d^2+b^2-a^2-b^2\\
&=2ad+d^2.
\end{aligned}
$$

Når $a>0$ og $d>0$, er uttrykket positivt. Derfor er $c'^2>c^2$. Begge hypotenusene er positive, så også $c'>c$.

## Oppgaver

!!! question "Oppgave 3.6.1 – Undersøk stigen"

    En stige er 10 m lang og står mot en loddrett vegg. Avstanden fra veggen er først 6 m.

    a) Hvor høyt når stigen opp på veggen?

    b) Hva skjer med høyden hvis avstanden fra veggen økes til 8 m?

    c) Forklar med egne ord hvorfor høyden endres slik.

??? note "Fasit – oppgave 3.6.1"

    a)

    $$
    \begin{aligned}
    h^2+6^2&=10^2\\
    h^2&=100-36=64\\
    h&=8
    \end{aligned}
    $$

    b)

    $$
    \begin{aligned}
    h^2+8^2&=10^2\\
    h^2&=100-64=36\\
    h&=6
    \end{aligned}
    $$

    $$
    \underline{\underline{\text{Høyden går fra 8 m til 6 m.}}}
    $$

    c) Stigens lengde er fast. Når avstanden fra veggen øker, må den loddrette høyden bli mindre for at Pytagoras-sammenhengen fortsatt skal stemme.

!!! question "Oppgave 3.6.2 – Endre én katet"

    En rettvinklet trekant har katetene 3 cm og 4 cm.

    a) Finn hypotenusen.

    b) Øk den første kateten fra 3 cm til 5 cm. Finn den nye hypotenusen.

    c) Hva skjer med hypotenusen når én katet øker og den andre holdes fast?

??? note "Fasit – oppgave 3.6.2"

    a)

    $$
    c=\sqrt{3^2+4^2}=5
    $$

    b)

    $$
    c'=\sqrt{5^2+4^2}=\sqrt{41}\approx6{,}40
    $$

    c) Hypotenusen blir lengre. Når én katet øker og den andre er uendret, øker summen av katetenes kvadrater.

    $$
    \underline{\underline{c'\approx6{,}40\text{ cm}}}
    $$

!!! question "Oppgave 3.6.3 – Begrunn algebraisk"

    En rettvinklet trekant har katetene $a$ og $b$. Den første kateten økes med $d$, der $a>0$ og $d>0$.

    Vis ved hjelp av Pytagoras at hypotenusen blir lengre.

??? note "Fasit – oppgave 3.6.3"

    Den opprinnelige hypotenusen er $c$, og den nye er $c'$.

    $$
    \begin{aligned}
    c'^2-c^2
    &=(a+d)^2+b^2-(a^2+b^2)\\
    &=2ad+d^2
    \end{aligned}
    $$

    Fordi $a>0$ og $d>0$, er $2ad+d^2>0$. Dermed er $c'^2>c^2$. Hypotenusene er positive, så $c'>c$.

    $$
    \underline{\underline{c'>c}}
    $$

---
