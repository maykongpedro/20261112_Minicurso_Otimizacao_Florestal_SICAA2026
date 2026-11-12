# Minicurso: Otimização de Operações para o Planejamento da Produção Florestal

Material do minicurso apresentado no **13º Simpósio de Ciências Agrárias e Ambientais (SICAA 2026)**, UFU, Campus Monte Carmelo (MG), em 12/11/2026.

Na palestra, os modelos aparecem prontos. Neste minicurso, você monta os modelos. Em cada exercício o caminho é o mesmo: **estimar → modelar → resolver → comparar**.

Não é preciso saber programar.

## O que tem aqui

| Arquivo | Bloco | O que é |
|---|---|---|
| [`00_abertura.html`](00_abertura.html) / [`.pdf`](00_abertura.pdf) | Abertura | Slides da abertura, com o plano do dia e os testes do Solver e do Colab |
| [`notebooks/00_teste_ambiente.ipynb`](notebooks/00_teste_ambiente.ipynb) | Abertura | Teste do Colab: instala o Pyomo e o HiGHS e resolve um modelo pequeno |
| [`excel/01_familia_silva.xlsx`](excel/01_familia_silva.xlsx) | 1 | A floresta da família Silva: primeiro modelo de programação linear, no papel e no Solver |
| [`excel/02_marcenaria.xlsx`](excel/02_marcenaria.xlsx) | 2 | A marcenaria Gralha Azul: um problema novo para modelar sozinho |
| [`excel/03_blocos_fabricas.xlsx`](excel/03_blocos_fabricas.xlsx) | 3 | Cada bloco vai para qual fábrica? 30 blocos e variáveis binárias no Solver |
| [`notebooks/01_familia_silva.ipynb`](notebooks/01_familia_silva.ipynb) | 4 | A família Silva em Python (Pyomo + HiGHS), com um loop de cenários |
| [`notebooks/03_blocos_fabricas.ipynb`](notebooks/03_blocos_fabricas.ipynb) | 4 | Os blocos e as fábricas com os 120 blocos, mapa e cenários de nova fábrica |
| [`notebooks/02_marcenaria.ipynb`](notebooks/02_marcenaria.ipynb) | Extra | A marcenaria em Python, para praticar em casa |
| [`excel/04_base_florestal.xlsx`](excel/04_base_florestal.xlsx) | 5 | Quanta floresta a fábrica precisa? A conta da base florestal, passo a passo |

Todos os dados são ilustrativos e não têm relação com nenhuma empresa real.

## Como usar

**Planilhas:** baixe o arquivo e abra no Excel para computador, com o suplemento **Solver** ativo (*Arquivo › Opções › Suplementos › Suplementos do Excel › Solver*). As células em amarelo-claro são para você preencher.

**Notebooks:** abra no [Google Colab](https://colab.research.google.com/) (*Arquivo › Abrir notebook › GitHub* e cole o endereço deste repositório) e salve uma cópia no seu Drive (*Arquivo › Salvar uma cópia no Drive*). Onde aparecer `____`, complete com o número ou o nome do dado. Para rodar tudo, use *Ambiente de execução › Executar tudo*.

**Abertura:** baixe o `00_abertura.html` e abra no navegador. Use → ou espaço para avançar, ← para voltar, **G** para ver a grade de slides e **F** para tela cheia. Se preferir, use o PDF.

## Autor

Maykon Pedro · [GitHub](https://github.com/maykongpedro) · [LinkedIn](https://www.linkedin.com/in/maykon-pedro-5ab009170/) · [blog](https://maykongpedro.github.io/maykon_pedro/)
