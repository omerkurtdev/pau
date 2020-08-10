+++
author = "Ömer Kurt"
authorLink = "https://www.omerkurt.dev"
categories = ["Markdown"]
date = 2020-08-08T21:00:00Z
description = "Bu yazımda sizlere Markdown'nın ne olduğundan bahsedeceğim."
featuredImage = ""
featuredImagePreview = "/images/markdown.png"
hiddenFromHomePage = false
hiddenFromSearch = false
lastmod = ""
license = ""
lightgallery = true
subtitle = "Markdown ile Blog Yazmak"
tags = ["Markdown"]
title = "Markdown ile Blog Yazmak"
[math]
enable = false
[toc]
enable = true

+++
Bu yazımda sizlere Markdown'nın ne olduğundan bahsedeceğim.
<!--more-->
Merhaba arkadaşlar, Markdown yani `.md` uzantılı belgeleri hiç gördünüz mü? Markdown, internette yazı yazmayı kolaylaştıran belge türü diyebiliriz. Hayatımızda o kadar text editör girdi ki yazıları düzenlemek çile haline geliyor, ama Markdown ise o kadar kolay ki birkaç örnekle göstereyim hemen.

## 1. Liste Gösterimi

```Markdown
- Liste 1
- Liste 2
- Liste 3 
```

Yazdığımızda böyle gözekecek.

* Liste 1
* Liste 2
* Liste 3

```Markdown
* Liste 1
* Liste 2
* Liste 3
 	* Liste 4
    * Liste 5
* Liste 6
```

* Liste 1
* Liste 2
* Liste 3
  * Liste 4
  * Liste 5
* Liste 6

```Markdown
- [x] Mailini kontrol et
- [ ] Websiteyi güncelle
- [ ] Mail at
```

* \[x\] Mailini kontrol et
* \[ \] Websiteyi güncelle
* \[ \] Mail at

## 2. Başlık Gösterimi

Hangi büyüklükte başlık istiyorsanız başına sadece `#` koymak yeterli.

```Markdown
## h2 Başlık
### h3 Başlık
#### h4 Başlık
##### h5 Başlık
###### h6 Başlık
```

## 3. Yazı Tipleri Gösterimi

### Bold

```Markdown
**Kalın yazılar yazmak için**
```

**Kalın yazılar yazmak için**

### Italics

Italics bir biçimde yazıyı vurgulamak için şöyle yazılmalı:

```Markdown
_Italics bir yazı_
```

_Italics bir yazı_

### Üstü çizili yazı(Strikethrough)

Üstü çizili yazı tipini kullanmak için sigma(`~`) kullanılır.

```Markdown
~~Üstü çizili yazı~~
```

~~Üstü çizili yazı~~

## 4. Alıntı Yapma

Alıntı yapmak için büyüktür(`>`) işaretini kullanmamız yeterli.

```Markdown
> "Ne Mutlu Türküm Diyene!"
```

> "Ne Mutlu Türküm Diyene!"

## 5. Kod

### Tek satır kod

```Markdown
`printf("Merhaba Dünya")`
```

`printf("Merhaba Dünya")`

### Çok satırlı kod

Çok satırlı kod yazmak için <code>\`\`\`</code> kullanılır.
{{< highlight markdown >}}

     <!DOCTYPE html>
    <html>
    <body>
    
    <h1>My First Heading</h1>
    <p>My first paragraph.</p>
    
    </body>
    </html> 

{{< / highlight >}}

     <!DOCTYPE html>
    <html>
    <body>
    
    <h1>My First Heading</h1>
    <p>My first paragraph.</p>
    
    </body>
    </html> 

## 6. Tablo Oluşturmak

Markdown'da tablo oluşturmak aşırı kolay.

    | YBS Öğrencileri | Proje |
    | --------- | ------- |
    | Öğrenci 1 | Proje 1 |
    | Öğrenci 2 | Proje 2 |
    | Öğrenci 3 | Proje 3 |

| YBS Öğrencileri | Proje |
| --- | --- |
| Öğrenci 1 | Proje 1 |
| Öğrenci 2 | Proje 2 |
| Öğrenci 3 | Proje 3 |

Yada  tablo generatorlar var işinizi daha da kolaylaştıran şu linklerden ulaşabilirsiniz:

* [tablesgenerator](https://www.tablesgenerator.com/markdown_tables)
* [tableconvert](https://tableconvert.com/)

## 7. Linkler

    <https://omerkurt.dev>
    <okurt16@posta.pau.edu.tr>
    [YBS](https://ybs.pau.edu.tr)

[https://omerkurt.dev](https://omerkurt.dev)

[okurt16@posta.pau.edu.tr](mailto:okurt16@posta.pau.edu.tr)

[YBS](https://ybs.pau.edu.tr)

## 8. Dipnotlar

Dipnotlar, yazının bütünlüğü bozulmadan referans yada notlar eklememize yarar. Üstünde çıkan numaraya tıklarsanız referansa yönlendirilirsiniz.
```
Burası dipnottur.[^1]

[^1]: Referans yada not
```

Burası dipnottur.[^1]

[^1]: Referans yada not

## 9. Fotoğraflar
```
![Manzara](/images/fotograf.jpg)
```
![Manzara](/images/fotograf.jpg)

Evet, bu yazımda sizlere Markdown yazmak için gerekli Markdown sözdizimlerinden bahsettim. Peki Markdown yazmak için hangi editör ideal sorusuna şahsi cevabım: [Joplin](https://joplinapp.org/)

Farklı alternatifler de var mesela [Simplenote](https://simplenote.com/)

Merak edenleriniz varsa bu postu nasıl yazdığımı, altta bulunan `Markdown Oku`'ya tıklayabilirler.

## Kaynaklar
- [markdownguide](https://www.markdownguide.org/getting-started/)
- [markdownguide](https://www.markdownguide.org/basic-syntax/)