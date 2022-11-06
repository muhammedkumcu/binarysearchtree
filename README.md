[Patika.dev](https://www.patika.dev/tr)
# PROJE - 3
***
## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
***Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.***
***
### *Aşamalar*
***
* Root 7'dir.
```
                                    7
```
* 5 gelir. 5<7 olduğundan sola yazılır.
```
                                    7
                                  /
                                5
```
* 1 gelir. 1<7 olduğundan soldan ilerlenir.
  * 1<5 olduğundan sola yazılır.
```
                                    7
                                  /
                                5
                              /
                            1
```
* 8 gelir. 8>7 olduğundan sağa yazılır.
```
                                   7
                                 /   \
                                5     8
                               /
                              1
```
* 3 gelir. 3<7 olduğundan soldan ilerlenir.
  * 3<5 olduğundan soldan ilerlenir.
    * 3>1 olduğundan sağa yazılır.
```
                                   7
                                 /   \
                                5     8
                               /
                              1
                               \
                                3
```
* 6 gelir. 6<7 olduğundan soldan ilerlenir.
  * 6>5 olduğundan sağa yazılır.
```
                                   7
                                 /   \
                                5     8
                               / \
                              1   6
                               \
                                3
```
* 0 gelir. 0<7 olduğundan soldan ilerlenir.
  * 0<5 olduğundan soldan ilerlenir.
    * 0<1 olduğundan sola yazılır.
```
                                   7
                                 /   \
                                5     8
                               / \
                              1   6
                            /  \
                           0    3
```
* 9 gelir. 9>7 olduğundan sağdan ilerlenir.
  * 9>8 olduğundan sağa yazılır.
```
                                   7
                                 /   \
                                5     8
                               / \     \
                              1   6     9
                             / \
                            0   3
```
* 4 gelir. 4<7 olduğundan soldan ilerlenir.
  * 4<5 olduğundan soldan ilerlenir.
    * 4>1 olduğundan sağdan ilerlenir.
      * 4>3 olduğundan sağa yazılır.
```
                                   7
                                 /   \
                                5     8
                               / \     \
                              1   6     9
                             / \
                            0   3
                                 \
                                  4
```
- 2 gelir. 2<7 olduğundan soldan ilerlenir.
  - 2<5 olduğundan soldan ilerlenir.
    - 2>1 olduğundan sağdan ilerlenir.
      - 2<3 olduğundan sola yazılır.
```
                                   7
                                 /   \
                                5     8
                               / \     \
                              1   6     9
                             / \
                            0   3
                               / \
                              2   4
```
***
