# Talhão CRM (nome provisório)

CRM para profissionais do agronegócio que trabalham com vendas, geração de demanda e relacionamento com canais de distribuição: RTVs, promotores, consultores e equipes de revendas e cooperativas.

O projeto está na **fase 0: estruturação e validação**. Ainda não existe o sistema programado.

## O que tem aqui

| Arquivo | Conteúdo |
|---|---|
| `prototipo/index.html` | Página com três abas: **Plano do produto**, **Mercado e concorrentes** e **Protótipo do MVP** (simulação navegável do app no celular, com dados fictícios). Abra o arquivo no navegador. |

## Resumo das decisões

- **MVP:** clientes e contatos, registro de visita por voz com IA (o usuário confirma antes de salvar), linha do tempo por cliente, tarefas, funil de oportunidades em sacos, agenda com envio ao Google Agenda, campos demonstrativos e dias de campo (versão simples) e relatório mensal em PDF.
- **Posicionamento:** CRM de quem gera demanda no agro, com foco em relacionamento com o canal, campos e dias de campo, registros por voz e relatório do mês pronto.
- **Público inicial:** profissionais que escolhem a própria ferramenta (autônomos, consultores, RTVs de revendas). Depois, revendas, cooperativas e indústrias regionais.
- **Tecnologia proposta:** app em React Native/Expo (Android, iOS e web), banco local offline com sincronização, Supabase (Postgres, login, arquivos, separação por organização), transcrição de voz + modelo de linguagem, API oficial do Google Calendar.
- **Preço (hipótese):** R$ 59 a 89 por usuário/mês no plano individual. O mercado pratica R$ 59 a 100.

## Próximos passos

1. 20 entrevistas com RTVs, consultores e gerentes de revenda, mostrando o protótipo.
2. Teste "concierge" com 5 pessoas: áudios de visita pelo WhatsApp, registro e relatório mensal feitos manualmente.
3. Testar por dentro os concorrentes mais próximos (Noctua, AgroRota, Rural Rota, Agendor).
4. Só então iniciar o desenvolvimento do MVP.
