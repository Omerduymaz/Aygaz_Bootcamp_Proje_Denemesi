# Aygaz_Bootcamp_Proje_Denemesi
Aygaz bootcamp'te ilerleme için deneme projesi.
Bu proje, TensorFlow ve Keras kullanılarak oluşturulmuş bir makine öğrenimi uygulamasıdır. Amacımız, kedi ve köpek fotoğraflarını sınıflandırabilen bir Konvolüsyonel Sinir Ağı (CNN) modeli geliştirmektir.

Projenin Özeti
Hayvan sınıflandırma projesinde, Cats vs Dogs veri seti kullanılarak bir derin öğrenme modeli eğitilmiştir. Model, giriş olarak bir hayvan görüntüsü alır ve bu görüntüyü Kedi ya da Köpek olarak sınıflandırır. Modelin eğitim süreci ve doğrulama sonuçları grafiklerle görselleştirilmiştir.

Projede Kullanılan Teknolojiler ve Araçlar:
-Python
-TensorFlow ve Keras
-Matplotlib (görselleştirme için)
-Google Colab (projenin çalıştırılması ve eğitimi için)

Projenin Adımları
1. Gerekli Kütüphanelerin Yüklenmesi
Proje, TensorFlow ve Keras gibi makine öğrenimi kütüphanelerini kullanır. Ayrıca görselleştirme için Matplotlib'den faydalanılmıştır.

2. Veri Setinin Hazırlanması
-Google'dan indirilen Cats vs Dogs veri seti kullanılmıştır.
-Veri seti eğitim ve doğrulama olarak ikiye ayrılmıştır.
-Görseller, 150x150 piksel boyutuna ölçeklendirilmiş ve 0-1 aralığına normalize edilmiştir.

3. Modelin Tasarımı
-Model, üç konvolüsyonel katman ve max-pooling katmanları ile tasarlanmıştır.
-Fully connected katmanlar, sınıflandırma için kullanılmıştır.
-Çıkış aktivasyon fonksiyonu olarak sigmoid seçilmiştir.

4. Modelin Eğitimi
-Model, 10 epoch boyunca eğitilmiştir.
-Eğitim sırasında doğruluk ve kayıp değerleri kaydedilmiş ve doğrulama verileri ile karşılaştırılmıştır.
-5. Performansın Görselleştirilmesi
-Eğitim ve doğrulama süreçleri için doğruluk ve kayıp değerleri grafikler ile görselleştirilmiştir.

6. Modelin Test Edilmesi
 -Eğitilen model, bir test görüntüsü üzerinde tahmin yapmak için kullanılmıştır.
 -Modelin Çalıştırılması
 -Gereksinimler
 -Projeyi çalıştırmak için aşağıdaki kütüphanelerin yüklü olması gereklidir:
  *TensorFlow
  *Keras
  *Matplotlib

Nasıl Çalıştırılır?
 -Proje dosyasını bilgisayarınıza ya da Google Colab'e indirin.
 -Gerekli kütüphaneleri yükleyin:
 -bash
 -Kodu kopyalayın
      (pip install tensorflow matplotlib)
 -Not defterini çalıştırın ve her hücreyi sırayla çalıştırarak süreci takip edin.
-Test görüntüsü ile modelin sınıflandırma sonuçlarını gözlemleyin.
-Örnek Sonuçlar
-Eğitimden elde edilen doğruluk ve kayıp grafikleri aşağıdaki gibidir:
 *Eğitim ve Doğrulama Doğruluğu
 *Eğitim ve Doğrulama Kaybı
 *Grafikler, modelin performansını görsel olarak değerlendirmemize olanak tanır.


NOT: Bu proje zaman kısıtından kaynaklı geliştirmesi tamamlanamamıştır. Bu nedenle doğruluk oranı istenilen seviyede değildir.
