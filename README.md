# 7  HAZİRAN 2020 / 10:00 / Kodluyoruz .Net Core Bootcamp
.
## Ders Akışı 
1. [Oreilly](https://www.oreilly.com/) Online Ek Kaynağı gösterildi.
2. Şahin Yanlık ‘ın başlatmış olduğu aspnet core gitbook kaynağı incelenmeye başlandı.
   - https://github.com/sahinyanlik
   - https://sahinyanlik.gitbooks.io/kisa-asp-net-core-kitabi/
   - https://nbarbettini.gitbooks.io/little-asp-net-core-book/content/
3. Visual Studio’nun İlk Projesinin açılması
4. Razor Pages Nedir? (ödev verildi).
5. 4 Farklı Projede Yapılacak : *Change Authentication*
   - [ ] No Authentication
   - [ ] Individual User Account 
   - [ ] Work or School Accounts
   - [ ] Windows Authentication seçili projeler oluşturulmalı <br/>
6. Ayarlardaki *Output* kısmındaki Console Application nedir? diğerleri (Windows Application-Class Library)  arasında fark nedir?
 (araştırma ödev verildi ).
   > İlgili Sekme: Projeye Sağ Tıklanır ve Properties penceresi açılır. Application sekmesi altındaki Output type: açılır menüsü altındaki
   - Console Application
   - Windows Application
   - Class Library
7. appsettings.json dosyası neden kullanılır? (araştırma ödevi)
8. Kestrel Nedir?
9. c# json serialize / deserialize
    - * [Newtonsoft](https://www.newtonsoft.com/json)--> Json.NET
10. Rest servisleri ne / restful servisleri nedir? (araştırma ödevi)
    - restful vs soap
    - restful vs grpc
    - restful vs graphql
11. Dependency Injection Nedir?
12. IHostBuilder interfacesinden Build() methodu ile IHost() dönmeye başladı void Run methodu ile dönüyor.
    - * IHostBuilder ve HostBuilder Nedir? ( Araştırma ödevi)
13. MVC’nin açıklanması
14. Loosely coupled vs tightly coupled ( Araştırma )
15. nullable object c# neden?
16. [asp.net core Request Processing Pipeline](https://dotnettutorials.net/lesson/asp-net-core-request-processing-pipeline/#:~:text=The%20ASP.NET%20Core%20request%20processing%20pipeline%20consists%20of%20a,component%20using%20the%20next%20delegate.)
17. Middleware üzerinden işlemlerin gerçekleştiğini bilinmeli
18. İhtiyaç olduğunda Customize edilmiş Middleware’ler yazılır.
19. Owin and Katana ile SignalR arasında ne ilişki var? (incelenmeli).
20. Startup.cs -> UseEndpoints routing ile ilgili ayarlamalar başlangıç controllerini kavrama
21. controller boş index dolu halinde nereyi açıyor?
22. controller içine testaction adında bir action oluşturuyoruz.
    - * ilk aşamada view ini oluşturmayıp bir hata alıp çıkan hata kısımlarını inceliyoruz
    - * ardından action üzerine sağ tıklayıp Add New Scaffold Item üzerinden bir Razor View  projesi açıyoruz.
23. ViewEngines ve Razor ViewEngine nedir araştır?
24. Responsive Design ( Bootstrap Kütüphanesi ) <br/>
25. Katmanlı Mimari: n-tier vs tree-tier nedir? n-layer architecture
    - Data Access Layer - DAL 
    - Business Logic Layer - BLL
    - Presentation Layer - PL
26. input sterilizasyonu veya cross-site request forger(XSRF) (okunup incelenmeli)
27. Breakpoint Nedir?
28. .NET Core ve .NET Standart
29. MVC vs MVVM  MVP vs MVW vs MVU Pattern arasındaki farkı araştır.
    - Model-View-Update (MVU) nedir? <br/> 
30. Projelerin Github üzerinde yayınlanması işlendi ve bitirildi.

## Ödevler:
- [ ] Razor Pages Nedir?
- [ ] 4 Farklı Projede Yapılacak *Change Authentication* :
  - [ ] No Authentication
  - [ ] Individual User Account
  - [ ] Work or School Accounts
  - [ ] Windows Authentication seçili projeler oluşturulmalı
- [ ] Ayarlardaki Output kısmındaki Console Application nedir? diğerleri arasında fark nedir? [Ders Akışındaki 6. Madde'yi inceleyin.] ( araştırma ödev verildi ).
- [ ] c# json serialize / deserialize
- [ ] MVC vs MVVM
   - [ ] MVP vs MVW vs MVU Pattern arasındaki farkı araştır
   - [ ] Model-View-Update (MVU) nedir?
