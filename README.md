# 🌤️ ClimaticNow – Frontend

Interface web do sistema **ClimaticNow**, responsável por exibir informações de endereço e previsão climática de forma interativa, moderna e responsiva.  
O frontend consome a API do backend Laravel e apresenta os dados de forma amigável ao usuário.

---

## 🚀 Tecnologias Principais
- **Vue 3 + Vite** *(ou React/Next.js, dependendo da escolha final)*
- **Tailwind CSS** (design responsivo e limpo)
- **Axios** (requisições HTTP)
- **Pinia / Zustand** (gerenciamento de estado)
- **Chart.js / Recharts** (visualização de dados meteorológicos)

---

## 📌 Funcionalidades Principais
- Busca de CEP e exibição automática do endereço
- Exibição da previsão semanal do tempo
- Interface responsiva e intuitiva
- Comunicação com API Laravel
- Sistema de componentes reutilizáveis

---

## 📄 Documentação
Toda a documentação do projeto (conceito, arquitetura e etapas) está disponível no Notion:

🔗 [Acessar documentação completa](https://www.notion.so/ClimaticNow-2a6d844c940580379d22d27ec2d6786e)

---

## ⚙️ Como rodar localmente

```bash
# Clonar o repositório
git clone https://github.com/seuusuario/climaticnow-frontend.git
cd climaticnow-frontend

# Instalar dependências
npm install

# Rodar servidor de desenvolvimento
npm run dev
```

---

## 🧩 Comunicação com o Backend

Configure a variável de ambiente no arquivo .env do frontend:
```bash
VITE_API_BASE_URL=http://localhost:8000/api
```

---

## 🎨 Design

- Paleta principal: tons de azul (clima), amarelo (sol) e cinza claro (nuvens)

- Ícones vetoriais minimalistas

- Layout limpo e focado na informação

---

## 🧑‍💻 Autor

**ClimaticNow Team**

Frontend do MVP ClimaticNow — Sistema de previsão climática por CEP.
