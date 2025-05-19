# Akbank Makine Ogrenmesi Bootcamp Proje
# Neden Bu Veri Seti
Bu veri seti, bireylerin yillik gelir sinifini tahmin etmek icin gozetimli ogrenme yontemlerini kullanmamiza olanak sagliyor. Veri, gelir sinifini gosteren hedef degisken (income) ile birlikte, bu sonucu etkileyen farkli demografik ve ekonomik ozellikleri iceriyor. Hedef degisken iki siniftan olusuyor: "<=50K" ve ">50K". Bu sayede, elimizdeki ozellikleri kullanarak gelir sinifini dogru ve etkili sekilde tahmin etmeyi amacliyoruz.
# Kullandigim Kutuphaneler
**pandas** Veriyi okuyup duzenlemek icin  
**numpy**  Sayisal islemler icin (dogrudan kullanmadim ama pandas ile birlikte calisiyor)  
**seaborn**  Gorsel analiz yapmak icin  
**matplotlib.pyplot**  Grafik cizmek icin  
**warnings**  Gereksiz uyari mesajlarini kapatmak icin  
**sklearn.preprocessing.LabelEncoder**  Kategorik verileri sayiya cevirmek icin  
**sklearn.model_selection.train_test_split**  Gradient Boosting modeli icin  
**sklearn.ensemble.RandomForestClassifier**  Random Forest modeli icin  
**sklearn.metrics**  Modelin basarisina bakmak icin (accuracy, f1, AUC gibi)  


# Veride Yaptigim Islemler:
Eksik Deger Analizi    
Aykiri Deger Anlizi    
Veri Gorsellestirme  
Veri Onisleme    
Veriyi Gozetimli Ogrenme Modelleriyle Egitme  
# Kullandığım Gözetimli Ogrenme Modelleri
Gelir sınıfı tahmini bir classification problemidir, bu yüzden lineer regresyon gibi sadece sürekli değerler tahmin eden ve doğrusal varsayımlar içeren modeller uygun değildir. Veri hem sayısal hem kategorik değişkenler içerdiğinden, Random Forest ve Gradient Boosting Classifier esnek ve karmaşık ilişkileri modelleyebildiği için tercih ettim. Ayrıca, bu modeller aykırı değerlere dayanıklıdır ve genellikle daha yüksek doğruluk sağlar.
# Sonuc 
Bu calisma sayesinde gelir tahmini uzerine fena olmayan bir ilerleme kaydettigimi dusunuyorum. Modelin cikardigi sonuclar genel olarak dengeli ve makul geldi. Ilk sefer icin oldukca ogreticiydi. Ilerde boyle modellerin bankalar ya da finans alaninda, kisilerin gelirini dogrudan ogrenmeden tahmin etmek icin kullanilabilecegini hayal ediyorum. Mesela kredi onayinda ya da urun tavsiyelerinde daha saglikli kararlar alinmasina yardimci olabilir.
Tabii daha yolun basindayim. Bu proje benim icin veri bilimi alaninda bir nevi giris noktasi oldu. Model su an fena calismiyor ama hala ogrenmem gereken cok sey var. Veri on isleme, parametre ayarlari ya da farkli algoritmalar denemek gibi eksiklerim oldugunun farkindayim. Ama bu calisma sayesinde bir seylerin temelini atmis olmak beni motive etti. Zamanla daha iyi projeler yapip, bu alanda kendimi daha da gelistirmek istiyorum.
# Linkler
Veri setim: https://www.kaggle.com/datasets/uciml/adult-census-income  
(Kaggle’da ayni veri seti uzerine yapilmis bazi projelere baktim, inceledigim calismalarin linklerini asagida paylasiyorum)  
https://www.kaggle.com/code/eliamelfior2/classifica-o-com-machine-learning  
https://www.kaggle.com/code/bhupendrarajput/complete-eda-and-machine-learning  
https://www.kaggle.com/code/h31415926f/various-traditional-machine-learning-methods

