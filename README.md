# Faster-R-CNN-ile-Derin-Ogrenme-Tabanli-Nesne-Tespiti-ve-Dogruluk-Analizi

Faster R-CNN Evrişimsel sinir ağı üzerinde geliştirilen modelin derin öğrenme yöntemleri ile doğruluk tahmini ve analizi: Nesne Tespiti Uygulaması

Accuracy Estimation and Analysis of The Model Developed on The Faster R-CNN Evolutionary Neural Network Using Deep Learning Methods: Object Detection Application

Authors

•	Okan Yılmaz
Department of Computer Engineering, Faculty of Engineering and Architecture, Istanbul Gelisim University, Istanbul, Turkey

•	Hakan Aydın
Department of Computer Engineering, Faculty of Engineering, Istanbul Topkapı University, Istanbul, Turkey

•	Ali Çetinkaya
Department of Electronics Technology, Istanbul Gelisim Vocational School, Istanbul Gelisim University, Istanbul, Turkey

For Correspondence: alcetinkaya@gelisim.edu.tr

Article Information

•	Received: June 23, 2020

•	Accepted: December 5, 2020

•	DOI: 10.31590/ejosat.753896

•	Full Article Access Link: [Faster R-CNN Evrişimsel sinir ağı üzerinde geliştirilen modelin derin öğrenme yöntemleri ile doğruluk tahmini ve analizi: Nesne Tespiti Uygulaması](https://dergipark.org.tr/en/pub/ejosat/article/753896)

Özet

Nesne tanıma, görüntü işleme, tahmin etme gibi birçok konuya ev sahipliği yapan derin öğrenme gün geçtikçe insanoğlunun ihtiyacı haline gelmeye başlamıştır. Bu çalışmada derin öğrenme teknikleri kullanılarak nesne tanıma işlemi yaptırılmaktadır. Faster R-CNN (Faster Region Based Convolutional Networks) ağı kullanılarak geliştirilen ve çalışma içerisinde 502 adet görüntü bulunan “Bardak” veri seti oluşturulmuştur. Oluşturulan bu veri setinin bir kısmı test için diğer bir kısmını ise eğitim yaptırmak amacıyla ikiye ayrılarak kullanılmıştır. Farklı deneyler yaparak bardağı hangi şekillerde tanıyıp, tanıyamadığını gözlemledikten sonra doğruluk tahmin oranını nasıl arttırılabileceği konusunda önerilerde bulunulmuştur. Nesne tanıma yaparken fotoğraf, video ve anlık olarak görüntü alabileceğimiz web cam seçeneklerinin bulunduğu ara yüz tasarlanmıştır. Ara yüz tasarlanırken Python kütüphanesi olan Tkinter kütüphanesinden yararlanılmıştır. Nesne tespiti yapılacak olan görüntü, yapılan işlemlerin ardından eğer fotoğraf ise nesnenin üzeri çerçeve haline alınarak yüzde kaç oranında doğru tahmin ettiği yazılı olan bir fotoğraf kaydedilmektedir. Nesne tespiti yapılacak olan görüntü video ise video oynatılırken video üzerindeki nesne çerçeve halinde yüzde kaç oranında tahmin ettiği yazılı olacak, web cam ise anlık olarak görüntü içerisindeki nesneyi çerçeve içerisine alarak ekranda göstermeye devam edecektir.

Object Detection API kullanılarak gerçekleştirilen bu çalışmada, farklı epoch değerleri ile modeli eğitip, en doğru oranla tahmin yapan epoch değeri bulunmaya çalışılmıştır. Gerçekleştirilen 18 ayrı deney üzerinde oluşturulan veri seti üzerinde derin öğrenme ve Faster R-CNN kullanılarak gerçekleştirilmiştir. Eğitim sürecinde en başarılı tahmin oranının bulunması için ise farklı epoch sayılarıyla deneyler gerçekleştirilmiştir. Yapılan toplam 100.000 Epoch’luk eğitimin sonucunda elde edilen başarı sonucu 0,97835‬ ve loss oranı 0,02165’dir.

Anahtar Kelimeler: Faster R-CNN, Nesne tanıma, Object Detection API



