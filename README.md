# 🏖️ BeachLifeGame

**BeachLifeGame**, görev tabanlı bir **cankurtaran simülasyon oyunudur**.  
Oyuncu her gün farklı görevlerle karşılaşır: boğulan kişileri kurtarmak, köpek balıklarını uzaklaştırmak, sahildeki tehditleri etkisiz hale getirmek gibi.  

## 🎮 Oynanış Özellikleri
- 🧍‍♂️ Görev tabanlı ilerleyiş sistemi  
- 📆 Her gün değişen görevler ve zorluk seviyeleri  
- 🔧 Karakter ve ekipman geliştirme sistemi  
- 🌊 Su üstünde yüzme ve su altına dalış mekaniği  
- 🚨 Başarı ve başarısızlık takibi ile oyun sonu mekanizması  
- 🧠 Yapay zekâ kontrollü NPC'lerle etkileşim  
- 📈 Günlük performansa göre puan ve ödül sistemi *(yolda)*

## 🛠️ Kullanılan / Kullanılacak Teknolojiler ve Sistemler

| Teknoloji / Sistem                 | Açıklama |
|------------------------------------|----------|
| **Unity (HDRP)**                  | Gerçekçi su, ışık ve atmosfer efektleri için kullanılıyor. |
| **C#**                            | Oyun mekaniği, görev yapısı, animasyon ve UI kontrolü. |
| **Unity Input System**            | Platformlar arası esnek kontrol sistemi. |
| **Cinemachine**                   | Kamera geçişleri (yüzeyde 3. şahıs, dalarken FPS). |
| **Animator + Mecanim**            | Karakter animasyonları: yüzme, dalma, kurtarma, vs. |
| **Unity NavMesh + NavMesh Agent** | NPC'lerin sahilde rastgele gezinmesi için kullanılıyor. Her NPC kendi alanında rastgele hedef belirleyerek o noktaya yöneliyor. Wander behavior aktif. |
| **Custom FSM AI System**          | NPC’lerin yüzme, yardım çağrısı ve etkileşim durumlarını yöneten Finite State Machine yapısı. |
| **ScriptableObject**              | Görev tanımları, NPC verileri gibi veri yapılarını modüler şekilde yönetmek için. |
| **Event System + Observer Pattern** | Görevlerin tetiklenmesi, oyun akışı ve puanlama sisteminde kullanılıyor. |
| **Pooling System**                | Tekrarlanan objelerin (can simidi, köpek balığı, dalga) performanslı yönetimi. |
| **Shader Graph**                  | Su altı efektleri, ışık kırılması ve bulanıklık gibi görsel detaylar için. |
| **Audio Mixer + 3D Spatial Sound**| Çevresel sesler ve su altı/üstü ses geçişleri için. |
| **Unity Version Control (PlasticSCM)** | Versiyon kontrolü ve takım içi eş zamanlı geliştirme için. |
| **Blender**                       | Şezlong, can simidi gibi çevre modellerinin oluşturulması. |
| **Photoshop / GIMP**              | UI ikonları ve arayüz grafikleri için. |

## 🧠 Planlanan Geliştirmeler

- 🦈 Gelişmiş yapay zekâ (köpek balığı saldırısı, yardım çığlığına koşma gibi)
- 🎒 Envanter ve araç-gereç sistemi
- 🍹 **Bar sistemi**: Oyuncunun zaman geçirip mini görevler alabildiği sosyal alanlar
- 🗺️ **Ada görünümü**: Farklı sahil bölgeleri arasında geçiş yapılabilen, üstten görünümlü ada haritası
- 🌅 **Gün sonu değerlendirme ekranı**: O günkü performansın özetlendiği detaylı rapor
- 🎯 Steam başarı sistemi ve oyuncu profili takibi
- 🧩 Mini aktiviteler (plaj voleybolu, şemsiye yerleştirme gibi eğlenceli yan görevler)
- 🧃 Enerji sistemi (karakterin eforuna göre yorgunluk ve performans takibi)


## 📹 Oynanış Videosu (isteğe bağlı)

[▶ Drive Link](https://youtu.be/örnek-link)

## 🎯 Yayın Hedefi

Bu proje, **Unity oyun motoru** kullanılarak geliştirilmektedir.  
Amacımız, BeachLifeGame’i **Steam** üzerinden yayınlayarak oyunculara eğlenceli ve anlamlı bir yaz tatili deneyimi sunmak.

## 🙋‍♂️ Geliştirici Hakkında

Bu proje, iki kişilik bir geliştirici ekip tarafından yürütülmektedir.  
Ben, **Ahmet Meşiş**, Bilgisayar Mühendisliği 3. sınıf öğrencisiyim.  
Oyun geliştirme alanında uzmanlaşmak için Unity ve C# üzerinde aktif olarak çalışıyor, bu projeyi hem öğrenmek hem de sektöre giriş yapmak için bir basamak olarak görüyorum.

---

> Daha fazla bilgi veya iletişim için bana LinkedIn üzerinden ulaşabilirsiniz.  
> 👉 [linkedin.com/in/ahmetmesis](https://linkedin.com/in/ahmetmesis)
