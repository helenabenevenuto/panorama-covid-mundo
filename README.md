[![author](https://img.shields.io/badge/author-Helena&nbsp;Benevenuto-red.svg)](https://www.linkedin.com/in/helenabenevenuto/) 
[![](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/) 
[![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](LICENSE) 
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/helenabenevenuto/panorama-covid-mundo/issues)

<p align="center">
  <img src="https://raw.githubusercontent.com/helenabenevenuto/panorama-covid-mundo/master/images/evolucao_casos_banner.gif" alt="covid_banner"height="400px" >
</p>

# Panorama do COVID-19 no mundo

A COVID-19 é uma doença infecciosa causada por um recém-descoberto coronavírus.

Estamos completando quase 2 anos desde o surgimento do vírus COVID-19. As
medidas para controle pandêmico adotadas por governos em todo mundo afetaram
significativamente a rotina de todos e é de grande interesse acompanharmos a
evolução da pandemia para saber seus reais efeitos e avaliar o retorno ao
convívio normal.

**Neste trabalho, uma análise exploratória dos dados fornecidos pela Our World in
Data (OWID) é feita, mostrando o avanço temporal de casos, óbitos e vacinação.**
Estudos comparativos e busca de correlações são feitos com intuito de melhor
compreender os dados. Animações como a mostrada acima são criadas e
interpretadas.

Esse é um fork do trabalho original que [pode ser encontrado aqui](https://github.com/chicolucio/panorama-covid-mundo),
atualizando os dados até Maio de 2022.

Para abrir o *notebook* do projeto no Colab:
[![Abra no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/helenabenevenuto/panorama-covid-mundo/blob/master/projeto_covid_colab.ipynb)

Caso prefira olhar em sua máquina local, clone o projeto e abra no Jupyter
Notebook o arquivo `projeto_covid.ipynb`. Para instruções mais detalhadas veja
a seção [Reproduzindo o estudo](#reproduzindo-o-estudo).

**Links:**

- [LinkedIn](https://www.linkedin.com/in/helenabenevenuto/)
- [Ciência Programada](https://cienciaprogramada.com.br/author/helenabenevenuto/)

## Reproduzindo o estudo

Caso queira reproduzir o estudo feito aqui, siga os passos:

1. clone o repositório
2. crie um [ambiente virtual Conda](https://cienciaprogramada.com.br/2020/08/ambiente-virtual-projeto-python/#conda) com o arquivo `environment.yml`
3. ative o ambiente virtual
4. em um Jupyter Notebook, rode por completo o notebook `projeto_covid.ipynb`. Deve rodar sem erro algum

```bash
git clone git@github.com:helenabenevenuto/panorama-covid-mundo.git
cd panorama-covid-mundo
conda env create -f environment.yml
conda activate covid
jupyter notebook
```

## Contribuindo

Contribuições são bem-vindas.

**Issues**

Submeta issues com respeito a:

- recomendações
- melhorias
- erros ou bugs

**Pull requests**

- antes de submeter um PR, abra uma issue
- fork o repositório
- clone o projeto para sua própria máquina
- faça commits para uma branch sua
- faça push do seu trabalho
- submeta seu pull request, explicando o que desenvolveu, para revisão

## Licença

GNU v3, veja [LICENSE](LICENSE).

## Citando este trabalho

Caso queira usar este trabalho em aulas, publicações científicas ou de qualquer
outra forma, cite-o como

F. L. S. Bustamante, Panorama do COVID-19 no mundo, 2022 - Disponível em:
https://github.com/chicolucio/panorama-covid-mundo
