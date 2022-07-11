# insertion-sort-proje-patika.dev

  [22,27,16,2,18,6] -> Insertion Sort
    
     1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
      1) En küçük sayıyı dizinin en başındaki sayıyla değiştiririz.
      --> [2,27,16,22,18,6]
      2) İkinci sıra için en küçük sayıyı bulup yer değiştiririz.
      --> [2,6,16,22,18,27]
      3) Üçüncü sıradaki sayı küçük olduğu için olduğu yerde bırakılır.
      4) Dördüncü sıra için en küçük sayı bulunur ve yer değiştirilir.
      --> [2,6,16,18,22,27]
      5) Seri küçükten büyüğe dizildiği için işlemler tamamlanmıştır.
   
     2. Big-O gösterimini yazınız. 
      O(n^2)
     
     3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
      Best case    : O(n) -> 2
      Average case : O(n^2) -> 16,18
      Worst case   : O(n^2) -> 27
     
     4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
     
      Average Case kapsamına girer.
      
    [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
    
      1) [2,3,5,8,7,9,4,15,6]
      2) [2,3,5,8,7,9,4,15,6]
      3) [2,3,4,8,7,9,5,15,6]
      4) [2,3,4,5,7,9,8,15,6]
