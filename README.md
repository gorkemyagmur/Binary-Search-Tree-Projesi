# Binary-Search-Tree-Projesi
Patika.dev, Veri Yapıları ve Algoritmalar, Binary Search Tree Projesi


[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

1) Root 7 olarak belirlenmiştir.                             
                                                             
2) 5<7 olduğu için sol tarafa eklenir.                     
                                                            
3) 1<7 ve 1<5 olduğu için 5'in altına eklenir.               
                                                           
4) 8>7 olduğu için sağ tarafa eklenir.                      

5) 3<7 , 3<5 ve 3>1 olduğu için 1'in sağ tarafına eklenir.

6) 6<7 ve 6>5 olduğu için 5'in sağ tarafına eklenir.

7) 0<7 , 0<5, 0<1 olduğu için 1'in sol tarafına eklenir.

8) 9>7 ve 9>8 olduğu için 8'in sağ tarafına eklenir.

9) 4<7 , 4<5, 4>1 , 4>3 olduğu için 3'ün sağ tarafına yazılır.

10) 2<7, 2<5, 2>1, 2<3 olduğu için 3'ün sol tarafına yazılır.




                                                                        7 

                                                                      /     \

                                                                   5            8 

                                                                /    \        /    \
 
                                                              1       6              9

                                                            /   \

                                                         0         3

                                                                 /    \

                                                               2         4 








