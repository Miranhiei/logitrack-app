# LogiTrack App 📦📱

Aplicativo mobile desenvolvido em React Native com Expo para monitoramento e gestão de robôs logísticos autônomos.

## 👥 Integrantes

| Nome                | RM       |
|---------------------|----------|
| Thiago Keide        | RM557946 |
| Giovanni Giacomeli  | RM555083 |
| Amaury Tenorio      | RM559108 |
| Mateus Miranda      | RM559215 |

## 🧠 Descrição

Este app é parte do projeto LogiTrack, que simula um sistema de controle de robôs logísticos inteligentes em ambientes internos. O aplicativo consome dados de um backend desenvolvido em Spring Boot, mostrando:

- Robôs cadastrados
- Sensores e eventos sensoriais
- Entregas simuladas
- Perfil do usuário
- Login e navegação via tabs

## 🚀 Como rodar o projeto localmente

### 1. Instale o Expo CLI (se ainda não tiver)

```bash
npm install -g expo-cli
```

### 2. Clone o repositório

```bash
git clone https://github.com/Miranhiei/logitrack-app.git
cd logitrack-app
```

### 3. Instale as dependências

```bash
npm install --force
```

### 4. Rode o app

```bash
npx expo start
```

Use o aplicativo **Expo Go** no celular para escanear o QR code.

> ⚠️ Para comunicação com o backend, atualize a `baseURL` em `src/services/api.js` com o IP da sua máquina (ex: `http://192.168.0.103:8080/api`)

---

## 📁 Estrutura do projeto

- `src/screens/` → telas como Login, Dashboard, Robôs, Sensores
- `src/services/` → comunicação com backend
- `src/context/` → gerenciamento de autenticação
- `src/navigation/` → estrutura de navegação
- `src/constants/theme.js` → tema e cores
- `src/components/CustomDrawerContent.js` → menu lateral
- `App.js` → ponto de entrada principal

---

## 📄 Licença

Projeto acadêmico sem fins comerciais. Todos os direitos reservados aos autores.