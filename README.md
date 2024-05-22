Algoritma Projesi Dokümantasyonu
Bu doküman, NestJS (Backend) ve React (Frontend) teknolojileriyle geliştirilmiş olan Algoritma projesinin kurulumunu içermektedir. Proje MongoDB veritabanı kullanmaktadır.

Proje Kurulumu
Gereksinimler
Node.js (npm)
MongoDB Compass
NestJS CLI
Node.js
Node.js kurulumu için ilk olarak bu adrese giderek Current versiyonunu indirin.

Node.js kurulumunu tamamladıktan sonra terminalde node -v ve npm -v komutlarını kullanarak kurulumunuzu kontrol edebilirsiniz. Yüksek ihtimalle kusursuz kurulum gerçekleşmiş olacaktır. Eğer bilgisayarınızda zaten Node.js yüklü ise yeniden yüklemenize gerek yoktur, ancak sürümünün 18'den büyük olması yeterlidir.

MongoDB Compass
GUI Kurulumu için bu bağlantıyı kullanarak MongoDB Compass'ı indirin ve kurun.

Community Server Kurulumu için bu bağlantıyı kullanarak MongoDB'nin Community Edition'ını indirip kurun.

NestJS CLI
Bilgisayar terminalini açın ve npm i -g @nestjs/cli komutunu çalıştırın.

Not: Eğer "npm recognized" gibi bir hata alıyorsanız, bilgisayarınızı yeniden başlatın ve yeniden deneyin.

Proje Clone Kısmı
Mevcut Repository kısmından kodları zip olarak indirebilir veya GitHub üzerinden clone olarak alabilirsiniz.

Not: GitHub'dan clone işlemi yapabilmek için bilgisayarınızda git yüklü olmalıdır.

Proje Kurulduktan Sonra
Kullanılan IDE içerisinde 2 farklı terminal açın.

Terminal:

css
Kodu kopyala
cd frontend
npm i (hata verirse npm i --force)
npm run start
Terminal:

css
Kodu kopyala
cd backend
npm i (hata verirse npm i --force)
npm run start:dev
Bu adımlardan sonra projeniz, veritabanında, backend (NestJS) ve frontend (React) kısımlarında çalışacaktır.

Veritabanına Bağlanıp Verileri Görmek
MongoDB Compass uygulamasını açın.

Bağlantı için mongodb://localhost:27017 veya mongodb://localhost:27017/Algoritma adresini kullanarak MongoDB Compass ile veritabanına bağlanabilirsiniz.
