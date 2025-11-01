# PDF Report Generator | PDF Rapor Oluşturucu

[English](#english) | [Türkçe](#turkish)

---

<a name="english"></a>
## 🇬🇧 English

Automated professional PDF report generator from Excel/CSV data.

### Features

- 📄 Professional PDF generation
- 📊 Automatic chart creation (bar, line, comparison)
- 📈 Statistical analysis
- 🎨 Branded templates with custom colors
- 📋 Data tables with styling
- 🔢 Key metrics summary boxes

### Tech Stack

- Python 3.10+
- ReportLab (PDF generation)
- Pandas (data processing)
- Matplotlib (chart creation)
- OpenPyXL (Excel reading)

### Installation

```bash
pip install -r requirements.txt
```

### Configuration

Edit `config.py`:

```python
COMPANY_NAME = "Your Company"
REPORT_TITLE = "Monthly Business Report"
PRIMARY_COLOR = HexColor('#2C3E50')
```

### Usage

```bash
python main.py
```

The tool will:
1. Load data from Excel/CSV
2. Generate statistics
3. Create visualizations
4. Build professional PDF report

Reports saved to `reports/` folder.

### Input Format

Excel/CSV with columns like:
- Month, Sales, Revenue, Customers
- Or any numerical data

### Sample Output

Professional PDF including:
- Cover page with branding
- Executive summary
- Key metrics table
- Data visualizations
- Detailed analysis
- Conclusions & recommendations

### Use Cases

- Monthly business reports
- Client performance summaries
- Sales team dashboards
- Marketing campaign results
- Financial analysis reports

### Customization

Easily customize:
- Colors and branding
- Chart types
- Report sections
- Logo placement

### License

MIT

---

<a name="turkish"></a>
## 🇹🇷 Türkçe

Excel/CSV verilerinden otomatik profesyonel PDF rapor oluşturucu.

### Özellikler

- 📄 Profesyonel PDF oluşturma
- 📊 Otomatik grafik yaratma (çubuk, çizgi, karşılaştırma)
- 📈 İstatistiksel analiz
- 🎨 Özel renklerle markalı şablonlar
- 📋 Stilize veri tabloları
- 🔢 Anahtar metrik özet kutuları

### Teknolojiler

- Python 3.10+
- ReportLab (PDF oluşturma)
- Pandas (veri işleme)
- Matplotlib (grafik yaratma)
- OpenPyXL (Excel okuma)

### Kurulum

```bash
pip install -r requirements.txt
```

### Yapılandırma

`config.py` dosyasını düzenleyin:

```python
COMPANY_NAME = "Şirket Adınız"
REPORT_TITLE = "Aylık İş Raporu"
PRIMARY_COLOR = HexColor('#2C3E50')
```

### Kullanım

```bash
python main.py
```

Araç şunları yapar:
1. Excel/CSV'den veri yükler
2. İstatistikleri hesaplar
3. Görselleştirmeler oluşturur
4. Profesyonel PDF rapor hazırlar

Raporlar `reports/` klasörüne kaydedilir.

### Girdi Formatı

Excel/CSV sütunları örneği:
- Ay, Satış, Gelir, Müşteriler
- Veya herhangi sayısal veri

### Örnek Çıktı

Profesyonel PDF içeriği:
- Markalı kapak sayfası
- Yönetici özeti
- Anahtar metrikler tablosu
- Veri görselleştirmeleri
- Detaylı analiz
- Sonuçlar ve öneriler

### Kullanım Alanları

- Aylık iş raporları
- Müşteri performans özetleri
- Satış ekibi dashboard'ları
- Pazarlama kampanya sonuçları
- Finansal analiz raporları

### Özelleştirme

Kolayca özelleştirilebilir:
- Renkler ve marka kimliği
- Grafik tipleri
- Rapor bölümleri
- Logo yerleşimi

### Lisans

MIT

---

Built with ⚡ by [Forge270](https://github.com/Forge270)
