# Maaş Tahmin Projesi (Hitters Dataset)

Bu proje, beyzbol oyuncularının maaşlarını çeşitli makine öğrenmesi algoritmaları ile tahmin etmeyi amaçlar. Aşağıda projenin adım adım işleyişi özetlenmiştir.

## Adımlar

1. **Kütüphanelerin Yüklenmesi:**  
   Gerekli Python kütüphaneleri ve fonksiyonlar projeye dahil edilir.

2. **Veri Okuma:**  
   `hitters.csv` dosyası pandas ile okunur.

3. **Veri İncelemesi:**  
   Veri setinin genel yapısı, eksik değerler ve temel istatistikler incelenir.

4. **Değişken Türlerinin Belirlenmesi:**  
   Kategorik ve sayısal değişkenler otomatik olarak ayrılır.

5. **Kategorik ve Sayısal Değişken Analizi:**  
   Her bir değişkenin dağılımı ve temel istatistikleri görselleştirilir.

6. **Hedef Değişken Analizi:**  
   Maaş değişkeninin kategorik değişkenlere göre ortalamaları incelenir.

7. **Korelasyon Analizi:**  
   Değişkenler arası korelasyon matrisi ve yüksek korelasyonlu değişkenler analiz edilir.

8. **Aykırı Değer Analizi ve Baskılama:**  
   Sayısal değişkenlerdeki aykırı değerler tespit edilir ve baskılanır.

9. **Eksik Değer Analizi ve Temizleme:**  
   Eksik değerler analiz edilir ve veri setinden çıkarılır.

10. **Özellik Çıkarımı (Feature Engineering):**  
    Yeni değişkenler oluşturulur.

11. **One-Hot Encoding:**  
    Kategorik değişkenler dummy değişkenlere dönüştürülür.

12. **Özellik Ölçeklendirme:**  
    Sayısal değişkenler standartlaştırılır.

13. **Modelleme:**  
    Farklı regresyon modelleri ile temel karşılaştırmalar yapılır.

14. **Model Tuning:**  
    GridSearchCV ile en iyi hiperparametreler bulunur ve modeller optimize edilir.

15. **En İyi Modelin Seçilmesi:**  
    En düşük RMSE değerine sahip model seçilir.

16. **Test Seti ile Değerlendirme ve Görselleştirme:**  
    En iyi model ile test setinde tahminler yapılır, hata dağılımı ve QQ plot görselleştirilir.

17. **Feature Importance:**  
    En iyi modelin değişken önem düzeyleri görselleştirilir.

---

## Kullanım

1. Gerekli kütüphaneleri yükleyin.
2. Notebook'u adım adım çalıştırın.
3. Sonuçları ve görselleri inceleyin.

---

## Notlar

- Veri setinde log dönüşümü ve aykırı değer baskılama işlemleri uygulanmıştır.
- Model karşılaştırmaları ve hiperparametre optimizasyonu yapılmıştır.
- Sonuçlar ve görseller notebook sonunda yer almaktadır.
