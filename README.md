# Technexus Grid Tasarımı

## Proje Hakkında

Bu projede HTML ve CSS kullanılarak Technexus markasına ait görsel bir kart düzeni oluşturuldu. Kartların sayfa üzerindeki konumlandırılması için CSS Grid kullanıldı.

## Kullanılan Teknolojiler

- HTML5
- CSS3
- CSS Grid

## Özellikler

- CSS Grid ile dört sütunlu ve üç satırlı yerleşim oluşturuldu.
- Kartların konumları `grid-column` ve `grid-row` özellikleriyle ayarlandı.
- Bazı kartların birden fazla satır veya sütun kaplaması sağlandı.
- Görsellerin kartlara uyum sağlaması için `width`, `height` ve `object-fit: cover` özellikleri kullanıldı.
- Kartların taşmasını önlemek için `overflow: hidden` uygulandı.
- Kartlara yuvarlatılmış köşeler eklendi.

## Proje Yapısı

- `index.html`: Kartların HTML yapısını içerir.
- `style.css`: Grid düzenini ve kartların görsel stillerini içerir.

## Amaç

CSS Grid sistemini, satır ve sütun yerleşimini, elemanların birden fazla hücre kaplamasını ve görsellerin belirlenen alanlara uyum sağlamasını öğrenmek ve uygulamak.