### Insertion Sort Project
   - [22,27,16,2,18,6] Insertion Sort
 * Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
   - [*2, 27, 16, *22, 18, 6] (n)
   - [2,*6, 16, 22, 18, *27] (n-1)
   - [2, 6, 16, 22, 18, 27] (n-2) (değişiklik olmadı çünkü kalan sayılarda en küçük sayı zaten sıralıydı.)
   - [2, 6, 16, *18, *22, 27] (n-3)
   - [2, 6, 16, 18, 22, 27] (n-4)(değişiklik olmadı çünkü kalan sayılarda en küçük sayı zaten sıralıydı.)

 * Big-O gösterimini yazınız. 
     - O(n²)
 * Time Complexity: 
    - Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

* Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
   - Average Case kapsamına girer çünkü sıralandıktan sonra sayı ortada bulunur.


* [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

  - [ *2, 3, 5, 8, *7, 9, 4, 15, 6]
  - [ 2, 3, 5, 8, 7, 9, 4, 15, 6] (3 Zaten kalan sayılar arasındaki en küçük sayıydı. Bu yüzden yeri değişmedi. )
  - [ 2, 3, *4, 8, 7, 9, *5, 15, 6]
  - [ 2, 3, *4, *6, 7, 9, *5, 15, *8]
