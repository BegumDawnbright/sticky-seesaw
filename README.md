# Sticky Seesaw

Yapışkan bir elle blokları kapıp taşıdığın, tahterevalli gibi sallanan bir board üzerinde oynanan 3D bulmaca oyunu.

**Oyna:** https://begumdawnbright.github.io/sticky-seesaw/

## Nasıl oynanır

- Bir sütuna dokun → yapışkan el iner ve **en üstteki bloğu** kapar
- Başka bir sütuna dokun → bloğu oraya bırakır
- Aynı renkten **3 veya daha fazlası** yan yana gelince patlar
- **Tahtanın tamamını temizle** → sonraki seviye

## Dikkat etmen gerekenler

- **Denge:** Board bir mil üstünde duruyor. Ağırlık bir tarafa yığılırsa eğilir, çok eğilirse devrilir ve kaybedersin.
- **Kirlenen el:** El her kapmada biraz daha kirlenir. Kirlendikçe kontrolünü kaybeder ve istemediğin blokları da kapar. Patlatmak eli temizler — ya da kovaya dokun, tertemiz olsun. Ama kovanın bedeli 3 blok.
- **Yağmur:** Her hamlenden sonra tepeden rastgele bir sütuna yeni blok yağar. Yağmayı geride bırakman gerek.

## Teknik

Tek dosyalık HTML + [Three.js](https://threejs.org/) (r128). Kurulum gerektirmez, `index.html` dosyasını tarayıcıda açman yeterli.
