# CCS_C_ILE_SIFREL-_GIRIS-PIC16F877-

---------------Yazılım ne yapıyor?----------------------

Devre çalıştırıldığında keypaden şifre girilicek ise öncelikle "*" tuşuna basmasını ardından şifrenin girilip "#" tuşuna basılması gerekmektedir.

"#" tuşuna basıldığında girilen şifre onaylanıyor. Kullanıcının şifreyi 3 denemede doğru girmesi gerekmektedir.Eğer şifreyi yanlış girerse kalan hakkı kullanıcıya lcd ekranında söyleniyor ve yeniden şifre girmek için tekrar "*"tuşuna basması ve onaylamak içinde "#" tuşuna basması gerekmektedir.3 kez girme hakkında da şifre doğru girilemez ise kapı 30 saniyeliğine şifre girmeye engelleniyor ve kullanıcıya 30 saniye beklemesi gerektiği söyleniyor.Ardından yanlış girilen haklar sıfırlanıyor.

Kullanıcı şifreyi yanlış girdiğinde kırmızı,doğru girdiğinde ise yeşil led yakılmakta ve ekranda şifrenin doğru olup olmaması hakkında da bilgi veriliyor.
