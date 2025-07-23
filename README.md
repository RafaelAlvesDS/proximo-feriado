# Próximo Feriado 📅

Uma aplicação web em React com TypeScript que mostra o próximo feriado basead- `npm run eject` - Ejeta as configurações do Create React Applocalização geográfica.

## 📋 Sobre o Projeto

Este projeto foi desenvolvido como parte do meu aprendizado em TypeScript. A aplicação:

- 📍 Utiliza geolocalização para identificar sua cidade e estado
- 🎉 Consulta uma API de feriados brasileiros
- ⏰ Calcula quantos dias faltam para o próximo feriado
- 🌐 Exibe informações detalhadas sobre o feriado

## 🚀 Tecnologias Utilizadas

- **React** - Biblioteca para construção da interface
- **TypeScript** - Superset do JavaScript com tipagem estática
- **Axios** - Cliente HTTP para requisições à API
- **Moment.js** - Biblioteca para manipulação de datas
- **Geolocation API** - Para obter coordenadas do usuário
- **Geocode API** - Para converter coordenadas em cidade/estado
- **Calendario.com.br API** - Para consultar feriados brasileiros

## 🛠️ Funcionalidades

- ✅ Detecção automática da localização do usuário
- ✅ Consulta de feriados específicos por cidade/estado
- ✅ Cálculo da diferença de dias até o próximo feriado
- ✅ Interface simples e intuitiva
- ✅ Tratamento de erros de geolocalização

## 📦 Instalação e Execução

### Pré-requisitos

- Node.js (versão 12 ou superior)
- npm ou yarn

### Passos

1. Clone o repositório:
```bash
git clone https://github.com/RafaelAlvesDS/proximo-feriado.git
cd proximo-feriado
```

2. Instale as dependências:
```bash
npm install
```

3. Execute a aplicação:
```bash
npm start
```

4. Abra [http://localhost:3000](http://localhost:3000) no seu navegador

## 🎯 Conceitos de TypeScript Aplicados

Durante o desenvolvimento deste projeto, pratiquei os seguintes conceitos de TypeScript:

- **Interfaces**: Definição da interface `Feriado` para tipagem dos dados
- **Tipagem de Estado**: Uso do `useState<Feriado>` com tipagem específica
- **Tipagem de APIs**: Declaração de tipos para respostas de APIs externas
- **Hooks com TypeScript**: Implementação do `useEffect` com tipagem adequada
- **Event Handling**: Tipagem de eventos de geolocalização
- **Manipulação de Arrays**: Uso de métodos como `filter()` com tipagem

## 🔧 Estrutura do Projeto

```
src/
├── App.tsx          # Componente principal da aplicação
├── App.css          # Estilos do componente App
├── index.tsx        # Ponto de entrada da aplicação
├── index.css        # Estilos globais
└── ...
```

## 📱 Como Usar

1. Ao acessar a aplicação, permita o acesso à sua localização
2. A aplicação automaticamente detectará sua cidade e estado
3. Será exibido o próximo feriado da sua região
4. Você verá a data e quantos dias faltam

## ⚠️ Observações

- É necessário permitir o acesso à geolocalização no navegador
- A aplicação funciona apenas para feriados brasileiros
- Alguns feriados podem variar por município

## 📄 Scripts Disponíveis

- `npm start` - Executa a aplicação em modo de desenvolvimento

- `npm test` - Executa os testes

- `npm run build` - Gera build de produção

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## 🤝 Contribuição

Este é um projeto de aprendizado, mas sugestões e melhorias são sempre bem-vindas!

---

Desenvolvido com ❤️ durante meus estudos de TypeScript
