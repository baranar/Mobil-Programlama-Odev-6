Flutter’da, kullanıcıdan isim, e-posta ve şifre bilgilerini alan bir form yapısı oluşturun. Bu formda:
widget’ları ile isim, e-posta ve şifre alanları bulunsun.
E-posta adresinin geçerli bir formatta olup olmadığını kontrol eden bir doğrulama işlemi yapılmalı.
Şifre alanı en az 6 karakter olmalı, aksi halde kullanıcıya bir hata mesajı gösterilmeli.
Kullanıcı, tüm alanları doğru bir şekilde doldurduğunda butonuna tıklayarak formu tamamlamalı.
TextFormField widget’larının validator parametresi ile doğrulama işlemleri yapılabilir.
Formun doğrulama işlemlerini Form widget'ı içinde GlobalKey ve FormState kullanarak yönetin.
Hata mesajlarını göstermek için her bir TextFormField üzerinde validator işlevi tanımlayın.
