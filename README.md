# Proje 2

## [16,21,11,8,12,22] -> Merge Sort

### Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
### Big-O gösterimini yazınız.
````
1.Adım:  [16,21,11,8,12,22]

2.Adım:  [16,21,11]  —  [8,12,22]

3.Adım:  [16]  —   [21,11]  —  [8]  —  [12,22]

4.Adım:  [16]  —  [21]  —  [11]  —  [8]  —  [12]  —  [22]

5.Adım:  [16]   —   [11,21]    —    [8]  —  [12,22]

6.Adım:      [11,16,21]  —  [8,12,22]

    Son:  [8,11,12,16,21,22]

````

### Big-O Gösterimi: 
````
O(nlogn)
````