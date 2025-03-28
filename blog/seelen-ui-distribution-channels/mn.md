# **Seelen ui: Суулгах аргууд ба шинэчлэх суваг**

## **Сууцт суулгах Сторал**

### **Microsoft Store (MSIX)**

Microsoft Store-ээс хамгийн сүүлийн хувилбарыг татаж авах. Энэ бол хамгийн найдвартай юм
 болон хэрэглэгчийн ээлтэй сонголт, автомат шинэчлэлттэй.

*   Ашиг:
    *   Автомат шинэчлэлтүүд.
    *   Баталгаажуулсан, Microsoft-ийн батлагдсан.
    *   Аюулгүй байдал, найдвартай байдал.
    *   Энэ хувилбараас болж .Exe суулгагчтай харьцуулахад хөнгөн хувилбар
         дибаг хийх тэмдэг орно.
*   ХОЛБОО:
    *   Шинэчлэлтүүд шинэчлэгдэхийн тулд ажлын 1-3 өдөр шаардагдана.
    *   Дибаг хийх, асуудлыг мэдээлэхэд хэцүү.

***

### **Winget (MSIX)**

Дараах командыг ашиглан хамгийн сүүлийн хувилбарыг суулгана уу.

```pwsh
winget install --id Seelen.SeelenUI
```

Түргэн суулгацын болон хурдан суулгац бүхий ижил давуу болон сул талууд
 коммандын шугам.

***

### \*\*. EXEST суулгагч \*\*

Setup.exe суулгагчийг FEEASES хуудсыг татаж аваад ажиллуул.

*   Ашиг:
    *   Нэн даруй шинэчлэлтээр хурдан суурилуулах.
    *   Шинэ хувилбарыг авах боломжтой болмогц нь мэдэгдэл хүлээн авна.
*   ХОЛБОО:
    *   Тоон гарын үсэг зураагүй, антивирусын сэрэмжлүүлгийг өдөөж болно.
    *   Энэ хувилбар нь дибаг хийгдсэн тул MSIX суулгагчтай харьцуулахад бага хөнгөн жинтэй
         тэмдэг.

## **Суваг шинэчлэх**

> Шинэчлэлтийн суваг дахь Хөргөгч бүх хувилбарууд нь автомат шинэчлэлтүүдийг хүлээн авдаг,
>  Хэрэв та тогтворгүй шинэчлэлт суваг ашиглах боломжтой бол мөн шинэчлэлтүүдийг авах болно
>  Илүү тогтвортой шинэчлэлтийн сувгууд, жишээ нь: Шөнийн шинэчлэлтүүдийг шөнийн шинэчлэлтийг хүлээн авах боловч
>  Бета, суллахаас

### **Суллах (тогтвортой)**

Бүх хэрэглэгчдэд хамгийн найдвартай, санал болгож буй суваг.

*   Онцлог:
    *   Шүүмжлэлтэй алдаануудыг сайтар туршиж үзсэн.
    *   Үйлдвэрлэл, өдөр тутмын хэрэглээнд хамгийн тохиромжтой.
    *   Microsoft Store, Winget, Winget, .msix, .exe, .exe.

### **Бёа**

Албан ёсоор суллахаас өмнө шинэ шинж чанаруудыг туршиж үзэхийг хүсч буй хэрэглэгчид рүү чиглэсэн.
 Энэ суваг нь бета ба нэр дэвшигчд багтдаг.

*   Онцлог:
    *   Туршилтын дор шинэ шинж чанаруудыг агуулдаг.
    *   Бага зэргийн алдаатай байж болно.
    *   Тогтвортой хувилбараас илүү олон удаа олон удаа шинэчлэлт хийх.
    *   Дээрх хуудасны хуудсан дээр л .exe-д ашиглах боломжтой.

### **Муу**

Хамгийн сүүлийн үеийн өөрчлөлтөд нэвтрэхийг хүсч байгаа дэвшилтэт хэрэглэгчид, хөгжүүлэгчдэд зориулсан
 туршилтын шинж чанарууд.

*   Онцлог:
    *   Хамгийн сүүлийн өөрчлөлтийг багтаасан боловч сайтар туршиж үзээгүй болно.
    *   Алдаанууд эсвэл дуусаагүй шинж чанарыг агуулж болно.
    *   Өдөр бүр шинэчлэгдсэн эсвэл бүх чухал кодын өөрчлөлттэй шинэчлэгдсэн.
    *   Зөвхөн .EASES-ийн хуудсан дээрх.

Талаар дэлгэрэнгүй унших [Seelen ui nighly](./nightly.md)

## **Setup.exe vs msix дээрх шинэчлэлтийг хүлээн авах**

MSIX-ийн шинэчлэлтүүд Microsoft Store-ээр удирддаг, гэхдээ тохируулга.exe дээр тэдгээр нь байдаг
 биш, тийм болохоор шинэчлэгч програмыг багтаасан болно. Энэ нь танд үзүүлэх болно
 Шинэчлэлт хийх боломжтой үед мэдэгдэл.

![Seelen UI update notification on settings window](https://github.com/Seelen-Inc/slu-blog/blob/master/blog/seelen-ui-distribution-channels/image.png?raw=true)

Хэрэв та мэдэгдэл дээр дарвал энэ нь татаж авах, суулгах болно
 Энэ нь програмыг автоматаар дахин эхлүүлэх болно.
