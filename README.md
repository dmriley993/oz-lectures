# OZ Lectures

Lecture slides (PDF) and an interactive companion widget by
David Michael Riley (ENSTA Paris / Institut Polytechnique de Paris).

```
oz-lectures/
├── index.html                                                ← interactive widget
├── nonsmooth-contact/
│   └── nonsmooth_mechanics_pedagogical_slides.pdf
└── porosim/
    └── main.pdf
```

## Lectures

- **`nonsmooth-contact/`** — 45-minute lecture on nonsmooth contact mechanics:
  normal cones, variational inequalities, projections, Signorini contact,
  1D friction, and the 2D Coulomb cone. The widget at the repo root is its
  interactive companion.
- **`porosim/`** — a shifted-interface approach for internal discontinuities
  in poroelastic media (joint with Scovazzi and Stefanou; ERC INJECT,
  no. 101087771).

## Interactive widget

`index.html` is a self-contained companion to the nonsmooth-contact lecture,
with five tabs: normal cone, projection, Signorini (bouncing ball), 1D
Coulomb friction (spring-slider), and 2D Coulomb iteration. Once GitHub
Pages is enabled (Settings → Pages → Source: `main` / root), it lives at:

```
https://dmriley993.github.io/oz-lectures/
```

The widget supports deep linking via URL hash — useful for QR codes on
individual slides:

| Slide topic                            | Deep link                                                    |
| -------------------------------------- | ------------------------------------------------------------ |
| Normal cone (interior / edge / corner) | https://dmriley993.github.io/oz-lectures/#tab=ncone          |
| Projection identity                    | https://dmriley993.github.io/oz-lectures/#tab=proj           |
| Signorini / bouncing ball              | https://dmriley993.github.io/oz-lectures/#tab=ball           |
| 1D Coulomb friction (spring-slider)    | https://dmriley993.github.io/oz-lectures/#tab=slider         |
| 2D Coulomb iteration — three regimes   | https://dmriley993.github.io/oz-lectures/#tab=iterate        |

## Local widget preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000/
```
