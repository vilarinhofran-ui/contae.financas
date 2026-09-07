# CONTAÊ

Sua vida financeira em um só lugar.

Aplicação web estática e PWA do CONTAÊ, com landing page, dashboard financeiro, planos Mensal e Anual, criação de perfil, checkout demonstrativo, lançamentos manuais, objetivos, curso e acesso administrativo de demonstração em ambiente local.

## Rodar localmente

O projeto não precisa de build para a versão atual. Sirva a pasta por HTTP para ativar o PWA:

```powershell
python -m http.server 4173
```

Abra `http://localhost:4173`.

## Publicar no Netlify

1. Crie um repositório GitHub vazio chamado `contae`.
2. No Netlify, escolha **Add new site > Import an existing project**.
3. Conecte o repositório GitHub.
4. Use `.` como diretório de publicação.
5. Não informe comando de build.

O arquivo `netlify.toml` já configura publicação estática, headers do PWA e fallback de rotas.

## Estado atual

A interface é um protótipo frontend. Login, pagamentos, e-mail, autorização administrativa, OCR e persistência de produção ainda precisam de backend e serviços reais. Nenhuma senha deve ser colocada no HTML ou JavaScript.

## Marca

CONTAÊ é uma solução da [Vilarinho Tech Solutions](https://vilarinhotechsolutions.com.br/).
