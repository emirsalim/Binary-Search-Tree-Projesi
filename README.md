# Binary-Search-Tree-Projesi

**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.**


öncelikle diziyi küçükten büyüğe sıralıyoruz [0,1,2,3,4,5,6,7,8,9]
root olarak 4 ü seçiyorum. 4 sayısının solunda 2, sağında 7 bulunur.
sol taraf: 2 düğümünün sağında 2 den büyük olduğu için 3,solunda 1 sayısı bulunur. 1 sayısının sağı boş sol tarafında 0 bulunur.
sağ taraf: 7 düğümünün solunda 6 bulunuyor 6'nın sol tarafında 5,sağ tarafı ise boştur. 7 düğümünün sağında ise 8 bulunuyor, 8'in sol tarafı boş sağ tarafı ise 9 bulunuyor.  


                   4
               /      \
              2        7
             /  \     /  \
            1    3   6     8
           /        /        \
          0        5          9
