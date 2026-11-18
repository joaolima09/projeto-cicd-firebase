# Projeto CI/CD Firebase

Aplicação web com Firebase Authentication e Cloud Firestore, integrada a um pipeline de CI/CD com GitHub Actions e GitHub Pages.

## Comandos

- `npm test`: executa os testes unitários
- `npm run test:firebase:local`: executa o teste de integração com Firebase
- `npm run build:local`: gera a pasta `dist`
- `npm start`: serve o build localmente

## Configuração local

1. Copie `.env.example` para `.env`.
2. Preencha as variáveis com os dados do app Web no Firebase.
3. Execute `npm run test:firebase:local` e `npm run build:local`.

O arquivo `.env` e a pasta `dist` não são versionados.

