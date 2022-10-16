## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

- Root 7'dir
- 5'i kontrol ederiz ve 7 yani roottan küçük olduğu için sola yazarız.
- 1'i kontrol ederiz 7'den küçüktür rootun solunu yani 5i kontrol ederiz 5'ten de küçüktür, 5'in soluna yazarız.
- 8'i kontrol ederiz 7'den büyüktür rootun sağına yazarız.
- 3'ü kontrol ederiz roottan küçüktür, sola geçeriz 5'ten de küçüktür, sola geçeriz, birden büyüktür, 1'in sağına yazarız.
- 6'yı kontrol ederiz, rootan küçüktür sola geçeriz, 5'ten büyüktür, 5'in sağına yazarız.
- 0'ı kontrol ederiz rootan küçüktür sola geçeriz, 5'ten küçüktür sola geçeriz, 1'den küçüktür, 1'in soluna yazarız
- 9'u kontrol ederizi 7'den büyüktür sağa geçeriz, sekizden büyüktür sekizin sağına yazarız.
- 4'ü kontrol ederiz, 7'den küçüktür sola geçeriz, 5'ten küçüktür sola geçeriz, 3'ten büyüktür, 3'ün sağına yazarız.
- 2'yi kontrol ederiz, 7'den küçüktür sola geçeriz, 5'ten küçüktür sola geçeriz, 1'den büyüktür sağa geçeriz, 3'ten küçüktür 3'ün soluna yazarız

#### Görsel Hali

                              7
                              |
                       5          8
                       |          |
                    1     6         9
                    |
                0       3
                        |
                    2      4