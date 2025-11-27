# Öğrenci Portal Bilgi Sistemi

## Projenin Amacı

Bu projenin amacı, bir üniversite öğrenci portalı için C# Windows Form uygulaması geliştirmektir. Uygulama, öğrenci bilgilerini ve ders verilerini yönetebileceğiniz, aynı zamanda veritabanı üzerinde kolayca işlem yapabileceğiniz bir platform sunmayı hedeflemektedir.

Verilerimizi saklamak ve rahatça erişebilmek için MySQL veritabanı kullanılmıştır.

## Veritabanı Yapısı

Projede, öğrenci bilgileri, dersler, notlar ve ders programı gibi verilerin depolanabilmesi için çeşitli tablolar oluşturulmuştur. Aşağıda, kullanılan temel tablolara ait örnekler ve içerikleri yer almaktadır:

### Tablolar

Projede aşağıdaki tablolar kullanılmıştır:

![Tablo Görselleri](https://github.com/Kemalgnl/Ogrenci_portal_Bilgi_sistemi/assets/86780970/356844d0-f7c1-45a7-9766-cc22ae75d0b0)
![Tablo Görselleri](https://github.com/Kemalgnl/Ogrenci_portal_Bilgi_sistemi/assets/86780970/0fc4d46b-0587-44d6-a974-e50a0feee7ae)

Bu tablolarda, öğrencilerin ve derslerin bilgileri yer almaktadır. İlk etapta, dersler ve bazı veriler manuel olarak eklenmiştir.

![Ders Ekleme Görseli](https://github.com/Kemalgnl/Ogrenci_portal_Bilgi_sistemi/assets/86780970/6b9a50a7-361c-440a-933a-71c0a42087af)

### Dersler Tablosu

Dersler tablosunda her döneme ait dersler yer almaktadır. Bu dersler, öğrenci portalında kullanılacak olan derslerdir.

![Dersler Tablosu Görseli](https://github.com/Kemalgnl/Ogrenci_portal_Bilgi_sistemi/assets/86780970/d7dd581e-79f4-4fc0-a24a-a39d3cccf536)

### Notlar Tablosu

Notlar tablosuna, her derse ait notlar rastgele eklenmiştir. Bu veriler, öğrencilere ait başarı notlarını içerir.

![Notlar Tablosu Görseli](https://github.com/Kemalgnl/Ogrenci_portal_Bilgi_sistemi/assets/86780970/cf4f424a-b5dc-4ba9-bb3b-27a7bd7a0df4)

### Ders Programı

Ders programı oluşturmak amacıyla sınıf ve ders saatleri verileri eklenmiştir. Bu veriler, öğrencilerin ders programlarını oluşturmak için kullanılır.

## C# Form Tasarımı

C# Windows Form uygulaması ile tasarlanan öğrenci portalı, kullanıcı dostu bir arayüze sahip olacak şekilde düzenlenmiştir. 

### Giriş Ekranı

Öğrenciler ve personel için giriş ekranları hazırlanmıştır. Kullanıcılar, sistemdeki bilgilerle giriş yaptıktan sonra, portalın iç yapısına erişebilirler.

![Giriş Ekranı Görseli](https://github.com/Kemalgnl/Ogrenci_portal_Bilgi_sistemi/assets/86780970/021a7eec-1785-4287-8959-6b883ea9ff7b)
![Giriş Ekranı Görseli](https://github.com/Kemalgnl/Ogrenci_portal_Bilgi_sistemi/assets/86780970/b6e8dd2f-36bc-42e3-877a-b93a47eb99f7)

### Öğrenci Portalı

Öğrenci portalında, öğrencilerin derslerini, notlarını ve diğer eğitim bilgilerini görüntülemeleri sağlanır. Aşağıdaki görsellerde, öğrenci portalının iç yapısına dair örnekler yer almaktadır:

![Öğrenci Portalı Görseli](https://github.com/Kemalgnl/Ogrenci_portal_Bilgi_sistemi/assets/86780970/5d998977-03f2-4f29-bd07-cdd714d08526)
![Öğrenci Portalı Görseli](https://github.com/Kemalgnl/Ogrenci_portal_Bilgi_sistemi/assets/86780970/e87239ab-cb5a-47fa-9a28-993430309130)

### Öğretmen Paneli

Öğretmenler için ayrı bir panel tasarlanmış olup, öğretmenler derslere ait bilgileri ve öğrenci notlarını buradan yönetebilirler.

![Öğretmen Paneli Görseli](https://github.com/Kemalgnl/Ogrenci_portal_Bilgi_sistemi/assets/86780970/6cec103d-760b-4048-9c51-ebe166a3d322)
![Öğretmen Paneli Görseli](https://github.com/Kemalgnl/Ogrenci_portal_Bilgi_sistemi/assets/86780970/6463a44d-3612-4aec-bc9c-fd609c5ab9c3)
