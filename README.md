<img width=100% src="https://capsule-render.vercel.app/api?type=rect&color=0:1a6e2c,100:43a341&section=header&height=120&text=Infraçoes%20registradas%20pelo%20DER%20DF%&desc=Tratamento%20e%20visualização%20de%20dados&animation=fadeIn&fontColor=ffffff&fontSize=30&descSize=15&fontAlignY=45&descAlignY=70"/>

<div> 
<img align=right width="35%" height="35%" src="https://lagosul.com.br/wp-content/uploads/2019/02/der-df.jpg">
  
## Sobre o projeto
Os datasets tratados e analisados neste projeto são referentes às infrações registradas pelo [Departamento de Estradas de Rodagem do Distrito Federal](https://www.der.df.gov.br/) no ano de 2021. Os arquivos podem ser encontrados no [Portal de Dados Abertos](https://dados.gov.br/dados/conjuntos-dados) do governo federal. Neste repositório é possível encontrar o código utilizado no processo de tratamento dos dados, bem como alguns gráficos e dashboards construídos com as informações obtidas.
</div>
&nbsp;

## Sobre o tema
>A sigla DER DF é referente ao Departamento de Estradas de Rodagem do Distrito Federal. Segundo o site do órgão, o departamento tem como missão “Assegurar a qualidade da infraestrutura viária, do trânsito e da mobilidade nas rodovias do Distrito Federal, comprometida com o desenvolvimento sustentável”. Cabe ao DER a administração de rodovias e estradas estaduais.  E este princípio é válido tanto para o DER DF quanto para os respectivos Departamentos de Estradas de Rodagem de outros estados brasileiros.

>Dentre as competências estabelecidas, há a de fazer cumprir e também fazer com que se cumpra a legislação de trânsito. Desse modo, consequentemente, outra competência do DER é a de **fiscalizar, autuar e aplicar penalidades de advertência, multas** e também outras medidas direcionadas aos motoristas flagrados cometendo atos de infração de trânsito.

## Tecnologias utilizadas
[![Jupyter Notebook](https://img.shields.io/badge/jupyter-1a6e2c.svg?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/try)
[![Python](https://img.shields.io/badge/python-1a6e2c?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Power Bi](https://img.shields.io/badge/power_bi-1a6e2c?style=for-the-badge&logo=powerbi&logoColor=white)](https://powerbi.microsoft.com/pt-br/)

### Bibliotecas
[![Pandas](https://img.shields.io/badge/pandas-545454.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Glob](https://shields.io/badge/GLOB-545454?style=for-the-badge&logo=python&logoColor=white)](https://docs.python.org/3/library/glob.html#module-glob) 
[![Matplotlib](https://img.shields.io/badge/Matplotlib-545454?style=for-the-badge&logo=python&logoColor=white)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-545454?style=for-the-badge&logo=python&logoColor=white)](https://seaborn.pydata.org/)

## Conhecendo os dados
### Esquema original

| n° | Coluna                  |
|----|-------------------------|
|  0 | tipo_infracao           |
|  1 | descricao               |
|  2 | tipo_infrator           |
|  3 | tipo_veiculo            |
|  4 | cometimento             |
|  5 | hora_cometimento        |
|  6 | auinf_local_rodovia     |
|  7 | auinf_local_km          |
|  8 | auinf_local_referencia  |
|  9 | auinf_local_complemento |
| 10 | auinf_local_latitude    |
| 11 | auinf_local_longitude   |
| 12 | grav_tipo               |

## Resultados gerados
Realizada a limpeza dos dados, foram compilados em um só arquivo .csv para ser utilizado no software Power BI para geração de dashboards interativos. Abaixou seguem algumas imagens dos dashboards gerados.
