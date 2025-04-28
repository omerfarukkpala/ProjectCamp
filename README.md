 # Asp.Net Mvc ile Teknoji Sözlük Uygulaması Geliştirme                                                                                     
                                                        
Bu proje, Mvc dünyasına kurumsal mimari ile code first yaklaşımını kullanarak oluşturulan bir projedir.Asp.Net Mvc kullanarak bir  Sözlük benzeri uygulama geliştirmeyi ele alır. Projede kullanılan teknolojiler arasında Asp.Net Mvc, SQL Server, Entity Framework, Bootstrap, Fluent Validation ve N-Tier Architecture(Katmanlı Mimarisi) bulunmaktadır.      
                               
                              
https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/ac124791-030b-467a-bb8c-d3ca18776a41  
     
                           
                         
                    
## Proje Detayları :       
   
### 1. Model-View-Controller (MVC) Mimarisi:
  
Projede MVC mimarisini kullanarak kodu modüler hale getiriyoruz. Model, View ve Controller bileşenlerini ayrı tutarak geliştirme sürecini daha organize hale getiriyoruz.

### 2. Bootstrap ile Kullanıcı Arayüzü Tasarımı:

Kullanıcı arayüzü tasarımında Bootstrap CSS framework'ünü kullanarak modern ve responsive bir tasarım oluşturuyoruz. Bu sayede uygulamamız farklı cihazlarda ve ekran boyutlarında uyumlu olacak.

### 3. Fluent Validation ile Veri Doğrulama:

Kullanıcı girişlerinin doğrulanması için Fluent Validation kütüphanesini kullanıyoruz. Bu sayede gelen verilerin doğruluğunu sağlayarak güvenliği artırıyoruz.

### 4. Entity Framework (CodeFirst):

Veritabanı entegrasyonunu kolaylaştırmak için Entity Framework'ü CodeFirst yaklaşımıyla kullanıyoruz. Bu sayede C# sınıflarından veritabanı tablolarını otomatik olarak oluşturarak veritabanı işlemlerini yönetiyoruz.

### 5. N-Tier Architecture(Katmanlı Mimari):

Projeyi katmanlara ayırarak N-Tier Architecture prensiplerine uygun olarak geliştiriyoruz. Bu sayede projeyi modüler hale getiriyor, bakımını kolaylaştırıyor ve genişletilebilir bir yapı oluşturuyoruz.

## Kullanılan Teknolojiler:

- **C# (C Sharp):** Veri işleme, iş mantığı ve diğer uygulama katmanlarının geliştirilmesinde kullanılan programlama dili.
  
- **Asp.Net Mvc5:** Web uygulamaları geliştirmek için kullanılan bir framework.
  
- **SQL Server:** Veritabanı yönetim sistemi.
  
- **Entity Framework:** Veritabanı entegrasyonunu kolaylaştırmak için kullanılan bir ORM aracı.
  
- **Bootstrap:** Responsive ve modern web arayüzleri oluşturmak için kullanılan bir CSS framework'ü.
  
- **Fluent Validation:** Veri doğrulamasını gerçekleştirmek için kullanılan bir kütüphane.
  
- **N-Tier Architecture:** Projeyi modüler hale getiren ve bakımını kolaylaştıran bir mimari yaklaşım.

Bu proje, geliştirme sürecinde karşılaşılan temel mimari kavramları ve teknolojilerini öğrenmek için ideal bir örnek olacaktır. Uygulama geliştirme sürecinde adım adım ilerleyerek, bir web uygulamasını baştan sona nasıl geliştireceğinizi detaylı olarak öğreneceksiniz.


## Proje İçeriği

Bu proje, MVC (Model-View-Controller) mimarisi kullanılarak geliştirilmiş bir web uygulamasıdır. Projede, aşağıdaki 4 ana bölüm bulunmaktadır:

### 1. Admin Paneli 🛠

