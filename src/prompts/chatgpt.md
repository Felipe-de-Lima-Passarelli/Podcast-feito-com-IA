# 📚 Fluxo Completo para Criar o Podcast "A Guerra dos Selectores"

Este arquivo organiza os prompts e instruções para criar **todas as partes do podcast**: títulos, roteiro, capa e narração. Seguindo este fluxo, você consegue gerar o conteúdo completo de forma sequencial.

---

## 1️⃣ ChatGPT: Títulos

**Ação:** Criar nomes originais para o podcast.  
**Prompt:**  

> Você é um roteirista criativo especializado em podcasts de tecnologia. Sua missão é criar **5 sugestões de nomes originais** para um podcast sobre tecnologia focado em **front end**, feito por nerds. O podcast abordará dicas, novidades e tendências do mercado de front end.  
>
> **Requisitos:**  
> - Devem ser enxutos, com título e subtítulo.  
> - O título precisa conter um trocadilho nerd inspirado em franquias populares (ex: Harry Potter, Star Wars, Senhor dos Anéis).  
> - O nome deve transmitir algo forte e marcante ligado a front end (elementos visuais, interface, design, código, interação, etc.).  
>
> **Restrições:**  
> - Não usar palavras em inglês no título (o subtítulo pode ter).  
> - Não usar: JavaScript, Programador.  
> - Não usar frontend nem variações no título.

---

## 2️⃣ ChatGPT: Roteiro

**Ação:** Criar roteiro completo para o podcast.  
**Prompt:**  

> Você é um roteirista especialista em podcasts de tecnologia e precisa criar um **roteiro completo** para podcast de frontend chamado **"A Guerra dos Seletores - CSS, design e a batalha pelo layout perfeito"**, voltado para iniciantes em frontend.  
>
> **Formato do roteiro:**  
> 1. **INTRODUÇÃO:** Apresentação do podcast, tema da semana e conexão com o público iniciante.  
> 2. **CURIOSIDADE 1:** Conte uma curiosidade interessante e divertida sobre CSS, com exemplos simples.  
> 3. **CURIOSIDADE 2:** Apresente uma ferramenta útil para front-end, explicando como ajuda no dia a dia.  
> 4. **FINALIZAÇÃO:** Despedida leve e engajante, incluindo a frase: “Eu sou Felipe, e esse foi A Guerra dos Seletores dessa semana.”  
>
> **Instruções adicionais:**  
> - Linguagem acessível e próxima, sem perder o tom profissional.  
> - Humor nerd e referências geek leves.  
> - Transições naturais entre blocos.  
> - Evite exemplos de código complexos; use apenas ilustrações simples.  
> - Entregue pronto para leitura ou gravação.

---

## 3️⃣ ImageFX: Capa do Podcast

**Ação:** Criar arte de capa épica.  
**Prompt:**  

> Arte de capa épica para podcast no estilo de **pôster de Star Wars**, cinematográfica e dramática. Um **guerreiro futurista** segurando um **sabre de luz brilhante feito de código CSS** (`div { color: blue; }`). Fundo: **campo de batalha digital cósmico** com grids, elementos de interface, botões, caixas e pixels flutuando, representando design e layout de web. **Cores neon vibrantes, alto contraste, atmosfera sci-fi**.  
>
> **Título grande:** A Guerra dos Selectores  
> **Subtítulo menor:** CSS, JAVASCRIPT, REACT, HTML

---

## 4️⃣ Text-to-Speech: Narração

**Ação:** Gerar áudio do roteiro.  
**Prompt:**  

> Use o roteiro do podcast **"A Guerra dos Selectores"** como texto de entrada. Leia de forma natural, envolvente e fluida, com pausas apropriadas entre blocos. Destaque títulos e curiosidades com pequenas variações de tom. O áudio deve ficar agradável, engajante e pronto para publicação como episódio.

---

## 🔄 Sugestão de Fluxo de Trabalho Automático

1. **Gerar títulos** usando o ChatGPT → escolher o nome final.  
2. **Gerar roteiro completo** com ChatGPT → revisar e ajustar se necessário.  
3. **Criar capa** com ImageFX → exportar imagem final.  
4. **Gerar áudio** com ferramenta de Text-to-Speech → revisar a narração.  
5. **Publicar**: combinar capa + áudio + título para criar o episódio final do podcast.

---

> Dica: Você pode criar scripts simples em Python ou Node.js para chamar APIs do ChatGPT, ImageFX e TTS usando os prompts deste arquivo, permitindo gerar todo o conteúdo do podcast automaticamente.
