<div align="center">

# ⚡ LFTools

### O canivete suíço de quem projeta elétrica no Revit

*Feito por um projetista, para projetistas.*

[![Download](https://img.shields.io/badge/⬇_Baixar_última_versão-2ea44f?style=for-the-badge)](https://github.com/luisfernandoeng/LFTools-Releases/releases/latest)

**Compatível com Revit 2024 · 2025 · 2026**

</div>

---

## A história

Todo projetista de elétrica conhece a rotina: dimensionar circuito por circuito na calculadora, renumerar quadro inteiro porque o cliente mudou uma coisa, exportar 40 folhas uma a uma, caçar elemento sobreposto que está dobrando o quantitativo...

O LFTools nasceu das necessidades de um projetista, resolvendo esses problemas um por um — no projeto, no dia a dia, com prazo apertado especialmente. 
Cada botão existe porque alguém perdeu uma tarde fazendo aquilo na mão e decidi que seria a última vez.

Hoje são **mais de 30 ferramentas** organizadas em uma aba só: **LF Tools**.

---

## 🚀 Comece em 2 minutos

1. **Feche o Revit.**
2. [Baixe a última versão](https://github.com/luisfernandoeng/LFTools-Releases/releases/latest) — escolha o instalador:
   - **SingleUser** → instala só para você, sem precisar de administrador *(recomendado)*
   - **MultiUser** → instala para todos os usuários da máquina (pede administrador)
3. Execute o MSI e avance até o fim.
4. Abra o Revit → a aba **LF Tools** aparece na faixa de opções.

> 💡 Quando sair uma versão nova, o LFTools avisa dentro do próprio Revit.

---

## 🧰 As ferramentas

> 💡 **Dica geral:** vários botões têm configuração escondida — segure **Shift** ao clicar para abrir as opções.

### ⚡ Elétrica — o coração da suíte

O painel que faz o LFTools valer a pena sozinho.

| Ferramenta | O que ela faz por você |
|---|---|
| **Sincronizar Circuitos** | Dimensiona **disjuntor, cabo e distância** de todos os circuitos de um quadro de uma vez, conforme **NBR 5410**. O que levava uma tarde vira um clique. |
| **Transferir Circuitos** | Move circuitos entre quadros, com conversão opcional de tensão e número de polos. Reorganizou o QDC? Sem refazer nada. |
| **Gerenciar Circuito** | Adiciona ou remove elementos de um circuito existente. Clique num elemento do circuito e edite. |
| **Renomear Circuitos** | Renumera, agrupa e reordena os circuitos de um quadro no padrão **que você definir** — e o quadro de cargas segue a nova ordem. |
| **Anotar Fiação** | Clique num eletroduto ou eletrocalha e o LFTools descobre **quais circuitos passam ali** e cria a anotação de condutores. Sim, ele rastreia o caminho sozinho. |
| **LF Eletrical → Energia** | Configura quadros e cria circuitos de energia para iluminação, tomadas e cargas em série. |
| **LF Eletrical → Dados** | Cria circuitos de dados e telecom (CV-, WF-, TEL-, PT-). |
| **Acoplar / Desacoplar** | Conecta (ou desconecta) eletrocalhas e eletrodutos em cadeia, sem briga com conectores. |
| **Conectar Eletrocalha** | Cria trechos de eletrocalha ligando elementos em sequência — tipo, dimensões e offset configuráveis. |
| **Conectar Eletroduto** | Conecta eletrodutos com ajustes assistidos: ângulos válidos, conexões e descidas resolvidas para você. |
| **Desviar** | Encontrou um clash? Cria o **desvio automático** em eletrodutos, eletrocalhas, dutos e tubos — direção e ângulo configuráveis. |
| **Substituir Elementos** | Troca famílias elétricas **preservando posição, circuito e parâmetros**. Até entre categorias diferentes. |
| **Pontos por Vínculo** | Lê o vínculo Revit (arquitetura, por exemplo) e coloca seus pontos elétricos e de dados **nos mesmos lugares**. |

### 🤖 Automatizar — o trabalho repetitivo, sem você

| Ferramenta | O que ela faz por você |
|---|---|
| **Gerar Folhas** | Exporta folhas **em lote** para DWG e/ou PDF. Configure uma vez, exporte o projeto inteiro. |
| **Transfer Settings** | Transfere padrões (filtros, modelos de vista, tipos elétricos) entre projetos — via API ou JSON, inclusive **entre versões diferentes do Revit**. |
| **Transferir Vistas** | Copia legendas, vistas de desenho e tabelas de outro projeto aberto para o atual. |
| **Parâmetros → Parameter Manager** | Gerencie parâmetros compartilhados em famílias e projetos num painel só. |
| **Parâmetros → Transfer Parâmetros** | Transfere valores de parâmetros de tipo entre projetos quando o mesmo tipo existe no destino. |
| **Parâmetros → Copiar Parâmetro** | Compõe várias origens (parâmetros, dados do circuito) num único parâmetro de texto de destino. Perfeito para tags compostas. |
| **Alterar Nível** | Muda o nível de vários elementos de uma vez — inclusive seleções mistas que o Revit se recusa a editar pela paleta. |

### 📊 Dados — do modelo para o papel

| Ferramenta | O que ela faz por você |
|---|---|
| **Planilhar** | Exporta, importa e **atualiza** dados do modelo em planilhas .xlsx. Também transforma Excel em tabelas visuais dentro de Vistas de Desenho. |
| **Memorial Elétrico** | Gera o **memorial descritivo e de cálculo** direto dos dados do Revit. O documento que ninguém gosta de escrever, escrito sozinho. |

### 💥 Compatibilização

| Ferramenta | O que ela faz por você |
|---|---|
| **LF Clash** | Detecta **colisões reais** (com profundidade de interferência, não só toque) entre o modelo e os vínculos. Filtra o ruído, mostra cada conflito no Revit e exporta **BCF 2.1** para ACC, Solibri e afins. |

### 🔍 Filtros e Limpeza — modelo saudável

| Ferramenta | O que ela faz por você |
|---|---|
| **Filtro +** | Filtra elementos por categoria, parâmetro, condição e valor — o filtro que o Revit deveria ter de fábrica. |
| **Elétrica** | Selecionou um quadro? Seleciona junto todos os circuitos e elementos ligados a ele. |
| **Soma Dist** | Soma comprimentos de eletrodutos, eletrocalhas, tubos, dutos e conexões da seleção. Quantitativo instantâneo. |
| **Smart Select Similar** | Seleciona elementos similares ao de referência — com critérios que **você** define. |
| **Overkill** | O clássico do AutoCAD, no Revit: encontra elementos sobrepostos e recursos não utilizados para limpeza do projeto. |

### ✏️ Anotação — documentação sem sofrimento

| Ferramenta | O que ela faz por você |
|---|---|
| **Nome Amb** | Cria notas de texto com dados dos ambientes **de um vínculo Revit** — o nome do ambiente da arquitetura, na sua planta. |
| **Anotar+** | Corrige orientação de anotações: espelha horizontal, vertical ou gira por ângulo definido. |
| **Merge Text** | Une várias notas de texto numa só. |
| **Numerar+** | Renumera elementos em sequência por qualquer parâmetro editável. |
| **Renomear+** | Renomeia parâmetros, tipos e notas de texto em lote — **com prévia** antes de aplicar. |

### 🎯 Smart — qualidade de vida

| Ferramenta | O que ela faz por você |
|---|---|
| **Smart Crop** | Ajusta a crop region da vista atual ou **copia o crop para outras vistas**. Pranchas alinhadas sem esforço. |
| **Smart Cotas** | Gera cadeias de cotas automáticas entre os elementos selecionados — detecta eixos, inclusive diagonais. |
| **Auto Save** | Salvamento automático do projeto, do jeito que o Revit nunca ofereceu. |

### 🖥️ Interface e Dev

| Ferramenta | O que ela faz por você |
|---|---|
| **Ocultar Abas** | Esconde as abas do Revit que você não usa. Menos poluição, mais foco. |
| **Inspecionar** | Relatório técnico completo dos elementos selecionados: parâmetros, família, fórmulas, geometria, materiais, conectores, circuitos e dependências. |
| **Geometria** | Exporta coordenadas e dados geométricos da seleção em JSON. |

---

## 📋 Requisitos

- Autodesk **Revit 2024, 2025 ou 2026**
- Windows 10/11
- Conexão com a internet (para aviso de atualizações)

## 💬 Suporte

Dúvidas, sugestões, licenças ou problemas:

**Luís Fernando Campos Machado** — [lufe.machado@gmail.com](mailto:lufe.machado@gmail.com)

Encontrou um bug? [Abra uma issue](https://github.com/luisfernandoeng/LFTools-Releases/issues) com a versão do Revit e o passo a passo.

---

<div align="center">

*Cada botão do LFTools é um dia de trabalho manual que você não vai perder mais.*

**[⬇ Baixar agora](https://github.com/luisfernandoeng/LFTools-Releases/releases/latest)**

</div>
