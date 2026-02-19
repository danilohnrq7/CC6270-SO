## Processos

- **Processo** é um programa carregado na memoria ram

- diferença entre programa e processo: programa são instruções num arquivo (modo que o ser humano entende), o processo são estas instruções traduzidas no que a máquina entender (binário) na memória RAM sendo executadas.

---

## - **Estados de um Processo:**
<img width="1113" height="533" alt="image" src="https://github.com/user-attachments/assets/e27363ec-0001-437c-864a-7126ef40abb0" />

- somente um processo pode estar executando em um processador.
- porém, muitos processos podem estar prontos e aguardando


## Process Control Block

- estrutura de dados (basicamente uma struct) que guarda informações sobre o processo

## Escalonamento de Processo
- Multiprogramação selecionar qual processador 

**- Tipos de Escalonadores**:
- curto praazo: fica trocando de pronto pra executando-aguardando o dia todo
- longo prazo: pega os programas do hd e insere na memória para serem executados

- o escalonador migra processos entre várias filas



