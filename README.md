# 🍝 Dining-Philosophers

> Dining Philosophers problemi üzerine geliştirilen, eşzamanlılık (concurrency) ve thread yönetimini ele alan bir proje.

---

## 🚀 Proje Hakkında

Klasik "Dining Philosophers" problemini çözmeyi amaçlayan bir projedir. Amaç:

* 🧠 Deadlock önlemek
* ⚡ Thread senkronizasyonu sağlamak
* 🍴 Filosofların doğru şekilde yemek yemesini yönetmek

Her filozof:

* Düşünür
* Yemek yer
* Uyur

---

## 🧱 Kullanılan Teknolojiler

* C / C++98
* Threads (pthread)
* Mutex
* Concurrency & synchronization

---

## ⚙️ Özellikler

✔️ Thread bazlı yapı
✔️ Mutex ile kaynak yönetimi
✔️ Deadlock prevention
✔️ Starvation kontrolü
✔️ Gerçek zamanlı loglama

---

## 🧠 Problem Tanımı

Filozoflar yuvarlak bir masada oturur ve:

* Her iki filozof arasında 1 adet çatal bulunur
* Yemek yemek için 2 çatal gerekir

Amaç:

* Hiçbir filozof aç kalmamalı
* Sistem deadlock’a girmemeli

---

## 🧩 Kullanılan Algoritma

Proje şu mantık üzerine kuruludur:

* Her filozof bir thread olarak çalışır
* Forklar mutex ile korunur
* Filozoflar belirli bir sırayla fork almaya çalışır

---

## 📊 Durumlar

Her filozofun durumu:

* 🧠 THINKING
* 🍴 EATING
* 😴 SLEEPING
* 💀 DIED

---

## 🧠 Öğrendiklerim

* Thread yönetimi
* Mutex kullanımı
* Deadlock ve race condition kavramları
* Senkronizasyon teknikleri
* Gerçek zamanlı sistem davranışı

---

![An_illustration_of_the_dining_philosophers_problem](https://github.com/user-attachments/assets/c60a136c-432c-4c33-ad3e-11bbe9535700)
