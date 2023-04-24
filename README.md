# RSTC queuing slides
These slide set corresponds to the
2nd half of the RSTC subject at UPM.
In particular the slide set comprises:
```txt
tema-5
tema-6
tema-7
tema-8
```

## Slides
You can find the slides under each
`tema-N`. For example
```txt
tema-5/
  tema-5.pdf
```
contains the slide set of `tema-5`.

## Assignments
Each `tema-N` has its assignment at, e.g.:
```txt
tema-5/
  ejercicio-alumno.pdf
```

You can fill the assignments using LaTeX
replacing the missing input inside
`tema-5/ejercicio-alumno.tex`, e.g. replace
```tex
    \begin{solucion}
        \input{../../RSTC-solutions/tema-5/solucion-problema-1.tex}
    \end{solucion}
```
by
```tex
    \begin{solucion}
       $e = m c^2$ 
    \end{solucion}
```
and then activate the flag to show your
solutions inside `tema-5/ejercicio-alumno.tex`:
```tex
\setboolean{show}{true}   % <-- uncomment
%\setboolean{show}{false} % <-- comment
```

Then it is enough to go inside the directory
and compile the LaTeX:
```bash
cd tema-5
pdflatex ejercicio-alumno.tex
```
this will produce the PDF file with your
assignment.



# LICENSE
Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0).

Beware that you may **not use the material for commercial purposes**.

