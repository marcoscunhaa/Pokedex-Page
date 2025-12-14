🧠 Pokédex App - Angular
========================

Frontend da aplicação **Pokédex**, desenvolvido em **Angular**, com estilização em **Tailwind CSS**, consumindo uma **API REST em Spring Boot** que por sua vez integra com a **PokéAPI**. A aplicação apresenta informações detalhadas dos Pokémon de forma moderna, responsiva e performática.



Este frontend pode ser executado de forma **independente em ambiente de desenvolvimento** ou **buildado e servido diretamente pelo backend Spring Boot**, conforme a arquitetura do projeto em produção.

🔗 **Backend (Spring Boot):** https://github.com/marcoscunhaa/Pokedex-API

🌐 **Aplicação em produção:** [http://137.184.186.231:8080/](http://137.184.186.231:8080/)

* * *

📑 Features
-----------

- 🔎 Busca de Pokémon por:
  
  - ID
  
  - Nome
  
  - Tipo
  
  - Habilidade
  
  - Movimento
  
  - Região

- 🧬 **Busca avançada**
  
  - Combinação de múltiplos filtros (tipos, habilidades, movimentos e regiões)

- 🎨 **Interface moderna e responsiva**
  
  - Layout adaptado para desktop e mobile
  
  - Estilização com Tailwind CSS

- ⚡ **Performance**
  
  - Consumo de API via RxJS
  
  - Componentização e boas práticas do Angular

- 🚀 **Deploy integrado**
  
  - Frontend buildado e servido via `static/` no backend Spring Boot

* * *

🛠️ Tecnologias Utilizadas
--------------------------

* **Angular CLI**: 17.3.17

* **Node.js**: 22.12.0

* **NPM**: 11.4.1

* **TypeScript**

* **RxJS**

* **Tailwind CSS**

* **Docker** (via backend)

* **DigitalOcean** (VM em produção)

* * *

📁 Estrutura de Ambientes
-------------------------

A aplicação possui dois arquivos de ambiente:

### 🔧 `environment.ts` (development)

    import { environment } from '../../environments/environment';

API apontando para o backend local: http://localhost:8080

### 🚀 `environment.prod.ts` (production)

    import { environment } from '../../environments/environment.prod';

API apontando para o backend hospedado na VM do DigitalOcean: http://137.184.186.231:8080

* * *

👨‍💻 Rodando o Frontend Localmente
-----------------------------------

### ✅ 1. Pré-requisitos

Certifique-se de ter instalado:

* Node.js v22.12.0

* NPM v11.4.1

* Angular CLI v17.3.17

* * *

### 🔄 2. Clone o repositório

```https://github.com/marcoscunhaa/Pokedex-Page
git clone https://github.com/marcoscunhaa/Pokedex-Page
cd Pokedex-with-Angular
```

* * *

### 💾 3. Instale as dependências

    npm install

* * *

### 🚀 4. Execute em ambiente de desenvolvimento

    ng serve

A aplicação ficará disponível em: http://localhost:4200

* * *

🐳 Produção (Build + Backend)
-----------------------------

- Em produção, o frontend Angular é **buildado** e copiado para a pasta:
  
      /backend/src/main/resources/static

- Dessa forma, toda a aplicação (frontend + backend) é acessada diretamente pelo navegador via Spring Boot:

🌐 **URL pública:**  http://137.184.186.231:8080/

* * *

📌 Observações
--------------

* O projeto segue boas práticas de componentização e organização de código Angular.

* O frontend foi projetado para funcionar tanto de forma independente quanto integrado ao backend.

* Ideal para estudo de **Full Stack Java + Angular**, Docker e deploy em VPS.

* * *

🚀 Desenvolvido por **Marcos Cunha**


