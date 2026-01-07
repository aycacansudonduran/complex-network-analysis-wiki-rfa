# Kompleks Ağ Analizi – Wikipedia RfA

## Proje Tanımı
Bu proje, Wikipedia Requests for Adminship (wiki-RfA) veri seti kullanılarak
büyük ölçekli ve yönlü bir sosyal ağın analizini amaçlamaktadır.

Çalışmanın temel amacı; gerçek bir sosyal ağ üzerinde çeşitli ağ metriklerini
hesaplayarak yapısal özellikleri ortaya koymak, merkezi düğümleri belirlemek
ve topluluk yapısını incelemektir.

Bu proje, Ağ Analizi dersi kapsamında akademik bir çalışma olarak geliştirilmiştir.

---

## Veri Seti
- Veri seti: Wikipedia Requests for Adminship (wiki-RfA)
- Düğümler (Nodes): Wikipedia kullanıcıları
- Kenarlar (Edges): Kullanıcılar arasındaki oylama etkileşimleri (yönlü)
- Toplam düğüm sayısı: 11.377
- Toplam yönlü kenar sayısı: 188.077

---

## Kullanılan Yöntemler ve Metrikler
- In-degree ve out-degree dağılımları
- Log-log derece dağılımı analizi
- Power-law uyum analizi
- Degree Centrality (Derece Merkeziliği)
- Closeness Centrality (Yakınlık Merkeziliği)
- Betweenness Centrality (Arasındalık Merkeziliği)
- PageRank
- Ortalama yol uzunluğu ve ağ çapı
- Kümelenme katsayısı (Clustering Coefficient)
- Benzerlik katsayısı (Assortativity)
- Topluluk tespiti (Community Detection)
- Ağ görselleştirmesi (örneklemeli)

---

## Kullanılan Araçlar ve Teknolojiler
- Python
- NetworkX
- Matplotlib
- Gephi
- Pyvis

---

## Elde Edilen Bulgular
- Ağın düşük yoğunluğa sahip olduğu ve seyrek bağlantılı bir yapı gösterdiği
  tespit edilmiştir.
- PageRank, closeness ve betweenness merkezilik ölçümleri, bazı kullanıcıların
  ağda kritik roller üstlendiğini göstermektedir.
- Derece dağılımlarının log-log analizleri, ağın ölçek-bağımsız (scale-free)
  özellikler taşıdığını desteklemektedir.
- Ortalama yol uzunluğu 2.95, ağ çapı ise 8 olarak hesaplanmış olup,
  bilgi yayılımının ağda hızlı gerçekleşebileceği sonucuna varılmıştır.
- Toplam 7 adet topluluk tespit edilmiş; en büyük toplulukların binlerce
  düğümden oluştuğu gözlemlenmiştir.
- Assortativity katsayısı negatif bulunmuş ve ağın disassortative yapıda
  olduğu görülmüştür.
- Gephi ve Pyvis kullanılarak ağ yapısı görsel ve etkileşimli olarak incelenmiştir.

---

## Genel Değerlendirme
Bu proje sayesinde, sosyal ağlarda merkeziyet, topluluk yapısı ve
ölçek-bağımsızlık gibi kavramların gerçek bir veri seti üzerinde nasıl
ortaya çıktığı gözlemlenmiştir.

Yönlü sosyal ağların yapısal analizi; bilgi yayılımı, etkileşim dinamikleri
ve kullanıcı davranışlarının daha iyi anlaşılmasına katkı sağlamaktadır.
