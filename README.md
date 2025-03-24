
# Deprem Büyüklüğü Tanımlayıcı Programı

## Amaç
Bu proje, kullanıcıdan alınan deprem büyüklüğüne göre uygun bir tanımlayıcı belirleyen basit bir programın geliştirilmesini amaçlamaktadır. Program, kullanıcı tarafından girilen deprem büyüklüğünü, Richter ölçeğine göre değerlendirerek büyüklüğüne uygun olan tanımlayıcıyı ekranda gösterecektir.

## Özellikler
- Kullanıcıdan deprem büyüklüğü (magnitude) girişi alır.
- Girilen büyüklüğün Richter ölçeğine göre aralıklarda hangi kategoride yer aldığını belirler.
- Deprem büyüklüğüne göre uygun tanımlayıcıyı ekranda gösterir.

## Kullanıcı Arayüzü
Program, komut satırında çalışan basit bir konsol uygulamasıdır. Kullanıcıdan deprem büyüklüğünü girmesi istenecektir ve bu büyüklük, ilgili tanımlayıcı ile birlikte ekranda gösterilecektir.

## Algoritma

1. Kullanıcıdan deprem büyüklüğü (magnitude) girişi alınır.
2. Girilen büyüklüğün, Richter ölçeğindeki aralıklara göre hangi kategoriye ait olduğu kontrol edilir:
    - Eğer büyüklük 2.0'dan azsa: "Micro - Mikro"
    - Eğer büyüklük 2.0 ile 3.0 arasındaysa: "Very minor - Çok küçük"
    - Eğer büyüklük 3.0 ile 4.0 arasındaysa: "Minor - Küçük"
    - Eğer büyüklük 4.0 ile 5.0 arasındaysa: "Light - Hafif"
    - Eğer büyüklük 5.0 ile 6.0 arasındaysa: "Moderate - Orta"
    - Eğer büyüklük 6.0 ile 7.0 arasındaysa: "Strong - Ağır"
    - Eğer büyüklük 7.0 ile 8.0 arasındaysa: "Major - Büyük"
    - Eğer büyüklük 8.0 ile 10.0 arasındaysa: "Great - Çok Büyük"
    - Eğer büyüklük 10.0'dan fazlaysa: "Meteoric - Meteorik"
3. Uygun tanımlayıcı ekranda yazdırılır.
4. Program sonlandırılır.



