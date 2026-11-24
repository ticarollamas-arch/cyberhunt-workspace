# Cyber Hunt Lab — Workspace v0.1
Protótipo independente, estático, sem afiliação ao Google. Analisa texto localmente com sete regras heurísticas; não executa código, não clona repositórios, não acessa alvos, não confirma vulnerabilidades. Links são referências e não uma lista verificada de escopo. Não há login, persistência, integração IA ou backend VPS nesta versão. Não use como armazenamento de informações confidenciais em dispositivos compartilhados.

## Vercel
Importe este diretório em um repositório GitHub e selecione Framework Preset: Other. Sem build command; Output Directory: `.`. Alternativamente execute `npx vercel` no diretório, autenticando sua própria conta. Não há chaves necessárias.

## Local
`python3 -m http.server 8000` e abra http://localhost:8000. Testes: `npm test` (Node 18+).

## Próxima fase
Backend privado na VPS com autenticação, fila, análise defensiva de código próprio/autorizado em containers isolados e integração de ferramentas SAST/SCA. Vercel hospedará apenas a interface. Revisar regras oficiais antes de qualquer pesquisa; nenhuma submissão automática. A versão atual gera rascunhos e perguntas para IA, não patches executáveis.
