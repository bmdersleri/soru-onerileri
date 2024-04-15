# Soru Önerileri İçin JSON Şablonu

Sınav sorusu için soru önerileri aşağıdaki JSON şablona göre hazırlanacaktır.

Sorular aşağıda verilmiş olan JSON formatına uygun olmalıdır. 

|Anahtar Kelime |Açıklama |
| ------ | ------ |
| **question** | Soru cümlesi bu bölüme yazılmalıdır. |
| **difficulty** | Sorunun zorluk derecesi buraya yazılmalıdır (1: Kolay, 2: Orta, 3:Zor) |
| **choices** | Her bir soru için 5 şık yazılmalıdır, ilk şık doğru cevabı gösterir. |
 



```json
{
    "questions": [
        {
            "question": "Birinci örnek soru cümlesi buraya yazılmalı",
            "difficulty": 2,
            "choices": [
                "A şıkkı",
                "B şıkkı",
                "C şıkkı",
                "D Şıkkı",
                "E şıkkı"
            ]
        },
        {
            "question": "İkinci örnek soru cümlesi buraya yazılmalı",
            "difficulty": 3,
            "choices": [
                "Birinci seçenek",
                "İkinci seçenek",
                "Üçüncü seçenek",
                "Dördüncü seçenek",
                "Beşinci seçenek"
            ]
        }
    ]
}
```

[![Build Status]([https://travis-ci.org/joemccann/dillinger.svg?branch=master](https://github.com/bmdersleri/soru-onerileri/blob/main/qrcode.png))]
