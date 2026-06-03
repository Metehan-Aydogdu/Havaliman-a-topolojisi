# Havalimani-ag-topolojisi
Cisco Packet Tracer üzerinden havalimanı ağ simulasyonu tasarlanması.
 Bu proje, modern bir havalimanının karmaşık gereksinimlerini karşılamak üzere tasarlanmış kapsamlı bir ağ altyapısı sunmaktadır. BLM2006 – Bilgisayar Ağlarına Giriş dersi final projesi kapsamında Cisco Packet Tracer 8.x kullanılarak geliştirilmiştir.

 Bu depo (repository), hem hazırlanan ağ altyapısının dökümantasyonunu hem de sistemin yolcu ve IT personeli tarafında nasıl çalıştığını gösteren interaktif bir web arayüzü demosunu içermektedir.

  Temel Özellikler
 VLAN Segmentasyonu: Gelen/giden yolcular (VLAN 20, 21), idari personel (VLAN 99) ve yetkili sunucular (VLAN 50) için mantıksal ağ ayrımı yapılmıştır.
 Cisco ASA Firewall ve NAT: İç ağ ile İnternet arasındaki sınır güvenliği, dinamik NAT ve ACL politikaları ile Cisco ASA 5505 üzerinden sağlanmıştır.
 EtherChannel: Core Switch ile Access Switch'ler arasında bağlantı yedekliliği ve bant genişliği artırımı uygulanmıştır.
 WLC Entegrasyonu: Havalimanı içindeki Access Point'lerin CAPWAP üzerinden merkezi yönetimi gerçekleştirilmiştir.
 Port Security: Switch portlarında yetkisiz MAC adresleri engellenmiş, ihlal durumunda portların kapatılması (shutdown) sağlanmıştır.
 DHCP ve DNS Servisleri: Core switch üzerinden otomatik IP ataması yapılmış ve merkezi DNS sunucusu kurulmuştur.
 Kullanılan Araçlar
 Ağ Simülasyonu: Cisco Packet Tracer 8.x
 Arayüz (Demo): HTML5, CSS3, JavaScript
