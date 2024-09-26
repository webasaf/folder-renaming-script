------------------------TR------------------------
# Klasör İsimlendirme Scripti

Bu Python scripti, belirli bir dizindeki klasörleri yeniden isimlendirmenize olanak tanır. Script, klasör isimlerinin belirli bir kısmını sabit tutarken, kullanıcı tarafından belirlenen bir isim ve ID ile dinamik olarak yeni isimler ekler. Script, yalnızca üst düzey klasörleri yeniden isimlendirir ve alt dizinlere ya da dosyalara dokunmaz. Ayrıca, isimlendirme işleminden sonra yapılan değişiklikleri geri alma seçeneği de sunar.

## Özellikler
- **Kullanıcı Tanımlı Klasör İsmi**: Klasör isminin hangi kısmının değişmeden kalacağını ve üst klasör ismini kullanıcı belirleyebilir.
- **Dinamik ID Üretimi**: Yeniden isimlendirilen her klasör, artan bir ID ile sona erdirilir.
- **Geri Alma Seçeneği**: İsimlendirme işleminden sonra, klasörleri eski isimlerine döndürme seçeneği sunulur.
- **İkinci CMD Penceresi**: Script, yeniden isimlendirme işleminden önce klasör listesini ayrı bir CMD penceresinde gösterir.

## Kullanım
1. Bu repository'yi klonlayın:
    ```bash
    git clone https://github.com/ornek-repo/klasor-isimlendirme-scripti.git
    ```
2. Script'i çalıştırın:
    ```bash
    python rename_folders.py
    ```
3. Aşağıdaki adımları takip edin:
    - Sabit kalacak klasör isminin kısmını belirleyin.
    - Üst klasör ismini girin.
    - İsimlendirme işlemini onaylayın.
    - Gerekirse geri alma işlemini yapabilirsiniz.

## Örnek Kullanım
Eğer dizin yapınız şöyleyse:


