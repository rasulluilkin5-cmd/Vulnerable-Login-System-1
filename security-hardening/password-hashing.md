Şifrələrin Hash Edilməsi

Bu mərhələdə şifrələr artıq plaintext saxlanılmır. bcrypt kitabxanası vasitəsilə şifrələr hash edilir və təhlükəsiz şəkildə bazada saxlanılır. Bu üsul məlumat sızması halında şifrələrin oxunmasının qarşısını alır.

bcrypt quraşdırmaq
Şifrəni hash etmək
Login zamanı compare funksiyası istifadə etmək
Salt əlavə etmək

SQL Injection-dan Müdafiə

Prepared statements və input validation istifadə edilərək SQL Injection zəifliyi aradan qaldırılır. İstifadəçi məlumatları birbaşa sorğuya əlavə edilmir.

Prepared statements istifadə etmək
Input validation əlavə etmək

Rate Limiting

Login cəhdlərinə limit tətbiq edilir. Müəyyən sayda uğursuz cəhddən sonra hesab və ya IP müvəqqəti bloklanır. Bu brute force hücumlarının qarşısını alır.

5 uğursuz cəhddən sonra bloklama
IP izləmə sistemi
Müvəqqəti hesab kilidləmə

Güclü Şifrə Siyasəti

İstifadəçilər üçün minimum şifrə uzunluğu və mürəkkəblik qaydaları tətbiq edilir. Böyük hərf, kiçik hərf, rəqəm və xüsusi simvol tələbi əlavə olunur.

Minimum 8 simvol
Böyük hərf
Kiçik hərf
Rəqəm
Xüsusi simvol