Admin paneli, projenin yönetimini sağlayan bir arayüzdür. Admin kullanıcılarına özel olarak tasarlanmıştır ve genellikle aşağıdaki özellikleri içerir:

- **CRUD İşlemleri:** Kullanıcı ekleme, düzenleme ve silme işlemleri gibi temel veritabanı işlemlerini gerçekleştirme yeteneği.
  
- **Mesaj Yönetimi:** Kullanıcılar arasındaki mesajlaşma sisteminin yönetimi, mesajları görüntüleme ve yanıtlama yeteneği.
  
- **Site İstatistikleri:** Site ile ilgili istatistiklerin görüntülenmesi, ziyaretçi sayıları, en popüler içerikler gibi bilgilerin takibi.
- **Yetkilendirmeler:** Farklı kullanıcı rollerine göre erişim yetkilerini yönetme imkanı sağlar.
- **Galeri Yönetimi:** Projenin içeriğini zenginleştirmek için kullanılan görsellerin yönetimini sağlar.
- **Hakkımızda Sayfası Yönetimi:** Site hakkında bilgilerin bulunduğu "Hakkımızda" sayfasının içeriğini yönetir.
- **İletişim Mesajları Yönetimi:** Site ziyaretçileri tarafından gönderilen iletişim mesajlarının yönetimini sağlar.
- **Kategori Yönetimi:** İçeriklerin kategorize edilmesini sağlayan kategorilerin yönetimini sağlar.
- **Yazar Yönetimi:** Proje yazarlarının yönetimini sağlar.

### 2. Yazar Paneli 📝

Yazar paneli, kullanıcıların içerik eklemelerini ve düzenlemelerini sağlayan bir arayüzdür. Genellikle şu özellikleri içerir:

- **Yazı Oluşturma:** Yeni içeriklerin (makaleler, blog yazıları, vb.) oluşturulması.
- **Yazı Düzenleme:** Var olan içeriklerin düzenlenmesi ve güncellenmesi.
- **Yorum Yönetimi:** Kullanıcıların içeriklere yaptığı yorumların yönetimi, onaylama veya reddetme gibi işlemler.
- **Profilim:** Yazarın kişisel bilgilerini ve şifresini değiştirebilmektedir.
- **Başlıklarım:** Yazar kendi başlıklarını, başlıklarına yapılmış yorumları görebilir ve başlık işlemleri gerçekleştirebilir.
- **Tüm Başlıklar:** Sözlükteki aktif başlıkları görebilir, başlıklara yapılmış yorumları görebilir ve yorumlarını ekleyebilir.
- **Yazılarım:** Yazarın kendi yazılarını görebilir.
- **Mesajlar:** Kullanıcılar arasında mesajlaşmayı sağlar.

### 3. Sözlük 📖

Sözlük bölümü, projenin ana içeriğini oluşturan kısımdır. Genellikle şu özellikleri içerir:

- **Başlık Oluşturma:** Kullanıcıların yeni başlıklar oluşturmasına izin veren bir sistem.
  
- **Yorum Yapma:** Kullanıcıların başlıklara yorum eklemelerine izin verilir.
  
- **Başlık Arama:** Kullanıcıların başlıkları anahtar kelimelere veya kategorilere göre aramasını sağlayan bir arama özelliği.

### 4. Vitrin 🌟

Vitrin bölümü, projenin önemli içeriklerini veya duyurularını sergileyen bir alandır. Genellikle şu özellikleri içerebilir:

- **Öne Çıkan İçerikler:** Admin tarafından belirlenen ve önemli bulunan içeriklerin gösterilmesi.
  
- **Etkinlikler ve Duyurular:** Yaklaşan etkinliklerin veya projeye ait duyuruların yayınlanması.
  
- **Kullanıcı Geri Bildirimleri:** Kullanıcıların projeye ve içeriklere ilişkin geri bildirimlerini gösteren bir alan.

