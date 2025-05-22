# Akbank Makine Ogrenmesi Bootcamp Proje
# Neden Bu Veri Seti
Bu veri setini secmemdeki en buyuk neden, gercek hayattan alinmis, anlamli ve cozulmesi gereken bir problemi temsil etmesi. Gelir sinifini tahmin etmek, hem toplumsal hem de finansal acidan onemli. Aynı zamanda veri setinin icindeki kategorik ve sayisal degisken cesitliligi, eksik ve aykiri degerler gibi durumlar model gelistirme surecini daha ogretici hale getiriyor.

Ayrica hedef degiskenin dengesiz olmasi (yaklasik 3’e 1 oraninda) bu veri setini daha da ilginc kiliyor. Cunku bu gibi durumlarda dogru model kurmak, dogru metrik secmek (ben f1-score’a odaklandim) daha kritik hale geliyor. Kisacasi bu veri seti, hem teknik hem de dusunsel anlamda kendimi gelistirmem icin guzel bir baslangic noktasi oldu.
# Kullandigim Kutuphaneler  
**warnings**: Uyari mesajlarini gizler  
**pandas (pd)**: Veri islemesi  
**seaborn (sns)**: Istatistik grafik  
**matplotlib.pyplot (plt)**: Grafik cizimi  
**sklearn.preprocessing.LabelEncoder**: Kategorik kodlama  
**sklearn.model_selection.train_test_split**: Veri bolme  
**sklearn.model_selection.cross_val_score**: Capraz dogrulama  
**sklearn.linear_model.LogisticRegression**: Lojistik regresyon  
**sklearn.ensemble.RandomForestClassifier**: Random Forest  
**sklearn.ensemble.GradientBoostingClassifier**: Gradient Boosting  
**sklearn.ensemble.AdaBoostClassifier**: AdaBoost  
**sklearn.svm.SVC**: Destek vektor makinesi  
**sklearn.neighbors.KNeighborsClassifier**: K-en yakin komsu  
**sklearn.tree.DecisionTreeClassifier**: Karar agaci  
**xgboost (xgb)**: XGBoost
**sklearn.model_selection.GridSearchCV**: Hiperparametre arama  
**sklearn.metrics.accuracy_score**: Dogruluk hesapla  
**sklearn.metrics.f1_score**: F1 skoru hesapla  
**sklearn.metrics.roc_auc_score**: ROC AUC olcumu  
**sklearn.metrics.confusion_matrix**: Karisiklik matrisi  

 

# Bu Projede Neyi Amacliyorum?
Projemde gercek bir veri seti uzerinde calisarak kendimi veri bilimi ve makine ogrenmesi konusnda gelistirmeyi amacliyorum. Model gelistirirken verimde hedef degiksenimde 3'e birlik bir oran oldugu icin ben daha cok f1-scoruna odaklanmak istedim bu yuzden o skoru artirma amacli calismalar yaptim.  



# Veride Yaptigim Islemler:
Eksik Deger Analizi    
Aykiri Deger Anlizi  
Veri Gorsellestirme  
Veri Onisleme    
Veriyi Gozetimli Ogrenme Modelleriyle Egitme  
Model Degerlendirilmesi ve Sonuclarin Gorsellestirilmesi
# Kullandığım Gözetimli Ogrenme Modelleri
Logistic Regression, Random Forest, SVM, XGBoost, Gradient Boosting, KNN, Decision Tree, AdaBoost
# Neden XGBoost
Benim veri setimde hedef degisken kategorik ve siniflar arasinda yaklasik 3’e 1’lik bir dengesizlik var. Ayrica sayisal degiskenlerde de fazlasiyla aykiri deger bulunuyor. Bu yuzden aykiri degerlere karsi guclu oldugu icin agac tabanli modelleri tercih etmek istedim. Bu konuda XGBoost ve benzeri modeller en iyilerden biridir.  
Bu yuzden XGBoost’u tercih etmek istiyorum cunku yuksek dogruluk orani sagliyor ve dengesiz siniflarda etkili parametre ayarlari yapabiliyor. Endustri projelerinde de yaygin olarak kullanilmasi, gercek dunyadaki karmasik verilerle basa cikma gucunu gosteriyor. Bu model, hem hiz hem de verimlilik acisindan avantajli oldugu icin benim icin en uygun secenek.
# Sonuc 
Bu calisma sayesinde gelir tahmini uzerine fena olmayan bir ilerleme kaydettigimi dusunuyorum. Modelin cikardigi sonuclar genel olarak dengeli ve makul geldi. Ilk sefer icin oldukca ogreticiydi. Ilerde boyle modellerin bankalar ya da finans alaninda, kisilerin gelirini dogrudan ogrenmeden tahmin etmek icin kullanilabilecegini hayal ediyorum. Mesela kredi onayinda ya da urun tavsiyelerinde daha saglikli kararlar alinmasina yardimci olabilir.
Tabii daha yolun basindayim. Bu proje benim icin veri bilimi alaninda bir nevi giris noktasi oldu. Model su an fena calismiyor ama hala ogrenmem gereken cok sey var. Veri on isleme, parametre ayarlari ya da farkli algoritmalar denemek gibi eksiklerim oldugunun farkindayim. Ama bu calisma sayesinde bir seylerin temelini atmis olmak beni motive etti. Zamanla daha iyi projeler yapip, bu alanda kendimi daha da gelistirmek istiyorum.
# Veri Hakkinda Kisa Bir Bilginiz Olmasi Acisindan Gorseller
![image](https://github.com/user-attachments/assets/90fb2dec-2a80-4a3c-a632-f1bfbef3ba2d)
![image](https://github.com/user-attachments/assets/e1e7bfb4-0cb0-413e-9b5c-fb4978453909)

# Modelin Degerlendirilmesi
Modelimin Siniflandirma Raporu:  
<img width="826" alt="Screenshot 2025-05-20 at 02 50 56" src="https://github.com/user-attachments/assets/c8bbfde1-2626-4cb8-bb0e-b0863352927e" />

Modelimin t-SNE Kume Dagilimi Grafigi
![image](https://github.com/user-attachments/assets/962856df-1896-4b02-888f-cd0b7264c3cc)


# Linkler
Veri setim: https://www.kaggle.com/datasets/uciml/adult-census-income    
Kendi kaggle notebookum: https://www.kaggle.com/code/feyzayildizz/ml-project-xgboost (Kaggle yukledikten sonra modelin gorsellestirilmesi icin bazi seyleri kendi notebookume ekledim buradaki mlproject.ipynb son halidir.)
(Kaggle’da ayni veri seti uzerine yapilmis bazi projelere baktim, inceledigim calismalarin linklerini asagida paylasiyorum)  
https://www.kaggle.com/code/eliamelfior2/classifica-o-com-machine-learning  
https://www.kaggle.com/code/bhupendrarajput/complete-eda-and-machine-learning  
https://www.kaggle.com/code/h31415926f/various-traditional-machine-learning-methods

