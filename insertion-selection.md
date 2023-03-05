[22,27,16,2,18,6] insertion sort dizilimine göre düzenleyeceğiz

1. Aşama --> 22|,27,16,2,18,6 --> 22 tek başına sıralıdır ve başka işlem yoktur.

2. Aşama --> 22,27|,16,2,18,6 --> 22 ve 27 aralarında doğru şekilde sıralanmıştır

3. Aşama --> 22,27,16|,2,18,6 --> 22,16,27|,2,18,6 --> 16,22,27|,2,18,6 --> 16'yı eklediğimizde en küçük olması nedeniyle en sola gelir.

4. Aşama --> 16,22,27,2|,18,6 --> 16,22,2,27|,18,6 --> 16,2,22,27|,18,6 --> 
2,16,22,27|,18,6

5. Aşama --> 2,16,22,27,18|,6 --> 2,16,22,18,27|,6 --> 2,16,18,22,27|,6

6. Aşama --> 2,16,18,22,27,6| --> 2,16,18,22,6,27| --> 2,16,18,6,22,27| -->
2,16,6,18,22,27| --> 2,6,16,18,22,27| 

Big-O gösterimi = O(n^2) 

18 sayısı bu dizilimde Avarage Case kapsamına girmektedir.

-----

[7,3,5,8,2,9,4,15,6] Selection Sort'a göre ilk 4 adımını yazacağız. Öncelikle dizinin en küçük öğesini buluyoruz.  

--> Dizinin en küçük öğesi 2, bu durumda 2 en başa geçer.

1. Adım --> [2,3,5,8,7,9,4,15,6]  

2. Adım --> [2,3,4,8,7,9,5,15,6] **Bu adımda 2 ve 3 sıralı olması nedeniyle 3. öğeye geçtim ve bu sebeple adım farkı oluşabilir. Eğer sıralı olan adımı atlamasaydık 3. adım 4. adım olacaktı, bu konuda çeşitli kaynaklardan araştırma yaptım ancak ancak atlanması yada atlanmaması konusunda bir bilgiye ulaşamadım.**

3. Adım --> [2,3,4,5,7,9,8,15,6]

4. Adım --> [2,3,4,5,6,9,8,15,7]

