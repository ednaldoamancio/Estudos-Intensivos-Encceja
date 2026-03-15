# Análise dos Padrões do Site Estudos Intensivos Encceja

## Estrutura de cada página de resumo
1. **Header**: Controles (Voltar + Modo Noturno)
2. **Header do Resumo**: Título criativo com emoji + frase motivacional juvenil dirigida a "Híngrid"
3. **Mapa Mental**: Caixa com borda dashed, nó central com gradiente, 3 branches
4. **Card "Papo Reto"**: Resumo da matéria com linguagem coloquial, destaques em `<span class="destaque">`
5. **Quiz (Autoavaliação)**: 2 questões de múltipla escolha (3 opções cada), feedback imediato
6. **Botão Conclusão**: Salva nota no localStorage e volta ao index
7. **Nav inferior**: Links para Início e Rotina

## Padrão de linguagem
- Tom juvenil, motivacional, direto ("Papo Reto", "Pega a visão", "Bora", "Foco na missão")
- Dirigido a "Híngrid" (nome da estudante)
- Explicações com exemplos do cotidiano
- Emojis nos títulos
- Feedback das questões explicativo e informal

## Padrão técnico
- HTML standalone (sem frameworks)
- CSS variables para temas claro/escuro
- localStorage para salvar progresso (chave: `edhumanas_status_CHAVE` e `edhumanas_nota_CHAVE`)
- Cores por disciplina:
  - História: #cc0000 (vermelho), accent: #ffdd00
  - Geografia: secondary #7f00ff, accent: #00e5ff
  - Linguagens: accent: #ff6600 (laranja)
  - Matemática: accent: #00cc66 (verde)
- Nav no rodapé com gradiente roxo-rosa

## Páginas existentes
- resumo_historia_1.html (chave: hist1) - Exploração Colonial
- resumo_geografia_1.html (chave: geo1) - Urbanização e Êxodo Rural
- resumo_linguagens_1.html (chave: ling1) - Interpretação de Textos
- resumo_matematica_1.html (chave: mat1) - Porcentagem e Regra de Três
- matematica_fracoes.html (chave: mat_treino) - Treino de frações
- regra_de_tres_simples.html (chave: regra3_simples) - Treino
- regra_de_tres_composta.html (chave: regra3_composta) - Treino

## Cartões "Em Produção" no index.html
- Ciências da Natureza (card-ciencias)
- Inglês (card-ingles)
- Artes (card-artes)

## Novas páginas necessárias (currículo EF2 SP)
Preciso pesquisar o currículo para definir os temas.
