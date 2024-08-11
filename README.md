# GitHub'da Projeyi Paylaşma Adımları

Bu kılavuz, Tkinter ve Plotly kullanarak oluşturduğunuz etkileşimli grafik projenizi GitHub'da nasıl paylaşacağınızı adım adım anlatmaktadır.

## 1. GitHub'da Yeni Bir Depo (Repository) Oluşturma
1. GitHub hesabınıza giriş yapın.
2. Sağ üst köşedeki `+` işaretine tıklayın ve "New repository" seçeneğini seçin.
3. Depo ismini ve açıklamasını girin (örn. `tkinter-plotly-interactive-graph`).
4. Depoyu "Public" olarak ayarlayın ve "Create repository" butonuna tıklayın.

## 2. Projenizi Yerel Olarak Hazırlayın
1. Proje dosyalarınızı bilgisayarınızda bir klasöre koyun.
2. Bu klasör içerisinde aşağıdaki dosyaların olduğundan emin olun:
   - Python kodu (örneğin `main.py` olarak adlandırılabilir).
   - Gereksinimleri belirtmek için `requirements.txt` dosyası (örn. `plotly`, `pandas` gibi kütüphaneleri içerir).
   - README.md dosyası (projenin açıklamasını içerir).

## 3. Gereksinim Dosyası (requirements.txt) Oluşturma
Eğer yoksa, bir `requirements.txt` dosyası oluşturun ve içinde kullanmanız gereken kütüphaneleri listeleyin. Örneğin:

- pandas
- plotly
- tk

  ## 4. README.md Dosyası Oluşturma
Projenizin ne yaptığını, nasıl çalıştığını ve nasıl kullanılacağını açıklayan bir `README.md` dosyası oluşturun. Örnek bir içerik:

```markdown
# Tkinter ve Plotly ile Etkileşimli Grafik Uygulaması

Bu proje, Python'da Tkinter ve Plotly kullanarak etkileşimli veri görselleştirme yapmanızı sağlar. Tkinter arayüzü ile belirli veri aralıklarını ve özellikleri seçebilir, ardından bu seçimlere göre oluşturulan grafikleri Plotly ile tarayıcınızda görüntüleyebilirsiniz.

