Port Tarama ve Servis Tespit Aracı

Temel Bilgiler

Proje Adı: Port Tarama ve Servis Tespit Aracı

Öğrenci Adı ve Numarası: Fatih Sultan Nakit - 2320191078

Teslim Tarihi: 30-01-2025

Projenin Amacı ve Kapsamı

Bu proje, ağ üzerindeki açık portları taramak, çalıştırılan servislerin sürümlerini tespit etmek ve güvenlik zafiyetlerini belirlemek amacıyla geliştirilmiştir.

Çözülen Güvenlik Problemi

Açık portların tespiti ve güvenlik analizleri ile saldırılara karşı önlem alınmasını sağlar.

Hedef Kitle ve Kullanım Alanları

Siber güvenlik uzmanları: Güvenlik açıklarını tespit etmek için kullanabilir.

Ağ yöneticileri: Kurumsal ağ güvenliğini sağlamak için portları analiz edebilir.

Güvenlik analistleri: Çalıştırılan servislerin versiyonlarını belirleyerek zafiyet analizleri gerçekleştirebilir.

Teknik Gereksinimler

Kullanılan Programlama Dili: Python

Gerekli Kütüphaneler ve Sürümleri:

GEREKLI_KUTUPHANELER = {
    "socket": "Yerleşik Python Modülü",
    "threading": "Yerleşik Python Modülü",
    "nmap": "python-nmap 0.7.1"
}

Çalışma Ortamı Gereksinimleri:

İşletim Sistemleri: Windows / Linux / macOS

Dış Bağımlılıklar:

Nmap komut satırı aracının sistemde yüklü olması gerekmektedir.

Python-nmap kütüphanesinin yüklü olması gerekir (pip install python-nmap).

Açıklama

Bu proje, ağ güvenliği ve siber güvenlik alanında çalışanlar için bir Port Tarama ve Servis Tespit Aracı geliştirmeyi amaçlamaktadır. Araç, açık portları tarayarak çalışan servislerin sürümlerini belirlemekte ve olası güvenlik zafiyetleri ile eşleştirme yapmaktadır.

Özellikler

Akıllı Port Tarama: Belirtilen IP adresinde açık portları tespit eder.

Servis Versiyon Tespiti: Açık portlarda çalışan servislerin isimlerini ve sürümlerini belirler.

Zafiyet Eşleştirme: Tespit edilen servisleri, bilinen güvenlik açıklarıyla eşleştirme yaparak bilgi sağlar.

Kullanım Alanları

Bu araç, aşağıdaki alanlarda aktif olarak kullanılabilir:

Ağ Güvenliği Analizi: Açık portların tespitiyle potansiyel saldırı vektörlerini belirleyerek ağ güvenliğini artırmak.

Sızma Testleri (Penetration Testing): Bir sistemin saldırılara karşı ne kadar savunmasız olduğunu görmek için test aracı olarak kullanılır.

Sistem Yönetimi: Ağ yöneticileri, sistemlerinde çalışan servisleri kontrol etmek ve gereksiz açıkları kapatmak için kullanabilir.

Güvenlik Açıklarının Belirlenmesi: Belirli servislerin bilinen zafiyetleri ile eşleşmesi sağlanarak, sistemin güvenliğini artırmak için alınması gereken önlemler belirlenebilir.
