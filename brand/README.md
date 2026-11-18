# Logo dosyaları

Hepsi şeffaf PNG. Zemine göre seçin; `src/components/brand/Logo.tsx` bunu `variant` ile yapar.

| Dosya | Zemin | `variant` |
| --- | --- | --- |
| `synapse-mark.png`, `synapse-logo.png` | Açık (beyaz, Mist): petrol pinler, amber üçgen | `dark` |
| `synapse-mark-koyu-zemin.png`, `synapse-logo-koyu-zemin.png` | Koyu (petrol koyu menü ve alt bilgi): beyaz pinler, amber üçgen | `light` |
| `synapse-mark-beyaz.png`, `synapse-logo-beyaz.png` | Fotoğraf ya da renkli zemin üstü, tek renk beyaz | `mono` |

UI-15 (19.11.2026) renkleri: lacivert -> petrol `#0A6C7E` (koyu zemin sürümündeki simgelerde
petrol koyu `#063A46`), kırmızı -> amber `#FF9F1C`. Dosyalar eski lacivert/kırmızı PNG'lerden
renk eşlemeyle üretildi (`araclar/marka/logo_renklendir.py`; kenar yumuşatması ve saydamlık
korunur); `favicon.png` açık zemin işaretinden çıkarılır. Kaynak bir vektör (SVG) dosyası gelirse
bu sürümler ondan yeniden çıkarılmalı.
