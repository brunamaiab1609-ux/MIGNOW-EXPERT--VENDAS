# MIG Expert — Dashboard MIGNOW

Dashboard pessoal de estudo e preparação comercial para a jornada MIG Expert: do estudo técnico SAP até a apresentação consultiva da Subscrição MIG.

## Como usar (rápido)

1. Baixe a pasta inteira (ou descompacte o ZIP) e mantenha junto:
   - `index.html`
   - `PORTFOLIO-MIGNOW.pdf`
2. Dê duplo clique em `index.html` — abre direto no navegador (Chrome ou Edge recomendados).
3. Marque os 4 pilares do dia em **Início** e siga a semana ativa em **Jornada → Semana ativa**.

Não precisa de servidor, login, instalação ou internet. Tudo roda dentro do navegador.

## O que tem dentro

Cinco painéis na barra lateral, cada um com sub-abas no topo:

- **Início** — visão geral do dia, semana ativa, 4 pilares (Estudo, Apresentação, Pitch, Revisão), streak e meta semanal
- **Jornada** — Semana ativa · Roadmap 15 semanas · Rotina diária · Histórico de 30 dias
- **Conteúdo** — Perfis de cliente (CIO, CFO, Basis, Negócio, Sponsor, Usuário) · Vocabulário · Flashcards · Módulos SAP · Mercado SAP
- **Comercial** — Portfólio MIGNOW (11 produtos, Subscrição em destaque) · Pitch & narrativa · Diagnósticos (Ballpark, EP, Readiness Check) · Apresentações reais
- **Checklist** — base de conhecimento essencial

## Onde seus dados ficam

Tudo é gravado no **localStorage do seu navegador**, na sua conta. Streak, dias completos, pilares, glossário editado, flashcards, apresentações, notas — nada disso sai do seu PC.

Como os dados ficam no navegador:

- **Cada pessoa que usar seu próprio computador/usuário tem dados separados.** O navegador não mistura.
- **Use sempre o mesmo navegador.** Se alternar entre Chrome e Edge, são dois progressos diferentes.
- **Não use aba anônima** — o navegador apaga tudo ao fechar.
- **Favorite a pasta** onde está o `index.html` para acessar sempre pelo mesmo caminho.

## Backup do seu progresso

No canto superior direito você tem três botões:

- **Backup** — baixa um JSON com tudo (streak, dias, pilares, notas, glossário, flashcards)
- **Importar** — restaura um backup desses
- **Exportar resumo** — gera um arquivo de texto bonito para revisar fora do dashboard

Recomendado: rodar **Backup** uma vez por semana e guardar o JSON no Drive/Dropbox.

## Compartilhar com outra pessoa

Quer dar este dashboard para uma colega usar a versão dela, separada da sua?

1. Mande a pasta inteira (ou o ZIP) para ela
2. Ela descompacta no PC dela e abre o `index.html`
3. Os dados dela ficam no navegador dela, totalmente isolados dos seus

Não tem nuvem nem servidor compartilhado — cada um roda a sua própria cópia local.

## Personalizar para outra pessoa (opcional)

Se a colega quiser ter o nome dela visível no dashboard:

1. Abra `index.html` em qualquer editor de texto (Notepad++, VS Code, até o Bloco de Notas)
2. Use **Localizar e substituir** (Ctrl+H):
   - Trocar `MIG Expert v4` pelo título dela (ex.: `Dashboard da Ana`)
   - Trocar `Estudo · Pitch · Portfólio MIGNOW` pelo subtítulo que ela quiser
3. Salve e abra de novo no navegador

O conteúdo de estudo (15 semanas, portfólio, perfis, módulos) permanece o mesmo — é o material MIGNOW comum a quem está nessa jornada.

## Trocar de PC sem perder progresso

1. No PC antigo: clique em **Backup** → salve o JSON
2. Mande o JSON pra você no PC novo (e-mail, Drive, pendrive)
3. No PC novo: abra o `index.html`, clique em **Importar**, escolha o JSON
4. Pronto, streak e progresso de volta

## Problemas conhecidos

| Sintoma | Causa | Solução |
|---|---|---|
| Streak zerou | Abriu em outro navegador ou aba anônima | Voltar ao navegador original |
| Botão Subscrição não abre PDF | `PORTFOLIO-MIGNOW.pdf` está fora da pasta | Manter o PDF na mesma pasta do `index.html` |
| Layout quebrado | Navegador muito antigo | Usar Chrome ou Edge atualizados |
| Tela escura/clara não muda | Cache | Ctrl+F5 para recarregar |

## Estrutura de pastas mínima

```
MIG Expert/
├── index.html              ← o dashboard
├── PORTFOLIO-MIGNOW.pdf    ← linkado pelo botão Subscrição
└── README.md               ← este arquivo
```

É só isso. Sem `node_modules`, sem build, sem dependências.

---

**MIGNOW · 2026** · Material de estudo interno para o programa MIG Expert.
