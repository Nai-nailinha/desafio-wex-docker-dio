# Projeto Docker HTML - 2 Arquivos

Este projeto é uma aplicação HTML simples executada em um servidor Apache usando **Docker Compose**.  
O objetivo é cumprir o desafio de criar e rodar um site utilizando **apenas dois arquivos** no repositório.

## 📂 Estrutura de Arquivos
```
.
├── docker-compose.yml
└── index.html
```

- **docker-compose.yml** → Define o serviço Apache (httpd) e monta o arquivo HTML.  
- **index.html** → Página web exibida no navegador.

## 🚀 Como Executar
1. **Clonar este repositório**
```bash
git clone <URL_DO_REPO>
cd <PASTA_DO_REPO>
```

Subir o container
```
docker compose up -d
```

Acessar no navegador
Abra: http://localhost:8080

Parar o container
```
docker compose down
```

🛠 Requisitos
* Docker instalado
* Docker Compose instalado

🎯 Objetivo
Este projeto demonstra como hospedar rapidamente uma página HTML em um servidor Apache utilizando Docker, mantendo o repositório minimalista com apenas dois arquivos.
