# Scripts, Estudos e Insights

<!-- project-badges:start -->
![Linguagem: Python](https://img.shields.io/static/v1?label=Linguagem&message=Python&color=3776AB&style=flat)
![Formato: Scripts · Notebooks](https://img.shields.io/static/v1?label=Formato&message=Scripts%20%C2%B7%20Notebooks&color=F37626&style=flat)
[![Autoria: Rebeca Diniz Moura](https://img.shields.io/static/v1?label=Autoria&message=Rebeca%20Diniz%20Moura&color=8b5cf6&style=flat)](https://github.com/RebecaGis)
<!-- project-badges:end -->


Coleção de estudos em Python e notebooks de geoprocessamento, geocodificação e processamento de imagens.

Este repositório reúne exercícios de aprendizado e ferramentas com ambientes diferentes. Os arquivos são independentes; não constituem um único aplicativo.

## Índice

| Grupo | Exemplos | Ambiente |
| --- | --- | --- |
| Fundamentos de Python | `fatorial.py`, `soma_digitos.py`, `vogais.py`, `ordenacao.py` | Python 3 |
| Lógica e exercícios | `fizzbuzz.py`, `maior_primo.py`, `Jogo_nim.py` | Python 3 |
| Geocodificação | Notebooks com Geocoding ou Geocodificação no nome | Conferir bibliotecas e entradas no notebook |
| Logradouros próximos | Notebook de Identificação de Tipo de Logradouro Próximo | ArcGIS Pro com ArcPy e licença compatível |
| Imagens | Notebook de Redução de tamanho de imagens em lote | Conferir dependências no notebook |
| Rascunhos | `teste 2.py`, `teste3.py`, `exercicio 2.py` | Exemplos experimentais |

## Obter e executar

```bash
git clone https://github.com/RebecaGis/Scripts-Estudos-Insights.git
cd Scripts-Estudos-Insights
python fatorial.py
```

Leia o arquivo antes de executá-lo: alguns scripts pedem entradas interativas ou usam caminhos locais. Para nomes com espaços, use aspas, por exemplo `python "par ou impar.py"`.

Abra arquivos `.ipynb` em um ambiente compatível. Notebooks que dependem de ArcPy devem ser executados no ArcGIS Pro; Jupyter e Google Colab não substituem essa dependência.

## Dados e dependências

Não há um ambiente único de dependências. Consulte as importações e instruções de cada arquivo, configure seus próprios caminhos e use cópias dos dados de entrada, especialmente em rotinas que atualizam atributos ou gravam arquivos.

Os exemplos são materiais de estudo. Valide os resultados com casos conhecidos antes de reutilizar uma rotina em trabalho técnico. Credenciais, dados pessoais e arquivos de entrada locais não devem ser adicionados ao repositório.

## Organização

Os nomes e caminhos existentes foram mantidos para preservar referências aos notebooks. O índice acima permite navegar por assunto sem mover os arquivos.