Bu bölümler, projenin farklı kullanıcı gruplarına yönelik özel arayüzler sunmasını sağlar ve uygulamanın işlevselliğini artırır.
Her bölüm, belirli bir kullanıcı veya rol tarafından erişilebilir ve ilgili işlevselliği sunar. Admin ve Yazar panelleri, ilgili kullanıcıların gereksinimlerine uygun olarak tasarlanmıştır. Bu bölümler, projenin yönetimi, içerik oluşturma/düzenleme ve kullanıcı etkileşimi gibi temel özelliklerini sağlar.

### Veritabanı ![image](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/654c10fa-e403-4c34-b208-3e99dec79287)

## Home ![direkanasayfa](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/c6591666-76c8-4ad9-9599-1347451c8da0)
## Default Headings ![default heading](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/b7d44a9f-8c0a-4745-9621-8c5753c66de3)
## Default Heading 2 ![default](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/d539444b-0c79-4503-a052-49c09320bb8e)

## Admin Login  ![adminlogin](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/17532593-b726-4ccc-8bf8-b0096221d074)
https://localhost:44361/Login/Index

## Admin Category ![admincategory](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/ecb00683-ae30-4ec6-9e27-f4f236e2c857)
## Admin Category Add ![image](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/71552bdc-5ba2-4cbb-ace0-9993fb903638)
## Admin Heading 
/Heading/Index/
![HeadingIndex](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/bfc92e08-b681-4b46-9e56-367267a11f4a)

## Admin New Heading 
![image](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/851a7527-27e3-432a-8dbe-5e7c4caf5730)


## Admin Heading Edit
https://localhost:44361/Heading/EditHeading/1
![adminheadingg](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/ff0219ab-108a-4cba-af78-96047ec0b89c)

## Admin Category Edit 
AdminCategory/EditCategory/1
![screencapture-localhost-44361-AdminCategory-EditCategory-1-2024-03-10-14_12_11](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/a5bb9f7c-a2d4-4b2b-a6e7-4f6c97ac1ad6)

## Admin Search 
ContentGetAllConten
![ContentGetAllContent](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/752c2fdb-d09a-48a2-930f-8759cbd58ece)

## Admin Writer Panel ![adminwriter](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/b23d1b3e-cca8-4b65-84a1-c73401ffdb9d)

## Admin Heading Report![adminheadingreport](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/c3ba562a-460f-4ac7-8b25-ee352137ab79)

## Admin Contact ![contact](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/df2b7fdd-226c-4cd3-9aa5-3809832e5120)

## Admin Authorization ![Authorizationadmin](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/9f57a5ac-600f-4278-878f-5ff9f1936c09)

## Admin Authorization Edit ![sifreee](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/6845b8f3-35a9-4a53-a122-b35457de0042)

## Admin Galley ![AdminGalley](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/27f42a5b-bad7-465c-a007-a84695be81ac)

## Admin SweetAlert ![image](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/625b37e8-d5da-4ae4-9ccc-b9b8b86d12b5)

## Admin Error Page ![eerre](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/e341fce5-1f3b-4538-9e14-2775a06a4393)

## Admin Skills Panel ![adminskills](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/ae7e989e-e497-46c3-a9f3-2576327e2cd4)




## Writer Login 
https://localhost:44361/Login/WriterLogin
![writerlogin](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/1504170a-a006-49b8-9901-c1fa5ef82920)

## Writer Profile ![writerprofile](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/b4a9ffe7-9bfc-4efb-9aae-8af41c565866)

## Writer Heading ![yaazarheading](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/e9691a99-23c6-4b51-997c-704f5812f427)

## Writer All Headings ![allheadings](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/fe4eb07e-c3c5-4dd5-8593-6f49f2078aad)

## Writer Panel Message ![WriterPanelMessage](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/2be897aa-db05-47a4-9532-d6ed09f17a63)

## Writer MyContent ![WriterPanelContentMyContent](https://github.com/omerfarukkpala/MvcProjectCamp/assets/101570820/4f8abe64-723f-4b5b-b232-72720e6ead15)


 
 
 
