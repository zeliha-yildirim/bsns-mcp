# Business Agent AI

Business Agent AI, işletmelere yönelik yapay zekâ destekli analiz ve karar destek süreçlerini kolaylaştırmak amacıyla geliştirilen çok platformlu bir uygulamadır.


## Özellikler

- Yapay zekâ destekli işletme analizi
- Web ve mobil platform desteği
- Analiz geçmişi görüntüleme
- Kullanıcı dostu arayüz
- API tabanlı haberleşme
- AI Agent mimarisi
- MCP (Model Context Protocol) desteği


## Kullanılan Teknolojiler

### Web

- React
- TypeScript
- Node.js

### Mobil

- React Native
- Expo

### Yapay Zekâ

- Python
- MCP (Model Context Protocol)

### Diğer

- REST API
- JSON
- Docker

## Proje Yapısı

```
Business-Agent/
│
├── business-agent/
│   ├── src/
│   ├── package.json
│   └── ...
│
├── business-agent-mobile/
│   ├── src/
│   ├── App.tsx
│   └── ...
│
├── bsns-mcp/
│   ├── app.py
│   ├── summarizer.py
│   └── requirements.txt
│
└── README.md
```


## Kurulum

### Web Uygulaması

```bash
cd business-agent
npm install
npm run dev
```

### Mobil Uygulama

```bash
cd business-agent-mobile
npm install
npx expo start
```

### MCP Servisi

```bash
cd bsns-mcp
pip install -r requirements.txt
python app.py
```


## Kullanım

Uygulama çalıştırıldıktan sonra kullanıcılar sistem üzerinden analiz işlemlerini gerçekleştirebilir, oluşturulan analiz sonuçlarını görüntüleyebilir ve geçmiş kayıtlarına erişebilir.

Web ve mobil uygulamalar aynı servis üzerinden haberleşerek ortak bir kullanıcı deneyimi sunmaktadır.


## Lisans

Bu proje eğitim ve araştırma amacıyla geliştirilmiştir.
