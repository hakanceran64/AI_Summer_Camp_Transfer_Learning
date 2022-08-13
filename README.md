# AI Summer Camp - Transfer Learning
Bu projede "Cats and Dogs" veri seti kullanılarak Transfer Learning ile derin öğrenme modeli eğitilecektir.

---

Bu projede “Cats and Dogs” veri setini kullanarak Transfer Learning ile derin öğrenme modeli eğiteceğiz. Sizden iki farklı notebook dosyası beklenmektedir. Birinci dosyada, verinin önişleme kısmı yapılacak. İkinci dosyada, önceden eğitilmiş bir model, hazırlanan veriler ile tekrar eğitilerek yapay zekâ modeli oluşturulacak. Amacımız herhangi bir accuracy veya loss sonucuna ulaşmak değil; kullanılan yöntemleri öğrenmektir.

Bu çalışma için Google Colab platformunu ve TensorFlow kütüphanesini kullanabilirsiniz.

Google Colab: [https://colab.research.google.com](https://colab.research.google.com)

TensorFlow Doküman: [https://www.tensorflow.org/api_docs/python/tf](https://www.tensorflow.org/api_docs/python/tf)

## 1. Önişleme
  - “Cats and Dogs” veri setini bilgisayarınıza indirin. (786.7MB) [https://www.microsoft.com/en-us/download/details.aspx?id=54765](https://www.microsoft.com/en-us/download/details.aspx?id=54765)
  - Görüntüleri Colab ortamına yükleyin.
  - Görüntüleri sırasıyla okuyarak, hepsini aynı boyuta getirin (resizing), normalizasyon yapın ve her bir görüntüyü etiketiyle birlikte, [görüntü, etiket] formatında bir listeye ekleyin.
  - Oluşturduğunuz listeyi; X_train, y_train, X_val, y_val, X_test ve y_test listelerine bölün.
  - Bu listeleri bilgisayarınıza kaydedin.

## 2. Model Eğitimi
  - Başka bir Colab dosyasında, bilgisayara kaydettiğiniz dosyaları tekrar yükleyin.
  - TensorFlow dokümantasyonunu kullanarak Keras içerisinden bir model seçin ve bu modeli yükleyin.
  - Modeli hazırlamış olduğunuz veriyle eğitin.
  - Model performans metriklerini, loss ve accuracy grafiklerini ekrana yazdırın.
