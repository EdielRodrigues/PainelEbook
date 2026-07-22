PAINEL ADMINISTRATIVO — PERSONAL TRAINER

Este painel é um projeto separado do e-book do cliente.

MODO DEMONSTRAÇÃO
- O arquivo firebase-config.js começa com demoMode: true.
- Os usuários de demonstração ficam no localStorage do mesmo domínio.
- Para o painel e o cliente compartilharem os mesmos dados em demonstração, hospede os dois no mesmo domínio. Em Firebase real, podem ficar em endereços diferentes.

FIREBASE REAL
1. Coloque os mesmos dados públicos do Firebase no firebase-config.js dos dois projetos.
2. Altere demoMode para false.
3. Publique database.rules.json no Realtime Database.
4. Cadastre sua primeira conta pelo e-book.
5. No Firebase, altere manualmente users/UID/role para admin.
6. Entre neste painel usando essa conta.

SEGURANÇA
- Não coloque token privado do Mercado Pago nestes arquivos.
- A integração Pix será adicionada depois em servidor seguro/Cloud Functions.


PRESENÇA ONLINE
- O painel mostra quantos usuários estão online no e-book.
- A coluna Presença mostra online, offline e último sinal.
- Há filtros Online agora e Offline.
- Publique o database.rules.json atualizado.
