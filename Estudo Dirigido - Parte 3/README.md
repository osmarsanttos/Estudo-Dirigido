# Processamento Digital de Sinais – Estudo Dirigido Parte 3

## 📌 Descrição
Este repositório contém o desenvolvimento da **Parte 3 do Estudo Dirigido de Processamento Digital de Sinais (PDS)**, abordando a **Análise no Domínio da Frequência**.

O objetivo desta atividade é compreender como sinais discretos podem ser representados espectralmente, analisando frequências dominantes, efeitos de aliasing, janelamento e aplicações da Transformada de Fourier e Transformada-Z.

---

## 📚 Conteúdos Estudados

- Transformada de Fourier em Tempo Discreto (DTFT);
- Transformada Discreta de Fourier (DFT);
- FFT (Fast Fourier Transform);
- Transformada-Z;
- Aliasing;
- Janelamento espectral.

---

## 📂 Estrutura do Repositório

```text
📁 teoria/
    └── resumo_teorico.pdf

📁 simulacoes/
    ├── questao1.m
    ├── questao2.m
    ├── questao3.m
    ├── questao4.m
    ├── questao5.m
    ├── questao6.m
    ├── questao7.m
    ├── questao8.m
    ├── questao9.m
    └── questao10.m

📁 resultados/
    ├── q1.png
    ├── q2.png
    ├── q3.png
    ├── q4.png
    ├── q5.png
    ├── q6.png
    ├── q7.png
    ├── q8.png
    ├── q9.png
    └── q10.png

README.md
🧪 Atividades Desenvolvidas
Questão 1

Geração de uma senoide discreta e análise espectral utilizando FFT para identificação da frequência dominante.

Questão 2

Soma de duas senoides distintas e verificação das componentes espectrais no domínio da frequência.

Questão 3

Análise do fenômeno de aliasing por redução da taxa de amostragem.

Questão 4

Aplicação de janela (Hamming/Hann) e comparação dos efeitos sobre o vazamento espectral.

Questão 5

Análise espectral de um sinal contaminado por ruído aditivo.

Questão 6

Implementação direta da DFT e comparação com a FFT, verificando equivalência dos resultados e custo computacional.

Questão 7

Determinação da resposta ao impulso do sistema:

H(z)=
1−0.8z
−1
1
	​


e análise de estabilidade.

Questão 8

Comparação da resolução espectral entre sinais com diferentes números de amostras.

Questão 9

Identificação de frequência principal e harmônicos em um sinal composto.

Questão 10

Análise espectral de um sinal real/simulado com ruído e interpretação física do espectro obtido.

🎯 Problema Norteador

A análise espectral permite identificar informações relevantes sobre o comportamento dinâmico de sistemas físicos a partir das frequências presentes em um sinal.

Em aplicações práticas, é possível detectar frequências dominantes, harmônicos, ruídos e padrões periódicos relacionados ao funcionamento do sistema. Entretanto, limitações como taxa de amostragem inadequada, aliasing, resolução espectral, ruído e janelamento devem ser consideradas durante a aquisição e processamento dos sinais.

🛠️ Ferramentas Utilizadas
MATLAB
ou
SciLab
👨‍💻 Autor

Osmar dos Santos Filho
Instituto Federal da Paraíba – IFPB
Curso: Engenharia da Computação
