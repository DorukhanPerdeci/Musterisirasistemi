# Simülasyon Projesi: Müşteri Kuyruk Sistemi
# Genel Bakış
Bu simülasyon projesi, Python ve SimPy kullanarak bir müşteri kuyruk sistemini modellemektedir. Müşterilerin bir hizmet noktasına gelmesini, gerekirse kuyrukta beklemesini, hizmet almasını ve ardından sistemden ayrılmasını simüle eder. Proje ayrıca bekleme sürelerinin görselleştirilmesini içerir ve sistemin performansına ilişkin istatistiksel analiz sağlar.

# Bağımlılıklar
Bu proje aşağıdaki bağımlılıkları gerektirir:

SimPy: Süreç tabanlı ayrık olay simülasyon kütüphanesi.
Matplotlib: Görselleştirmeler oluşturmak için kullanılan bir grafik çizim kütüphanesi.
Tabulate: Verileri tablolara biçimlendirmek için kullanılan bir kütüphane.
Bu bağımlılıkları pip aracılığıyla yükleyebilirsiniz: pip install simpy matplotlib tabulate

# Kullanım
# Sürüm 1: exact_numbers.py
Bu sürüm, belirli varış aralıkları ve rastgele hizmet süreleri dizileri ile 11 müşteri için simülasyonu göstermektedir.

Simülasyonu çalıştırmak için Python betiğini yürütün exact_numbers.py. Sisteminizde Python'ın kurulu olduğundan emin olun.

python exact_numbers.py

# Sürüm 2: theProject.ipynb
Bu sürüm, rastgele oluşturulmuş varışlar arası süreler ve rastgele oluşturulmuş hizmet süreleri dizileri değerleriyle 100 müşteri için simülasyonu göstermektedir.

Simülasyonu çalıştırmak için theProject.ipynbJupyter Notebook veya Jupyter Lab'te Jupyter Notebook'u açın ve hücreleri yürütün.

Simülasyon aşağıdaki çıktıyı verecektir:

Varış zamanı, hizmet süresi, kuyrukta bekleme süresi, sistemde geçirilen süre vb. dahil olmak üzere her müşteri için çeşitli ölçütleri gösteren bir tablo.
Bekleme süresi ve sistem süresinin dağılımını gösteren histogramlar.
Ek olarak, bu komut dosyası ortalama bekleme süresi, bekleme olasılığı, boş sunucu olasılığı, ortalama hizmet süresi, ortalama varışlar arası süre, bir müşterinin kuyrukta geçirdiği ortalama süre ve bir müşterinin sistemde geçirdiği ortalama süre gibi çeşitli performans ölçütlerini hesaplar ve yazdırır.

# Simülasyon Parametreleri
num_customersSimüle edilecek müşteri sayısı.
interarrival_timesMüşterilerin varışlar arasındaki sürelerini gösteren bir liste.
random_service_timesMüşterilerin hizmet sürelerini gösteren bir liste.
Bu parametreleri, ihtiyaçlarınıza göre komut dosyasında ayarlayabilirsiniz.
