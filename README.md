# Patikadev-Veri-Bilimi-Giri-Projesi

## Veriyi Model İçin Bölmek

* Elimizdeki veriler birbirine benzer veya benzer olmayabilir.

* Bunun için veriyi en verimli şekilde kullanmalıyız.

* Modelimizden çıkacak sonuçlar gerçek sonuçlarla örtüşmelidir.

* Bunun için elimizdeki veriyi 3'e bölmeliyiz.

* "Train", "Validation", "Test" olarak.

* Verileri bu 3 kategoriye öyle bir dağıtmalıyız ki model verimli olsun.

### Veriyi Dağıtmak

* Bir veri grubunda verilerin birbirine çok benzemesine overfit deriz.

* Train veri grubu overfit veriler içermelidir.

* Validation sınama grubudur ve verileri dolaylı olarak overfit olmalıdır.

* Validation Grubun'da modelimizi ölçeriz, eksiğini gideriririz.

* Test grubunda ise overfit olmayan veriler denenir ve objektif cevap alınır.

* Bu dağılım iyi olursa modelimiz verimli çalışır.