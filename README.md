# Selection/İnsertion Sort
Selection Sort Projesi
    [22,27,16,2,18,6] -> Insertion Sort aşamalarını yazınız.
    2'li elemanlar arası kıyaslama yapılmaktadır. Kıyaslama doğru oldukça sağa doğru ilerlenir. Doğru olmadığı zaman yer değişikliği yapılır. Yapılan yer değişikliği sonucunda önceden sağa doğru ilerlenen kısım kontrol edilmediği için sola doğru tekrar kıyas yapılır. Bu       noktada da kıyaslama hayır olana kadar devam edilir ve kıyaslama birince sağa doğru ilerlenen en son noktaya geri dönülür ve döngü bu şekilde devam eder. Aşağıda da bu konu ile ilgili bir örnek bulunmaktadır.
    
    1. Adım
    [22,27,16,2,18,6] 22 27'den küçük mü? -- Evet -- Yer değişikliği yapılmaz.
    2. Adım
    [22,27,16,2,18,6] 27 16'dan küçük mü ? -- Hayır -- Yer değişikliği yapılır. Sol tarafa doğru kıyas yapılmaya başlanır.
    3. Adım
    [22,16,27,2,18,6] 16 22'den küçük mü ? -- Evet -- Yer değişikliği yapılır. En son sol nokta ile sorgu yapıldığı için sağa doğru sorguda kalınan en son yerden (27 sayısından) sorgu devam eder.
    4. Adım
    [16,22,27,2,18,6] 27 2'den küçük mü ? -- Hayır -- Yer değişikliği yapılır. Sol tarafa doğru kıyas yapılmaya başlanır.
    5. Adım
    [16,22,2,27,18,6] 2 22'den küçük mü ? -- Evet -- Yer değişikliği yapılır.
    6. Adım
    [16,2,22,27,18,6] 2 16'dan küçük mü ? -- Evet -- Yer değişikliği yapılır. En son sol nokta ile sorgu yapıldığı için sağa doğru sorguda kalınan en son yerden (27 sayısından) sorgu devam eder.
    7. Adım
    [2,16,22,27,18,6] 27 18'den küçük mü ? -- Hayır -- Yer değişikliği yapılır. Sol tarafa doğru kıyas yapılmaya başlanır.
    8. Adım
    [2,16,22,18,27,6] 18 22'den küçük mü ? -- Evet -- Yer değişikliği yapılır.
    9. Adım
    [2,16,18,22,27,6] 18 16'dan küçük mü ? -- Hayır -- Yer değişikliği yapılmaz. Sağa doğru sorguda kalınan en son yerden (27 sayısından) sorgu devam eder.
    10. Adım
    [2,16,18,22,27,6] 27 6'dan küçük mü ? -- Hayır -- Yer değişikliği yapılır. Sol tarafa doğru kıyas yapılmaya başlanır.
    11. Adım
    [2,16,18,22,6,27] 6 22'den küçük mü ? -- Evet -- Yer değişikliği yapılır.
    12. Adım
    [2,16,18,6,22,27] 6 18'den küçük mü ? -- Evet -- Yer değişikliği yapılır.
    13. Adım
    [2,16,6,18,22,27] 6 16'dan küçük mü ? -- Evet -- Yer değişikliği yapılır.
    14. Adım
    [2,6,16,18,22,27] 6 2'den küçük mü ? -- Hayır -- Yer değişikliği yapılmaz. Sağa doğru sorguda kalınan en son yerden (27 sayısından) sorgu devam eder.
    15. Adım
    Kıyas yapılamayacağı için sıralama tamamlanmıştır. -- [ 2, 6, 16, 18, 22, 27 ] --



    
