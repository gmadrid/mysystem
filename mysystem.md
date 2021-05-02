# CFOP

## Cross

try for <10 moves

## FTL

try for <=4 cube rotations

## Two-look OLL

### bottom: edges

|     | Name | Alg | Image desc |
| --- | --- | --- | --- |
| ![bar](images/bar.svg) | bar | ```F R U R' U' F'  ==  F (sexy) F'``` | ```xUx===xDx```|
| ![ell](images/ell.svg) | ell | ```f R U R' U' f'  ==  f (sexy) f'``` | ```xUxL==x=x``` |

### corner algs

|     | Sym | Names | Alg | Left | Image desc |
| --- | ----   | ---   | --- | :---: | --- |
| ![oll27](images/oll27.svg) | S      | OLL 27, Sune | ```R U R' U R U2 R'``` | | ```U=R=====D``` |
| ![oll26](images/oll26.svg) | S- | OLL 26, Anti-sune | ```L' U' L U' L' U2 L``` | * | ```L=U=====R``` |
| ![oll21](images/oll21.svg) | H | OLL 21, Double-sune | ```R U R' U R U' R' U R U2 R'``` | | ```L=R===L=R``` |
| ![oll22](images/oll22.svg) | Pi | OLL 22 | ```R U2 R2' U' R2 U' R2' U2 R``` | | ```L=U===L=D``` |
| ![oll23](images/oll23.svg) | U | OLL 23 | ```R2 D R' U2 R D' R' U2 R'``` | | ```F=====D=D``` |
| ![oll24](images/oll24.svg) | T | OLL 24 | ```B' R' F R B R' F' R``` | | ```L=R======``` |
| ![oll25](images/oll25.svg) | L | OLL 25 | ```F R' F' L F R F' L'``` | | ```F=R===D==``` |

## One-look PLL

    H (1/72):   M2' U M2' U2 M2' U M2'
    Ua (1/18):  y2 F2 U' M U2 M' U' F2
    Ub (1/18):  y2 F2 U M U2 M' U F2
    Z (1/36):   (M2' U M2' U) (M' U2) (M2' U2 M') [U2]
    Aa (1/18):  l' U R' D2 R U' R' D2 R2 (x')
    Ab (1/18):  y' r' U' L D2 L' U L D2 L2 ***
    E (1/36):   ???
    F (1/18):   ???
    Ga (1/18):  y R2 u R' U R' U' R u' R2 F' U F  ***
    Gb (1/18):  ???
    Gc (1/18):  y' L2 u' L U' L U L' u L2 F U' F'
    Gd (1/18):  ???
    Ja (1/18):  y R' U L' U2 R U' R' U2 L R U'
    Jb (1/18):  y' L U' R U2 L' U L U2 R' L' U ***
    Na (1/72):  ???
    Nb (1/72):  ???
    Ra (1/18):  y R U R' F' R U2 R' U2 R' F R U R U2 R' (learning)
    Rb (1/18):  ???
    T (1/18):   R U R' U' R' F R2 U' R' U' R U R' F'
    V (1/18):   ???
    Y (1/18):   ???

??? = I don't have an alg memorized for this.  
*** = Mirror using left hand.
