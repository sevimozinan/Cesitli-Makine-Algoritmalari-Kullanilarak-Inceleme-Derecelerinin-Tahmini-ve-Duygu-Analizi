# Çeşitli Makine Algoritmalari Kullanılarak İnceleme Derecelerinin Tahmini ve Duygu Analizi

Marmara Üniversitesi çatısı altındaki son araştırma projem, işletmelerin e-ticaret ve destinasyon yöneticilerinin yenilikçi yöntemlerle kullanıcı yorumlarını değerlendirebileceğini göstermek istemektedir. Bu kapsamda, çeşitli makine öğrenimi algoritmaları kullanılarak veri kümesindeki inceleme derecelerinin tahmini ve duyarlılık analizi gösterilmiştir. Herhangi bir makine öğrenmesi modellemesi yapılmadan önce ilk olarak R ile keşifsel veri analizi yapılarak veri setine ilişkin içgörü oluşturuldu ve veriye ait önemli değişkenlere ve değişkenler arasındaki ilişkiye yer verildi. Uygulama aşamasında ise, ilk olarak python ile incelemenin kelime uzunluğunu içeren “length” isimli değişken oluşturuldu. Ardından length ile ilgili analizler yapıldı ve yorumlandı. Ardından veri çerçevesinin yalnızca 1, 3 veya 5 yıldızlı incelemelerini içeren classification yapıldı ve analizlere bu yeni veri çerçevesi ile devam edildi. Features, Labels, stop words ve vektörleştirme ile ilgili detaylara yer verildikten sonra veriseti, train ve test olarak ikiye bölünerek modelleme aşamalarına geçildi. Modelleme aşamalarında Multilayer Perceptron, Multinomial Naive Bayes, XGBoost Classifier, Gradient Boosting Classifier, Support Vector Machine, Random Forest Classifier, Decision Tree, K Neighbor Classifier olmak üzere 8 farklı makine algoritması detaylı bir şekilde anlatıldı ve python ile uygulaması yapıldı. Ardından, en iyi score değerine sahip olan modelin Multilayer Perceptron(Çok Katmanlı Sınıflayıcı) olduğu saptandı ve böylece çok katmanlı sınıflandırıcı en iyi puana sahip olduğundan, rastgele bir pozitif incelemeyi, rastgele bir ortalama incelemeyi ve rastgele bir negatif incelemeyi tahmin etmek için kullanıldı.  
