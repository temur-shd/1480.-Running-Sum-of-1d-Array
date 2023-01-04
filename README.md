# 1480.-Running-Sum-of-1d-Array (Tek boyutlu dizinin ilerleyerek alınan toplamı)
Given an array nums. We define a running sum of an array as runningSum[i] = sum(nums[0]…nums[i]).
Return the running sum of nums.

Burada bize **nums** adında bir dizi veriliyor.  Dizinin ilerleyerek alınan toplamlarını çıktı olarak isteniyor.<br>
Örneğin verilen dizi [1,2,3,4,5] ise [1, 1+2, 1+2+3, 1+2+3+4, 1+2+3+4+5] olacak şekilde [1,3,6,10,15]  çıktısı isteniyor. <br>
Bu işlemin ilk akla geelen çözümündeki karmaşıklığına baktığımızda O(n^2) olarka görünüyor. Ama biz karmaşıklığı olabildiğince azaltmak isteriz. Bunun içinde önceki adımda yapılan işlemden faydalanırız. 

