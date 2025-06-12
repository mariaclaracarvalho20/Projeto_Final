# 📒 Diário Animado  

Um diário online seguro e moderno para registrar pensamentos, memórias e sonhos, usando Firebase para autenticação e armazenamento.  

## 🚀 Começando  

Siga estas instruções para configurar o projeto localmente.  

### 📋 Pré-requisitos  

- [Node.js](https://nodejs.org/) (v18 ou superior)  
- [Yarn](https://yarnpkg.com/) 
- Conta no [Firebase](https://firebase.google.com/) (para configurar o banco de dados)  

### 🔧 Instalação  

1. **Clone o repositório**  
   ```bash
   git clone https://github.com/seu-usuario/diario-animado.git
   cd diario-animado
   ```

2. **Instale o Yarn** (caso não tenha)  
   ```bash
   npm install --global yarn
   ```

3. **Instale as dependências**  
   ```bash
   yarn install
   ```

4. **Configure o Firebase**  
   - Crie um projeto no [Firebase Console](https://console.firebase.google.com/).  
   - Ative **Authentication** (Email/Password) e **Firestore Database**.  
   - Copie suas credenciais do Firebase e atualize o arquivo `src/firebase-config.js`.  

5. **Inicie o servidor de desenvolvimento**  
   ```bash
   yarn dev
   ```
   O projeto estará disponível em: [http://localhost:5173](http://localhost:5173)  

6. **(Opcional) Build para produção**  
   ```bash
   yarn build
   ```

## 🛠 Tecnologias Utilizadas  

- **Frontend:** HTML, CSS (Tailwind), JavaScript  
- **Autenticação & Banco de Dados:** Firebase (Auth, Firestore)  
- **Bundler:** Vite  
- **Gerenciamento de Pacotes:** Yarn  

## 📝 Licença  

Este projeto está sob a licença MIT.  

---  

### Onde colocar esse arquivo?  
Adicione o `README.md` na **raiz do seu projeto**, assim ele aparecerá automaticamente no GitHub.  

### Como enviar para o GitHub?  
Se você já tem um repositório criado:  

```bash
git add README.md
git commit -m "Adiciona README com instruções de setup"
git push origin main
```  

Se ainda não tem:  

```bash
git init
git add .
git commit -m "Primeiro commit: adiciona projeto Diário Animado"
git remote add origin https://github.com/seu-usuario/diario-animado.git
git push -u origin main
```  

