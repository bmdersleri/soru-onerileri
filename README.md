# Soru Önerileri İçin JSON Şablonu
Sınav sorusu için soru önerileri bu şablona göre hazırlanacaktır.

Sorular aşağıda verilmiş olan JSON formatona uygun olmalıdır. 

question: Soru cümlesi bu bölüme yazılmalıdır
difficulty: Sozunun zırluk derecesi buraya yazılmalıdır (1: Kolay, 2: Orta, 3:Zor)
choices: Her bir soru için 5 şık yazılmalıdır. İlk şık doğru cevap olmalıdır.




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

