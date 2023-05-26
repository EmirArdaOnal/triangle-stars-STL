# triangle-start-STL
Star Triangle Codes Made Using Function Block



1. İlk olarak, "MyFunctionBlock" adında bir Fonksiyon Bloğu oluşturulur. Bu Fonksiyon Bloğu, giriş ve çıkış değişkenlerini içerir.
   - Giriş değişkenleri:
     - "Yildiz" adında bir BOOL değişkeni: Bu giriş, yıldız girişine ilişkin durumu temsil eder.
     - "Ucgen" adında bir BOOL değişkeni: Bu giriş, üçgen girişine ilişkin durumu temsil eder.
   - Çıkış değişkeni:
     - "Q0" adında 0'dan 5'e kadar olan 6 elemanlı bir BOOL dizi: Bu çıkışlar, belirli durumlar için atanır.

2. "UpdateOutputs" adında bir metod tanımlanır. Bu metod, girişlere bağlı olarak çıkışları günceller.
   - "UpdateOutputs" metodunda şu işlemler gerçekleşir:
     - "Yildiz" girişi Q0[0], Q0[1] ve Q0[2]'ye atanır.
     - "Ucgen" girişi Q0[3], Q0[4] ve Q0[5]'e atanır.
     - Son olarak, metod TRUE değerini döndürerek çıkışların güncellendiğini bildirir.

3. Kodun çalışması için bu Function Block'un bir TIA Portal projesine eklenmesi gerekir. TIA Portal'da Function Block'u ekledikten sonra, girişlere uygun değerler atanabilir ve çıkışlar kullanılabilir.

4. Kodun çalışması için Function Block'u çağırmak ve girişlere uygun değerleri atamak gereklidir. Ardından, "UpdateOutputs" metodunu çağırmak çıkışları günceller ve belirli durumlara bağlı olarak Q0 dizisine değerler atanır.
