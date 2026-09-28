# Melon CRM para Windows — downloads

Instalador `.exe` do **Melon CRM para Windows**, a casca desktop que abre
`https://crm.melonai.com.br` numa janela propria (bandeja, notificacao nativa,
login pelo navegador). Codigo-fonte em
[InfraYsraell/melon-desktop](https://github.com/InfraYsraell/melon-desktop)
(privado).

## Baixar

Ver [Releases](../../releases) — a mais recente e a atual.

## Aviso: build interna, sem assinatura

Esta e a fase interna do app (decisao D4 do `PLANO.md`), enquanto a conta de
empresa da Melon no Microsoft Partner Center nao e verificada. O instalador
**nao tem assinatura digital**, e por isso:

- O Windows mostra **"O Windows protegeu o computador"** (SmartScreen) ao
  instalar. Clique em **Mais informacoes** e depois em **Executar assim
  mesmo**. Isso aparece de novo em cada versao nova — a reputacao do
  SmartScreen e por arquivo, nao por editora.
- Se o **Controle Inteligente de Aplicativos** (Smart App Control) do Windows
  estiver ligado, ele bloqueia qualquer app sem assinatura sem oferecer opcao
  de exceção. As saidas: desligar em *Seguranca do Windows → Controle de
  aplicativos e navegador*, ou esperar a versao assinada da Microsoft Store.
- O SHA-256 de cada instalador vai nas notas da propria release — confira
  antes de instalar.

Quando a conta de empresa estiver aprovada, o app passa a ser distribuido
assinado pela Microsoft Store, sem esse aviso.
