# Jogo do Número Secreto

[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)]
[![Status: Concluído](https://img.shields.io/badge/Status-Concluído-brightgreen)]
[![Licença: MIT](https://img.shields.io/badge/Licença-MIT-blue)]

---

## Status
Concluído  
Foco do projeto: JavaScript. HTML e CSS foram usados apenas como suporte para testar o código.

---

## Descrição
Um jogo simples de adivinhar o número secreto (1 a 10), com dicas de maior ou menor e contagem de tentativas.  
Inclui narração das mensagens usando **responsiveVoice**.  

> Observação: O HTML e CSS de suporte foram criados com ajuda de IA/exemplos online. Estou estudando essas tecnologias para, futuramente, criar projetos completos do zero.  

---

## Funcionalidades
- Geração aleatória do número secreto sem repetir números anteriores até o limite.  
- Feedback instantâneo ao jogador sobre se o número digitado é maior ou menor.  
- Contagem de tentativas até acertar.  
- Botão de reinício para jogar novamente sem recarregar a página.  
- Narração das mensagens usando **responsiveVoice**.  

---

## Como jogar
1. Abra o arquivo `index.html` no navegador.  
2. Digite um número entre 1 e 10 no campo de entrada.  
3. Clique em “Chutar” ou pressione Enter.  
4. Siga as dicas até acertar o número secreto.  
5. Clique em “Reiniciar” para jogar novamente.  

---

## Visualização Online
Teste o jogo diretamente no navegador: [Clique aqui para jogar](https://numerosecretobymonica.vercel.app/)  
*(Substitua pelo link do seu GitHub Pages após publicar)*

---

## Estrutura do código
| Função | Descrição |
|--------|-----------|
| `exibirMensagemInicial()` | Inicializa a tela com título e instruções. |
| `verificarChute()` | Checa o número digitado e atualiza o feedback e tentativas. |
| `gerarNumeroAleatorio()` | Gera o número secreto sem repetir os anteriores. |
| `limparCampo()` | Limpa o campo de entrada após cada tentativa. |
| `reiniciarJogo()` | Reinicia o jogo, reseta tentativas e atualiza a tela. |

---

## Tecnologias utilizadas
- **JavaScript** – foco principal do projeto  
- HTML & CSS – apenas para estrutura e exibição (fornecidos para teste do JS)  
- [responsiveVoice](https://responsivevoice.org/) – para narração  

---

## Licença
Este projeto está sob a licença **MIT**.  
Você pode usar, copiar, modificar e distribuir este código, desde que dê crédito à autora original.  

Para mais detalhes, veja o arquivo [LICENSE](./LICENSE).

---

## Autor
**Mônica** – Aprendiz de programadora, focada em JavaScript e lógica de programação, estudando HTML e CSS para projetos futuros.
# jogo-numero-secreto
Jogo simples em JavaScript onde o jogador tenta adivinhar um número secreto de 1 a 10. Inclui dicas de maior/menor, contagem de tentativas e narração com responsiveVoice. HTML/CSS de suporte usados para teste.
