**TEMEL DOĞA GELİŞLİ - 1172602052**
**SORU 1**
**1)** 
>**Devre Anahtarlama**: Devre anahtarlamasında, gerçek veri iletimi başlamadan önce yola karar verilir ve atanır. İki uç nokta arasındaki iletişimin tamamı için, bant genişliği ve diğer kaynaklar sabit ve tahsis edilmiştir, bu da yalnızca oturum sona erdiğinde serbest bırakılacaktır. Buna ek olarak, kaynaktan gönderilen mesajların sırası, devre anahtar ağı üzerinden geçtiğinde hedefte değişmeyecektir. Bu, orijinal iletiyi yeniden oluşturmak için hedefte daha az işleme neden olur.

**2)**
>**Paket Anahtarlama**: Paket Anahtarı ağlarında ileti, birbirinden bağımsız olarak hedefe gönderilen küçük veri paketlerine bölünür. Kaynaktan hedefe giden yol protokol sayısı ile işlenirken, paketlerin yönlendirilmesi anahtarlama merkezleri veya yönlendiriciler tarafından gerçekleştirilir. Her paket, kaynak ve hedef adreslere ve bağlantı noktalarına bağlı olarak yolunu bulur. Her paket, paket anahtarlamalı ağlarda ayrı ayrı işlendiğinden, paketler kaynaktan gönderildikleri orijinal sıraya göre hedefe ulaşmamış olsalar bile, orijinal mesaj hedefte yeniden oluşturulabilecek şekilde etiketlenir. . ses ve video akışları gibi gerçek zamanlı trafik taşımak için paket anahtar etki alanlarının garantili QoS düzeyleriyle düzgün şekilde korunması gerekir.

**Aralarındaki Farklar:**
>Aralarındaki Farklar 
>1) Paket anahtar ağlarında, bant genişliği tam potansiyeline kadar kullanılabilirken, devre anahtar ağları ile bant genişliği kullanımı daha az verimli olur. 
>2) Her paket adresleri kullanılarak yönlendirildiği için paket Switch ağlarında daha fazla yedekli olabilirken, devre anahtarı ağlarında önceden tanımlanmıştır. 
>3) Paket anahtar ağları kullanıcı sayısı arttığında paylaşılabilirken, devre anahtar ağları kullanılabilir maksimum kanal sayısı ile sınırlıdır.
>4) Bir devre anahtarı ağı üzerinden geçerken gönderilen mesajların sırası değişmezken, paket anahtarı ağı ile böyle bir garanti yoktur.
>5) Devre anahtar ağları tasarımının kendisi garantili bir uçtan uca QoS sağlarken, paket anahtarı etki alanlarında QoS'nin uygulanması gerekir.


**SORU 2**
**1)**
>1) **Yol (Bus)**: Tüm makinelerin tek bir kablo ile bağlı oldukları ağ
türüdür.
 2) **Yıldız (Star)**: Tüm düğümlerin ortak bir merkeze bağlanmasıdır.
Arızalı cihazların tespiti bu yapıda kolay olur.
3) **Halka (Ring)**: Kapalı bir döngü biçiminde kurulan topoloji
yöntemidir. Bilgiler halka üzerindeki aktif istasyonlardan
sırasıyla geçerek yerine varır.
4) **Ağaç (Tree) veya Gelişmiş Yıldız (Extended Star)**: Genellikle
yıldız topolojisindeki ağları birbirine bağlamak için kullanılır. Bir
ağacın dalları farklı topolojideki ağları temsil eder, ağacın
gövdesi ile de bunlar birbirine bağlanır.
5) **Karmaşık (Mesh)**: Tüm bilgisayarlar birbirine direk olarak
bağlıdırlar.
6) **Hiyerarşik**: Üzerinde Bus topoloji ve Yıldız topolojiden özellikler
taşır.
