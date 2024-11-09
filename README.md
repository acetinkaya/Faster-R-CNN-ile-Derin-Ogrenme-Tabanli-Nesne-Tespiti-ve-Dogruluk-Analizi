# Faster-R-CNN-ile-Derin-Ogrenme-Tabanli-Nesne-Tespiti-ve-Dogruluk-Analizi

Faster R-CNN Evrişimsel sinir ağı üzerinde geliştirilen modelin derin öğrenme yöntemleri ile doğruluk tahmini ve analizi: Nesne Tespiti Uygulaması

Accuracy Estimation and Analysis of The Model Developed on The Faster R-CNN Evolutionary Neural Network Using Deep Learning Methods: Object Detection Application

Authors:

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

Özet:

Nesne tanıma, görüntü işleme, tahmin etme gibi birçok konuya ev sahipliği yapan derin öğrenme gün geçtikçe insanoğlunun ihtiyacı haline gelmeye başlamıştır. Bu çalışmada derin öğrenme teknikleri kullanılarak nesne tanıma işlemi yaptırılmaktadır. Faster R-CNN (Faster Region Based Convolutional Networks) ağı kullanılarak geliştirilen ve çalışma içerisinde 502 adet görüntü bulunan “Bardak” veri seti oluşturulmuştur. Oluşturulan bu veri setinin bir kısmı test için diğer bir kısmını ise eğitim yaptırmak amacıyla ikiye ayrılarak kullanılmıştır. Farklı deneyler yaparak bardağı hangi şekillerde tanıyıp, tanıyamadığını gözlemledikten sonra doğruluk tahmin oranını nasıl arttırılabileceği konusunda önerilerde bulunulmuştur. Nesne tanıma yaparken fotoğraf, video ve anlık olarak görüntü alabileceğimiz web cam seçeneklerinin bulunduğu ara yüz tasarlanmıştır. Ara yüz tasarlanırken Python kütüphanesi olan Tkinter kütüphanesinden yararlanılmıştır. Nesne tespiti yapılacak olan görüntü, yapılan işlemlerin ardından eğer fotoğraf ise nesnenin üzeri çerçeve haline alınarak yüzde kaç oranında doğru tahmin ettiği yazılı olan bir fotoğraf kaydedilmektedir. Nesne tespiti yapılacak olan görüntü video ise video oynatılırken video üzerindeki nesne çerçeve halinde yüzde kaç oranında tahmin ettiği yazılı olacak, web cam ise anlık olarak görüntü içerisindeki nesneyi çerçeve içerisine alarak ekranda göstermeye devam edecektir.

Object Detection API kullanılarak gerçekleştirilen bu çalışmada, farklı epoch değerleri ile modeli eğitip, en doğru oranla tahmin yapan epoch değeri bulunmaya çalışılmıştır. Gerçekleştirilen 18 ayrı deney üzerinde oluşturulan veri seti üzerinde derin öğrenme ve Faster R-CNN kullanılarak gerçekleştirilmiştir. Eğitim sürecinde en başarılı tahmin oranının bulunması için ise farklı epoch sayılarıyla deneyler gerçekleştirilmiştir. Yapılan toplam 100.000 Epoch’luk eğitimin sonucunda elde edilen başarı sonucu 0,97835‬ ve loss oranı 0,02165’dir.

Anahtar Kelimeler: Faster R-CNN, Nesne tanıma, Object Detection API

Abstract:

Deep learning, which is home to many subjects such as object recognition, image processing, forecasting, has become a human need. In this study, object recognition is performed using deep learning techniques. Faster R-CNN (Faster Region Based Convolutional Networks) Network has developed and 502 images in the study “Cup” data set has created. Some of this data set has used for testing and the other for training. After observing the ways in which the glass can be recognized and not recognized by conducting different experiments, suggestions have made on how to increase the accuracy prediction rate. The Python library Tkinter library has used when designing the interface. The image that is to be detected is taken into a frame after the operations done, and a photograph is recorded with the correct estimate of the percentage of the image. If the video is the image that will be detected, the video will be displayed on the screen, while the video will be played, and the web cam will instantly display the object in the image in the frame.

In this study, which has performed using Object Detection API, we tried to find the epoch value that trains the model with different epoch values and makes the most accurate predictions. It has conducted using deep learning and Faster R-CNN on the data set generated over 18 separate experiments performed. In order to find the most successful prediction rate in the training process, experiments has conducted with different epoch numbers. A total of 100.000 Epoch's has achieved as a result of the education and the result of success is 0.97835 and loss ratio is 0.02165.

Keywords: Faster R-CNN, Object detection, Object Detection API

How to Cite

•	IEEE: O. Yilmaz, H. Aydin, and A. Çeti̇nkaya, “Faster R-CNN Üzerinde Geliştirilen Model ile Object Detection Api Üzerinde Doğruluk Tahmini ve Analizi,” European Journal of Science and Technology, Dec. 2020, doi: 10.31590/ejosat.753896.

•	APA: Yılmaz, O., Aydın, H., & Çetinkaya, A. (2020). Faster R-CNN Evrişimsel Sinir Ağı Üzerinde Geliştirilen Modelin Derin Öğrenme Yöntemleri ile Doğruluk Tahmini ve Analizi: Nesne Tespiti Uygulaması. Avrupa Bilim Ve Teknoloji Dergisi(20), 783-795. https://doi.org/10.31590/ejosat.753896

•	MLA: Yılmaz, Okan, Hakan Aydın, and Ali Çetinkaya. "Faster R-CNN Evrişimsel sinir ağı üzerinde geliştirilen modelin derin öğrenme yöntemleri ile doğruluk tahmini ve analizi: Nesne Tespiti Uygulaması." Avrupa Bilim ve Teknoloji Dergisi 20 (2020): 783-795. 

License:

This work is licensed under a Creative Commons Attribution-Non Commercial 4.0 International License, allowing non-commercial sharing and adaptation with proper attribution.


