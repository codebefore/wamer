# Wamer - Prototip Gelistirme Plani

## Durum: Musteriye sorulacak (toplanti oncesi)

### Faz 1A - Prototipe Eklenmesi Gereken Ekranlar

- [ ] Siparis Listesi ekrani (planlamanin baslangic noktasi, siparis olusturma/import, durum takibi)
- [ ] Ana Veri ekrani (parca, makine, operator, vardiya tanimlari, operasyon rotasi)
- [ ] Is Emri Listesi ekrani (filtreleme, olusturma, partilere bolme, toplu durum guncelleme)
- [ ] Operator / Shopfloor ekrani (makine bazli is listesi, baslat/durdur/tamamla, adet girisi)

### Faz 1B - Mevcut Ekranlara Eklenecek Ozellikler

- [ ] Uretim Panosuna surukle-birak etkilesimi
- [ ] Uretim Panosuna setup suresi gosterimi ve alternatif makine onerisi
- [ ] Hazirlik kontrolu gostergeleri (planlama uzerine risk ikonlari: malzeme, takim, program)
- [ ] Gerceklesen veri giris ekrani (operasyon baslangic/bitis, adet, fire, durus nedeni)
- [ ] Dashboard'a "bugunun isleri" ve "termin riski" eklemeleri
- [ ] Is Emri Detayina siparis/ERP referansi baglantisi
- [ ] Kapasite ekranina gunluk kirilim ve makine grubu filtresi
- [ ] Shopfloor'a durus suresi gosterimi ve son 1 saatlik trend

### Faz 2 - Ikinci Dalga (MVP sonrasi)

- [ ] Kalite, fire ve rework modulu
- [ ] Admin ve yetki yonetimi (kullanici, rol, parametre, log)
- [ ] Otomatik cizelgeleme kurallari
- [ ] Setup optimizasyonu
- [ ] Malzeme yeterlilik kontrolu
- [ ] Takim omru / takim ihtiyac entegrasyonu
- [ ] ERP entegrasyon katmani (API/DB seviyesi)
- [ ] Ileri seviye KPI raporlari

## Musteriye Sorulacak Sorular

- Hangi ERP kullaniliyor?
- ERP'den hangi veriler alinabiliyor (API, DB, Excel)?
- Is emri ERP'de mi olusuyor, bu sistemde mi olusacak?
- Operasyon rotalari nerede tutuluyor?
- Veri toplama sistemi hangi verileri topluyor?
- Planlama ekrani mevcut mu, yoksa sifirdan mi isteniyor?
- Oncelik kurallari ve darbogaz makineler neler?
- Setup sureleri kritik mi?
- Vardiya bazli planlama gerekiyor mu?
- Proje sonunda ne duzelmis olmali? (gecikme, bos bekleme, Excel bagimliligi?)
