# CFOP

## Cross

try for <10 moves

## FTL

try for <=4 cube rotations

## Two-look OLL

### bottom: edges

|                        | Name | Alg                               |
| ---                    | ---  | ---                               |
| ![bar](images/bar.svg) | bar  | `F R U R' U' F'  ==  F (sexy) F'` |
| ![ell](images/ell.svg) | ell  | `f R U R' U' f'  ==  f (sexy) f'` |

### corner algs

|                            | Sym  | Names               | Alg                          | Left  |
| ---                        | ---- | ---                 | ---                          | :---: |
| ![oll27](images/oll27.svg) | S    | OLL 27, Sune        | `R U R' U R U2 R'`           |       |
| ![oll26](images/oll26.svg) | S-   | OLL 26, Anti-sune   | `L' U' L U' L' U2 L`         | *     |
| ![oll21](images/oll21.svg) | H    | OLL 21, Double-sune | `R U R' U R U' R' U R U2 R'` |       |
| ![oll22](images/oll22.svg) | Pi   | OLL 22              | `R U2 R2' U' R2 U' R2' U2 R` |       |
| ![oll23](images/oll23.svg) | U    | OLL 23              | `R2 D R' U2 R D' R' U2 R'`   |       |
| ![oll24](images/oll24.svg) | T    | OLL 24              | `B' R' F R B R' F' R`        |       |
| ![oll25](images/oll25.svg) | L    | OLL 25              | `F R' F' L F R F' L'`        |       |

## One-look PLL

|                      | Sym | Prob | Code | Alg                                                    |
| ---                  | --- | ---  | ---  | ---                                                    |
| ![Ua](images/ua.svg) | Ua  | 1/18 | R    | `F2 U' M U2 M' U' F2`                                  |
| ![Ub](images/ub.svg) | Ub  | 1/18 | R    | `F2 U M U2 M' U F2`                                    |
| ![Z](images/z.svg)   | Z   | 1/36 |      | `(M2' U M2' U) (M' U2) (M2' U2 M') [U2]`               |
| ![H](images/h.svg)   | H   | 1/72 |      | `M2' U M2' U2 M2' U M2'`                               |
| ![Aa](images/aa.svg) | Aa  | 1/18 | L    | `l' U R' D2 R U' R' D2 R2`                             |
| ![Ab](images/ab.svg) | Ab  | 1/18 |      | `r U' L D2 L' U L D2 L2`                               |
| ![E](images/e.svg)   | E   | 1/36 | N    | `x' (R U' R' D) (R U R' D') (R U R' D) (R U' R' D') x` |
| ![Ra](images/ra.svg) | Ra  | 1/18 | NL   | `R U R' F' R U2 R' U2 R' F R U R U2 R' [U']`           |
| ![Rb](images/rb.svg) | Rb  | 1/18 | N    | `L' U' L F L' U2 L U2 L F' L' U' L' U2 L [U]`          |
| ![Ja](images/ja.svg) | Ja  | 1/18 |      | `R' U L' U2 R U' R' U2 L R U'`                         |
| ![Jb](images/jb.svg) | Jb  | 1/18 | L    | `L U' R U2 L' U L U2 L' R' U `                         |
| ![T](images/t.svg)   | T   | 1/18 |      | `R U R' U' R' F R2 U' R' U' R U R' F'`                 |
| ![F](images/f.svg)   | F   | 1/18 | ?    | ``                                                     |
| ![V](images/v.svg)   | V   | 1/18 |      | ``                                                     |
| ![Y](images/y.svg)   | Y   | 1/18 |      | ``                                                     |
| ![Na](images/na.svg) | Na  | 1/72 |      | ``                                                     |
| ![Nb](images/nb.svg) | Nb  | 1/72 |      | ``                                                     |
| ![Ga](images/ga.svg) | Ga  | 1/18 | ?    | `R2 u R' U R' U' R u' R2 F' U F`                       |
| ![Gb](images/gb.svg) | Gb  | 1/18 | ?    | ``                                                     |
| ![Gc](images/gc.svg) | Gc  | 1/18 | L?   | `L2 u' L U' L U L' u L2 F U' F'`                       |
| ![Gd](images/gd.svg) | Gd  | 1/18 | L?   | ``                                                     |


Codes: L = left hand, ? = don't know, R = revisit for better alg, N = new, learning now

[//]: # (MACHINE PROCESSED INFO FOLLOWS THIS COMMENT)

[//]: # (ollimage specs for all of the OLL algs that I know.)
[//]: # (bar  xUx===xDx)
[//]: # (ell  xUxL==x=x)
[//]: # (oll27  U=R=====D)
[//]: # (oll26  L=U=====R)
[//]: # (oll21  L=R===L=R)
[//]: # (oll22  L=U===L=D)
[//]: # (oll23  F=====D=D)
[//]: # (oll24  L=R======)
[//]: # (oll25  F=R===D==)

[//]: # (pllimage specs for all of the PLL algs that I know.)
[//]: # (ua  8>6 6>4 4>8)             
[//]: # (ub  8>4 4>6 6>8)             
[//]: # (z  2<>4 6<>8)               
[//]: # (h  2<>8 4<>6)               
[//]: # (aa  1>3 3>9 9>1)             
[//]: # (ab  7>3 3>1 1>7)             
[//]: # (e  1<>7 3<>9)               
[//]: # (ra  3<>9 4<>2)               
[//]: # (rb  1<>7 2<>6)               
[//]: # (ja  2<>4 1<>3)               
[//]: # (jb  1<>3 2<>6)               
[//]: # (t  3<>9 4<>6)               
[//]: # (f  2<>8 3<>9)               
[//]: # (v  1<>9 2<>6)               
[//]: # (y  2<>4 1<>9)               
[//]: # (na  3<>7 4<>6)               
[//]: # (nb  1<>9 4<>6)               
[//]: # (ga  1>3 3>7 7>1 2>4 4>6 6>2)
[//]: # (gb  3>1 7>3 1>7 4>2 6>4 2>6)
[//]: # (gc  9>3 3>1 1>9 6>4 4>2 2>6)
[//]: # (gd  3>9 1>3 9>1 4>6 2>4 6>2)
