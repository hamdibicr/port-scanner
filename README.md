# Port Scanner
Basit ve kullanışlı API sistemi ve basitleştirilmiş yazma stili ile port tarama uygulaması.

## Gereksinimler
[Node.js](https://nodejs.org) komut dosyalarını 'npm' aracılığıyla çalıştırmak için gereklidir.

## Örnek
`http://localhost:300/api/process/127.0.0.1`

## Sonuç
``` 
{
    "success": true,
    "message": "Başarıyla port taraması gerçekleştirildi.",
    "ip": "acarfx.com.tr",
    "host": "acarfx.com.tr",
    "date": 1690179575276,
    "_service": "Port Scanner",
    "_allowservice": [
        {
            "port": 21,
            "service": "FTP"
        },
        {
            "port": 53,
            "service": "DNS"
        },
        {
            "port": 80,
            "service": "HTTP"
        },
        {
            "port": 110,
            "service": "POP3"
        },
        {
            "port": 143,
            "service": "IMAP"
        },
        {
            "port": 443,
            "service": "SSL"
        },
        {
            "port": 3306,
            "service": "MySQL"
        }
    ],
    "_deny": [
        22,
        23,
        25,
        115,
        135,
        139,
        194,
        445,
        1433,
        3000,
        3389,
        5000,
        5432,
        5900,
        8080,
        8081,
        8082,
        27017
    ],
    "_allow": [
        21,
        53,
        80,
        110,
        143,
        443,
        3306
    ]
}
```

## Mevcut Komutlar
`npm install`
`npm start`
