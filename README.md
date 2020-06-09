# II-hafta-7-haziran-ders-icerigi

# 7  HAZİRAN 2020 / 10:00 / Kodluyoruz .Net Core Bootcamp

## Ders Akışı 
1. [Oreilly](https://www.oreilly.com/) Online Ek Kaynağı gösterildi. <br/>
2. Şahin Yanlık ‘ın başlatmış olduğu aspnet core gitbook kaynağı incelenmeye başlandı.<br/>
 - https://github.com/sahinyanlik
 - https://sahinyanlik.gitbooks.io/kisa-asp-net-core-kitabi/
 - https://nbarbettini.gitbooks.io/little-asp-net-core-book/content/
3. Visual Studio’nun İlk Projesinin açılması <br/>
4. Razor Pages Nedir? (ödev verildi). <br/>
5. 4 Farklı Projede Yapılacak : *Change Authentication* <br/>
  -  No Authentication <br/>
  - Individual User Account <br/> 
  - Work or School Accounts <br/>
  - Windows Authentication seçili projeler oluşturulmalı <br/>
6. Ayarlardaki *Output* kısmındaki Console Application nedir? diğerleri (Windows Application-Class Library)  arasında fark nedir?
 (araştırma ödev verildi ). <br/>
İlgili Sekme: <br/>

  Projeye Sağ Tıklanır ve Properties penceresi açılır. Application sekmesi altındaki Output type: açılır menüsü altındaki <br/>
 - Console Application <br/>
 - Windows Application <br/>
 - Class Library <br/>
7. appsettings.json dosyası neden kullanılır? (araştırma ödevi) <br/>
8. Kestrel Nedir? <br/>
9. c# json serialize / deserialize  () <br/>
* [Newtonsoft](https://www.newtonsoft.com/json)--> Json.NET <br/>
Rest servisleri ne / restful servisleri nedir? (araştırma ödevi) <br/>
- restful vs soap <br/>
- restful vs grpc <br/>
- restful vs graphql <br/>
10. Dependency Injection Nedir? <br/>
11. IHostBuilder interfacesinden Build() methodu ile IHost() dönmeye başladı void Run methodu ile dönüyor. <br/>
 * IHostBuilder ve HostBuilder Nedir? ( araştırma ödev) <br/>
12. MVC’nin açıklanması <br/>
13. Loosely coupled vs tightly coupled ( araştırma ) <br/>
14. nullable object c# neden? ->  <br/>
15. [asp.net core Request Processing Pipeline](https://dotnettutorials.net/lesson/asp-net-core-request-processing-pipeline/#:~:text=The%20ASP.NET%20Core%20request%20processing%20pipeline%20consists%20of%20a,component%20using%20the%20next%20delegate.)<br/>
16. Middleware üzerinden işlemlerin gerçekleştiğini bilinmeli <br/>
17. İhtiyaç olduğunda Customize edilmiş Middleware’ler yazılır. <br/>
18. Owin and Katana ile SignalR arasında ne ilişki var? (incelenmeli). <br/>
19. Startup.cs -> UseEndpoints routing ile ilgili ayarlamalar başlangıç controllerini kavrama <br/>
20. controller boş index dolu halinde nereyi açıyor? <br/>
21. controller içine testaction adında bir action oluşturuyoruz. <br/>
  * ilk aşamada view ini oluşturmayıp bir hata alıp çıkan hata kısımlarını inceliyoruz <br/>
  * ardından action üzerine sağ tıklayıp Add New Scaffold Item üzerinden bir Razor View  projesi açıyoruz. <br/> 
22. ViewEngines ve Razor ViewEngine nedir araştır?  <br/>
23. Responsive Design ( Bootstrap Kütüphanesi ) <br/>
24. Katmanlı Mimari: n-tier vs tree-tier nedir? <br/>
   n-layer architecture <br/>
  * Data Access Layer - DAL <br/>
  * Business Logic Layer - BLL <br/>
  * Presentation Layer - PL  <br/>
25. input sterilizasyonu veya cross-site request forger(XSRF) (okunup incelenmeli) <br/>
26. Breakpoint Nedir? <br/>
27. .NET Core ve .NET Standart <br/>
28. MVC vs MVVM  MVP vs MVW vs MVU Pattern arasındaki farkı araştır. <br/>
  - Model-View-Update (MVU) nedir? <br/> 
29. Projelerin Github üzerinde yayınlanması işlendi ve bitirildi. <br/>

## Ödevler:
--- Razor Pages Nedir? <br/>
--- 4 Farklı Projede Yapılacak *Change Authentication* : <br/>
- No Authentication <br/>
- Individual User Account <br/>
- Work or School Accounts <br/>
- Windows Authentication seçili projeler oluşturulmalı <br/>
--- Ayarlardaki Output kısmındaki Console Application nedir? diğerleri arasında fark nedir? ( araştırma ödev verildi ). <br/>
   İlgili Sekme: <br/>
   Projeye Sağ Tıklanır ve Properties penceresi açılır. Application sekmesi altındaki Output type: açılır menüsü altındaki  <br/>
    * Console Application <br/>
    * Windows Application <br/>
    * Class Library <br/>

--- c# json serialize / deserialize <br/>
--- MVC vs MVVM  MVP vs MVW vs MVU Pattern arasındaki farkı araştır. <br/>
        * Model-View-Update (MVU) nedir?  <br/>
