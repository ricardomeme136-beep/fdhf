# Plano da Sofia 🌿

Uma pequena app web para acompanhar o plano alimentar da Sofia dia a dia — marcar o que
comeu, trocar por alternativas, ver um calendário do mês e (opcional) receber lembretes
das horas das refeições no iPhone.

Tudo funciona **localmente no telemóvel dela** (guardado no próprio Safari) — não há
servidor nem base de dados, por isso também não há custos a hospedar no GitHub Pages.

## Como publicar no GitHub Pages

1. Cria um repositório novo no GitHub (pode ser privado ou público).
2. Faz upload de todos estes ficheiros para a raiz do repositório:
   `index.html`, `style.css`, `app.js`, `manifest.json`, `sw.js` e a pasta `icons/`.
3. No repositório, vai a **Settings → Pages**.
4. Em "Source", escolhe a branch `main` e a pasta `/ (root)`, depois **Save**.
5. Ao fim de 1–2 minutos o GitHub mostra o link, algo como:
   `https://teu-utilizador.github.io/nome-do-repo/`

## Como instalar no iPhone dela

1. Abre o link acima no **Safari** (tem de ser Safari, não funciona bem noutros navegadores no iOS).
2. Toca no ícone de **Partilhar** (o quadrado com a seta a subir).
3. Escolhe **"Adicionar ao Ecrã Principal"**.
4. Confirma o nome ("Plano Sofia") e toca em **Adicionar**.

A partir daqui abre como uma app normal, em ecrã inteiro, com ícone próprio.

## Lembretes das refeições

O iPhone só permite notificações a apps abertas a partir do Ecrã Principal (passo acima é
obrigatório primeiro). Depois disso:

1. Abre a app pelo ícone no Ecrã Principal (não pelo Safari).
2. Toca no ícone do sino no topo.
3. Aceita a permissão de notificações quando o iOS perguntar.

A partir daí, a app avisa à hora de cada refeição (07:20, 10:30, 12:30, 16:30, 19:00, 22:00)
enquanto estiver instalada e tiver sido aberta recentemente. Nota honesta: o iOS é
restritivo com apps web em segundo plano — se ela não abrir a app durante vários dias
seguidos, os lembretes desse período podem falhar. Voltar a abrir a app repõe o agendamento.

## O que a app faz

- **Hoje** — todas as refeições do plano, com as alternativas originais como botões
  (ex: peixe *ou* ovo). Tocar marca essa opção como comida. Também dá para tocar em
  "comi outra coisa" e escrever uma substituição livre.
- **Calendário** — vista do mês, com um ponto verde nos dias completos e amarelo nos dias
  parcialmente cumpridos. Tocar num dia mostra e permite editar o registo desse dia.
- **Receita** — a receita da salada (ingredientes, modo de preparação e informação
  nutricional), tal como no plano original.
- Um pequeno indicativo de sequência semanal (folhinhas) e um anel de progresso do dia.

## Privacidade

Os dados (o que ela marcou como comido, dia a dia) ficam guardados só no Safari do
telemóvel dela, não são enviados para lado nenhum. Se ela desinstalar a app ou limpar
os dados do Safari, o histórico perde-se — não há backup automático neste momento.
