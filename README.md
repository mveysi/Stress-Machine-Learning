# PROJE AMACI 

Proje insanın fiziksel aktivitesine dayalı olarak stres seviyelerinin tespit edilip analiz edildiği bir projedir. Burada kullandığımız veri seti insan vücudu nemi, vücut sıcaklığı ve kullanıcının attığı adım sayısı ile ilgili 4 değişken ve 2001 değerden oluşmaktadır.
Stresin düşük stres, normal stres ve yüksek stres olmak üzere üç farklı sınıflandırması yapılmıştır.

Proje de makine öğrenmesindeki sınıflandırma modelleri denenmiştir ve bunun sonucunda en verimli olarak Lojistik Regresyon seçilmiştir. Daha farklı modeller de kullanılabilir.

![stres](https://github.com/user-attachments/assets/8848d8c2-2500-4072-8447-915c465b75b1)

# Veri Seti 📑

Bu verilerin nasıl analiz edildiğiyle ilgili daha fazla bilgi için şu kaynağa başvurabilirsiniz:
“L. Rachakonda, S. P. Mohanty, E. Kougianos, and P. Sundaravadivel, “Stress-Lysis: A DNN-Integrated Edge Device for Stress Level Detection in the IoMT,” IEEE Trans. Conum. Electron., vol. 65, no. 4, pp. 474–483, 2019.” 
1.	L. Rachakonda, S. P. Mohanty, E. Kougianos, and P. Sundaravadivel, “Stress-Lysis: A DNN-Integrated Edge Device for Stress Level Detection in the IoMT,” IEEE Trans. Conum. Electron., vol. 65, no. 4, pp. 474–483, 2019.
2.	L. Rachakonda, P. Sundaravadivel, S. P. Mohanty, E. Kougianos, and M. Ganapathiraju, “A Smart Sensor in the IoMT for Stress Level Detection”, in Proceedings of the 4th IEEE International Symposium on Smart Electronic Systems (iSES), 2018, pp. 141--145.

| Değişken | Değişken amacı | 
|----------|----------------|
|Humidity| Nem |
|Temperature| Sıcaklık |
|Step count| Adım sayısı |
|Stress levels(Target)| Stres seviyeleri (Hedef değişken)|
