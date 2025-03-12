# Case Study - Kazananların Seçilmesi Animasyonu

## Amaç

API isteklerinin verimli bir şekilde yönetilmesi, UI yaklaşımının ölçülmesi ve Reactivity konusunda yeteneklerinizi
ölçmektir.

## Zorunluluklar

1. **UI/UX (!!!):** Responsive bir tasarım yapılmalıdır.
    1. Sayfaların ve bileşenlerin kullanıcı dostu olmasına ve iyi bir kullanıcı deneyimi sunmasına,
    2. Estetik görüntü ve profesyonel bir izlenim oluşturmasına önem verilmelidir.

2. **Veriler:**  Aşağıdaki API'yi kullanarak verileri çekmelisiniz.
    - API: `--GET https://api-dev.simpliers.com/api/custom-projects/case/giveaway`
    - API'den çekilen verilerin içerisinde yorum listesini barındıran `entries` anahtarında bir *array* bulacaksınız.
    - Butona tıklandığında, bu *array*'ın içerisindeki yorumlardan rastgele bir ya da daha fazla kazanan seçmelisiniz.
    - Kazanan seçilene kadar 8 saniye (veya farklı bir süre boyunca) *array*'in içindeki yorumların karıştırıldığı bir animasyon göstermelisiniz. 

3. **Çekiliş Sonucu:** Kazananlar seçildikten sonra, sonuçlar sunucuya kaydedilmektedir.
    - API: `--POST https://api-dev.simpliers.com/api/custom-projects/case/save-result`
    - API'ye kazananların *winners* anahtarı ile göndermelisiniz.
    - İsteğin başarılı olup olmadığına dair kullanıcıyı bilgilendirmelisiniz.

## Bonus

1. **Tasarım** API'den çekilen verilerin içerisindeki diğer bilgileri de görselleştirmeniz bonustur.
2. **Dökümantasyon:**  Componentleri ve projeyi açıklayan bir döküman hazırlamak bir bonustur.

## Kullanılacak Teknolojiler
1. **Frontend:** Projeyi Vue 3 ile geliştirmenizi istiyoruz.
2. **UI Kütüphanesi:** Bootstrap 5.0+ tercih etmenizi istiyoruz.
3. **Kütüphaneler ve Methodoloji** İhtiyacınız olduğunda dileidğiniz açık kaynak kütüphaneleri tercih edebilirsiniz.

## Not

Geliştirdiğiniz proje yalnızca değerlendirme amacıyla kullanılacaktır. Araç, kitaplık ve metodoloji seçiminde en iyi uygulamalara öncelik verin.

Yapılacak çalışma tüm zorunlulukları karşılamıyor olsa bile yine de değerlendirmeye sunmaktan çekinmeyin.
