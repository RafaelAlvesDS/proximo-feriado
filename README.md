# Próximo Feriado

Pequeno app em React e TypeScript que mostra qual é o próximo feriado da sua cidade. Fiz para praticar TypeScript.

## Como funciona

1. Pede a sua localização ao navegador.
2. Descobre cidade e estado pelas coordenadas, com a API do geocode.xyz.
3. Busca os feriados do ano na API do calendario.com.br para essa cidade e pega o primeiro que ainda não passou.
4. Mostra o nome e a data do feriado e quantos dias faltam.

Feriados com `type_code` 9 são ignorados. Se você negar a permissão de localização, a tela fica com os valores vazios.

Está incompleto: as linhas "Faltam X semana(s)" e "XX:XX:XX horas" são texto fixo, ainda sem cálculo por trás.

## Rodar

```
npm install
npm start
```

Abre em `http://localhost:3000`. A API do calendario.com.br exige um token. Copie o `.env.example` para `.env` e preencha `REACT_APP_CALENDARIO_TOKEN`. Como o Create React App embute essa variável no JavaScript do build, o token fica visível para quem abrir o site publicado.

Criado com Create React App. O `README.old.md` é o texto padrão dele.
