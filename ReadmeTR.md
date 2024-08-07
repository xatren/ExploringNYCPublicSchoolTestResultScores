# NYC Kamu Okulu Test Sonuçları Analizi

Bu proje, New York City'deki kamu okullarının test sonuçlarını keşfeder ve analiz eder. Analiz, veri temizleme, özet istatistikler, görselleştirmeler ve farklı bölgelerdeki okulların performansını anlamak için korelasyon analizini içerir.

## İçindekiler

- [Kurulum](#kurulum)
- [Kullanım](#kullanım)
- [Veri](#veri)
- [Analiz](#analiz)
- [Sonuçlar](#sonuçlar)
- [Katkıda Bulunma](#katkıda-bulunma)
- [Lisans](#lisans)

## Kurulum

Bu projeyi yerel olarak çalıştırmak için lütfen şu adımları izleyin:

1. Depoyu klonlayın:
   ```sh
   git clone https://github.com/xatren/ExploringNYCPublicSchoolTestResultScores
   ```
2. Proje dizinine gidin:
   ```sh
   cd nyc-school-test-scores
   ```

## Kullanım

Analize başlamak için, tercih ettiğiniz ortamda (ör. Jupyter Notebook, JupyterLab, VSCode) Jupyter Notebook dosyasını açın:

1. Jupyter Notebook'u başlatın:
   ```sh
   jupyter notebook
   ```
2. `Exploring NYC Public School Test Result Scores.ipynb` not defterini açın.
3. Veri temizleme, analiz ve görselleştirmeleri gerçekleştirmek için hücreleri sırasıyla çalıştırın.

## Veri

Bu projede kullanılan veri seti `schools.csv` olup, aşağıdaki sütunları içermektedir:

- `school_name`: Okulun adı
- `borough`: Okulun bulunduğu ilçe
- `building_code`: Okul binası kodu
- `average_math`: Ortalama matematik test puanları
- `average_reading`: Ortalama okuma test puanları
- `average_writing`: Ortalama yazma test puanları
- `percent_tested`: Test edilen öğrencilerin yüzdesi

## Analiz

Analiz aşağıdaki adımları içerir:

1. **Veri Temizleme**:
   - Eksik değerlerin ele alınması
   - Yinelenen girişlerin kontrolü

2. **Veri Keşfi**:
   - Her sütun için özet istatistikler
   - Test puanları için dağılım grafikleri
   - Farklı test puanları arasındaki korelasyon analizi

3. **Görselleştirme**:
   - Test puanları için histogramlar ve kutu grafikleri
   - İlçelere göre ortalama puanları gösteren çubuk grafikleri
   - Farklı puanlar arasındaki ilişkileri görselleştirmek için saçılma grafikleri

## Sonuçlar

Analizden elde edilen önemli bulgular şunları içerir:

- Matematik, okuma ve yazma puanları arasındaki korelasyon.
- Farklı ilçelerdeki test puanlarının dağılımı.
- Test edilen öğrenci yüzdesine göre okulların performansı hakkında bilgiler.

## Katkıda Bulunma

Katkılar memnuniyetle karşılanır! Fikirleriniz, önerileriniz veya geliştirmeleriniz varsa, lütfen bir sorun açın veya bir çekme isteği oluşturun.

## Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için [LICENSE](LICENSE) dosyasına bakın.
