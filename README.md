# KişiRehberi (ContactOpedia)

Bu proje, React kullanılarak geliştirilmiş çok dilli bir kişi rehberi uygulamasıdır. Kullanıcılar kişileri ekleyebilir, düzenleyebilir, silebilir ve favorilere ekleyebilir.

## Özellikler

- Kişi ekleme, düzenleme ve silme
- Kişileri favorilere ekleme/çıkarma
- Rastgele kişi ekleme
- Tüm kişileri silme
- Çoklu dil desteği (Türkçe ve İngilizce)
- Responsive tasarım

## Kurulum

Projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları izleyin:

1. Repoyu klonlayın:
   ```
   git clone https://github.com/kullaniciadi/kisirehberi.git
   ```

2. Proje dizinine gidin:
   ```
   cd kisirehberi
   ```

3. Gerekli bağımlılıkları yükleyin:
   ```
   npm install
   ```

4. Uygulamayı başlatın:
   ```
   npm start
   ```

Uygulama varsayılan olarak `http://localhost:3000` adresinde çalışacaktır.

## Kullanılan Teknolojiler

- React
- Context API (Dil yönetimi için)
- Axios (API istekleri için)
- Bootstrap (Stil ve düzen için)
- React Hooks (useState, useCallback, useMemo)

## Proje Yapısı

- `src/Components`: React bileşenlerini içerir
- `src/context`: Dil bağlamını yöneten dosyaları içerir
- `src/translations`: Çeviri dosyalarını içerir
- `src/Utility`: Yardımcı fonksiyonları içerir (API çağrıları gibi)

## Katkıda Bulunma

1. Bu repoyu fork edin
2. Yeni bir özellik dalı oluşturun (`git checkout -b yeni-ozellik`)
3. Değişikliklerinizi commit edin (`git commit -am 'Yeni özellik: Açıklama'`)
4. Dalınıza push yapın (`git push origin yeni-ozellik`)
5. Bir Pull Request oluşturun

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasına bakın.

## İletişim

Sorularınız veya geri bildirimleriniz için lütfen [issue açın](https://github.com/kullaniciadi/kisirehberi/issues) veya benimle doğrudan iletişime geçin.

---

Mutlu kodlamalar! 🚀
