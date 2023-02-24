Bu proje kullanıcılar tarafından girilen yorumları toksik değil, az toksik ve çok toksik olarak filtreleyebiliyor.Proje pre-processing, feature representation, feature selection adımlarını
içerir.
Girilen bir yorum için önce noktalama işareetlerinden arındırılır. Stop word'ler atılır. Stemming uygulanır. Nan değerlerin sayısına göre bazı feature'lar temizlenir. Tf-İdf algoritmaları uygulanır. PCA algoritması ile 3 boyuta düşürülür. son olarak KNN algoritması uygulanır.
