# Vulnerable Login System + Security Hardening

## Layihənin Ümumi Təsviri
Bu layihə qəsdən zəif hazırlanmış giriş sisteminin qurulması, təhlükəsizlik boşluqlarının müəyyənləşdirilməsi, analiz olunması və müasir təhlükəsizlik tədbirləri ilə gücləndirilməsini əhatə edir.

## Layihənin Məqsədləri
- Zəif təhlükəsizlikli login sistemi yaratmaq
- Təhlükəsizlik boşluqlarını aşkar etmək
- Penetrasiya testləri və təhlükəsizlik analizi aparmaq
- Müasir qoruma üsullarını tətbiq etmək
- Təhlükəsizlik təkmilləşdirmələrini test etmək

## Əsas Təhlükəsizlik Boşluqları
- Şifrələrin açıq mətn şəklində saxlanılması
- SQL Injection hücumları
- Zəif session idarəetməsi
- Rate limiting olmaması
- Input validation çatışmazlığı

## Təhlükəsizlik Təkmilləşdirmələri
- Şifrələrin hash-lənməsi (bcrypt / Argon2)
- Prepared statements istifadəsi
- Rate limiting
- Input sanitization
- Təhlükəsiz session idarəetməsi

## Layihə Strukturu
- project-overview
- setup-environment
- vulnerable-implementation
- security-analysis
- security-hardening
- testing-validation

## İstifadə Olunan Alətlər
- Jira
- GitHub
- SQL verilənlər bazası
- Təhlükəsizlik test alətləri

## Nəticə
Bu layihə zəif giriş sistemlərinin necə istismar oluna biləcəyini göstərir və onların müasir təhlükəsizlik üsulları ilə necə qoruna biləcəyini praktik şəkildə nümayiş etdirir.
