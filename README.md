# Treino da Fran (PWA)

App simples e estático para organizar o treino semanal, com salvamento local (localStorage), busca e opções de substituição. Funciona offline (PWA) e pode ser publicado no GitHub Pages.

## Publicar no GitHub Pages
1. Crie um repositório chamado `treino-fran-app` (ou outro nome).
2. Envie estes arquivos para a branch `main`.
3. No repositório, acesse **Settings › Pages** e em **Build and deployment** escolha **Deploy from a branch** com `main` e pasta raiz `/`.
4. Aguarde o deploy. A URL ficará em `https://<seu-usuario>.github.io/<nome-do-repo>/`.

## Rodar localmente
Basta abrir `index.html` no navegador. Em `http(s)://` a instalação como app (PWA) fica disponível.

## Estrutura
```
/treino-fran-app
  ├─ index.html
  ├─ js/app.js
  ├─ manifest.webmanifest
  ├─ sw.js
  └─ icons/
      ├─ icon-192.png
      └─ icon-512.png
```

## Licença
MIT
