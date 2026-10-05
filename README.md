# TradingView Pine Script dosyaları

| Dosya | Tür | Ne işe yarar |
|---|---|---|
| `skr_sistem_strateji.pine` | **Strateji** | Ana alım-satım sistemi. TSI + sıkışma + Ichimoku (MEMATİ/POLAT) + OBV trend/uyumsuzluk + üst zaman dilimi onayını puanlayarak işlem açar; stop, hedef, başa baş ve iz süren stop içerir. Strategy Tester ile geçmiş test yapılır. |
| `skr_11tf_obv_tablosu.pine` | Gösterge | 11 zaman dilimli MEMATİ/POLAT alarm ve OBV tablosu (izleme paneli). |
| `tsi_choch_strategy.pine` | Strateji | Sadece TSI + CHoCH'tan oluşan önceki basit strateji. |
| `tsi_choch.pine` | Gösterge | Orijinal TSI oversold → CHoCH göstergesi. |
| `obv_trend_uyumsuzluk_sikisma.pine` | Gösterge (v4) | OBV trend çizgisi, kırılım, uyumsuzluk ve sıkışma alarmları. |

## Kurulum
1. TradingView → Pine Editor → dosya içeriğini yapıştır → *Add to chart*.
2. Strateji sonuçları için **Strategy Tester** sekmesi.
3. Alarm: Alarm oluştur → Koşul olarak göstergeyi/stratejiyi seç → **"Any alert() function call"**.
