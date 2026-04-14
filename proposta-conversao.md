# Proposta de Melhoria de Conversão: Landing Page COC

Esta proposta foi elaborada aplicando os 10 pilares de Design Orientado a Conversão (Conversion Design Review), com foco no objetivo principal: **Fazer com que os alunos aceitem participar das Olimpíadas (inscrição/engajamento)**, considerando que ainda não há provas sociais expressivas (depoimentos e métricas em larga escala).

## Resumo Executivo
* **Objetivo Primário:** Incentivar a participação e inscrição nas trilhas e cursos preparatórios.
* **Público-Alvo:** Estudantes do 6º ano do Ensino Fundamental ao 3º ano do Ensino Médio.
* **Diagnóstico Atual:** A página tem um design excelente, visualmente atraente e moderno (metáfora do espaço e foguete). No entanto, há oportunidades para tornar a jornada de conversão mais direta e reduzir a fricção na decisão do estudante, especialmente compensando a falta temporária de provas sociais.

---

## Análise por Pilares e Propostas de Mudança

### 1. Clarity Over Creativity (Clareza)
* **Diagnóstico:** O título "Lance seu conhecimento ao sucesso" é visual e inspirador, mas um pouco abstrato na primeira leitura.
* **Ação Recomendada:**
  * Adicionar um subtítulo (copy) focado no **benefício prático e imediato** para o estudante.
  * **Exemplo:** "Descubra como as Olimpíadas do Conhecimento podem transformar seu currículo, garantir bolsas de iniciação científica e facilitar sua entrada nas melhores universidades do país."

### 2. Strong Visual Hierarchy (Hierarquia Visual)
* **Diagnóstico:** Os CTAs no hero competem igualmente entre si (um preenchido, outro com bordas, mas pesos semelhantes no contexto do espaço escuro).
* **Ação Recomendada:**
  * Dar foco total ao botão primário de conversão e reduzir levemente o peso do botão secundário ("Explore Nossas Trilhas"). A ação de se inscrever deve ser o caminho óbvio e de menor atrito visual.

### 3. Single Primary Goal per Page (Objetivo Único)
* **Diagnóstico:** A página apresenta as trilhas, a equipe e os cursos com botões pulverizados. O usuário pode "baixar PDF" solto, sem deixar o contato.
* **Ação Recomendada:**
  * Unificar o objetivo: Captar o contato do aluno (Lead).
  * Em vez de fornecer os PDFs livremente nas trilhas, o CTA deve ser "Acessar Trilha Gratuita", redirecionando o aluno para um modal ou área de cadastro rápido. Ao informar o e-mail/WhatsApp, ele recebe o material, e o COC ganha o contato para nutrir e converter esse aluno para os cursos oficiais.

### 4. Obvious Calls to Action (CTAs Óbvios)
* **Diagnóstico:** O CTA primário é "Decole Rumo à Vitória: Prepare-se!". Apesar de temático, não segue a regra de completar a frase mental do usuário ("Eu quero...").
* **Ação Recomendada:**
  * **Mudar a Copy do CTA Principal:** Substituir por algo mais orientado à ação e com percepção de baixo risco. Exemplo: "Quero me Preparar Gratuitamente" ou "Quero Garantir Minha Vaga".
  * **CTAs das Trilhas:** Alterar de "Baixar PDF" para "Baixar Trilha Gratuita". A inclusão da palavra "gratuita" perto do clique aumenta consideravelmente o CTR (Click-Through Rate).

### 5. Low Cognitive Load (Baixa Carga Cognitiva)
* **Diagnóstico:** O design contém blocos de texto justificados (que foram alterados recentemente) muito longos. No mobile, textos longos e justificados geram "muros de texto" difíceis de escanear.
* **Ação Recomendada:**
  * Substituir parágrafos descritivos das trilhas e da seção "Sobre" por **Bullet Points (listas)** com ícones marcadores de check. O olhar do usuário escaneia melhor benefícios do que parágrafos.
  * Destacar palavras-chave em **negrito** e focar nos ganhos (ex: "Exercícios resolvidos", "Cronograma semanal").

### 6. Trust Before Persuasion (Confiança, na ausência de Prova Social)
* **Diagnóstico:** A seção de depoimentos foi ocultada porque ainda não há alunos suficientes para expor casos de sucesso expressivos.
* **Ação Recomendada:**
  * **Alavancar "Autoridade Emprestada":** Como não há prova social de alunos, utilize a autoridade da instituição e dos professores.
  * **Gatilho de Confiança (Trust Badge):** Adicionar uma barra (strip) visual logo abaixo da seção Hero, antes de rolar muito a página, contendo "trust signals" textuais:
    * *Uma iniciativa oficial do IFTO*
    * *Professores Especialistas (Mestres e Doutores)*
    * *Preparação 100% Gratuita para Rede Pública*

### 7. Mobile-First Design
* **Diagnóstico:** A animação grande do foguete no celular pode empurrar o CTA primário para baixo da "dobra" da página (área visível sem rolagem).
* **Ação Recomendada:**
  * Garantir que no formato Mobile o CTA principal ("Quero me Preparar Gratuitamente") apareça **antes** ou **acima** de grandes quebras visuais e animações que ocupem a tela inteira. O aluno precisa ver o botão no primeiro segundo de carregamento.

### 8. Speed and Performance
* **Diagnóstico:** Uso de vídeos (`.webm`) em autoplay para animações principais.
* **Ação Recomendada:**
  * Certificar de que o `foguete.webm` no Hero tenha uma imagem `poster="..."` altamente otimizada em `.webp`. Se a conexão de rede do aluno for lenta (comum em estudantes da rede pública no celular), ele verá a imagem instantaneamente e não um espaço preto aguardando carregamento, evitando abandono em 2 segundos.

### 9. Consistency
* **Diagnóstico:** Boa consistência visual geral, mas o tom de voz na conversão pode variar.
* **Ação Recomendada:**
  * Manter o tema "Espacial/Olimpíadas", mas sem perder a obviedade da ação.

### 10. Feedback and Reassurance (Tranquilização)
* **Diagnóstico:** Em volta dos botões e formulários faltam textos de suporte (microcopy).
* **Ação Recomendada:**
  * Adicionar uma microcopy logo abaixo do CTA principal para remover atrito de decisão.
  * **Exemplo (em texto pequeno, cor clara):** *"Cadastro rápido em 30 segundos. Sem compromisso financeiro."* Isso tira a ansiedade do estudante de "o que vai acontecer depois que eu clicar?".
