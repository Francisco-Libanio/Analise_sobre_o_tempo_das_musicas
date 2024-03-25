# Analise_Musical
Analise do tempo de música dos últimos 20 anos
Este projeto tem como objetivo analisar o tempo das músicas nos ultimos 20 anos. 
Essa ideia surgiu após ouvir muitas opiniões nas redes sobre o efeito do Tiktok nas músicas.
Ouvi frases  como ...

"Olha só as músicas estão bem mais curtas hoje em dia"
"Hoje as músicas não tem mais a parte C"

Assim Criei uma base de dados coletando dados de várias playlists do spótify. O requisito escolhido foi encontrar playlist com o titulo as músicas "As musicas mais ouvidas [Ano]" Para diversificar a base optei por capturar dados de várias playlists oficiais da plataforma e de usuários. E Através de Web scriping capturar dados de playlist em sites e blogs especializados.
O resultado foi uma base com os seguintes dados.

# Descrição da base

## Generos músicais
Os generos músicais mais reproduzidos nos útimos 20 anos.

| Gênero            | Contagem |
|-------------------|----------|
| sertanejo         | 520      |
| pop               | 425      |
| dance pop         | 335      |
| hip hop           | 288      |
| arrocha           | 169      |
| axe               | 158      |
| brazilian rock    | 135      |
| funk carioca      | 95       |
| pagode            | 91       |
| alternative metal | 81       |


## Número de músicas por ano 
Este projeto está em contante atualização, o propósito é deixar a amostra mais homogenea
| Ano   | Contagem |
|-------|----------|
| 2005  | 188      |
| 2023  | 184      |
| 2022  | 183      |
| 2019  | 177      |
| 2001  | 172      |
| 2017  | 168      |
| 2018  | 159      |
| 2016  | 152      |
| 2003  | 138      |
| 2002  | 136      |
| 2021  | 134      |
| 2004  | 132      |
| 2015  | 127      |
| 2006  | 124      |
| 2012  | 123      |
| 2020  | 119      |
| 2010  | 115      |
| 2007  | 113      |
| 2014  | 112      |
| 2008  | 109      |
| 2000  | 107      |
| 2011  | 104      |
| 2009  | 99       |
| 2013  | 99       |
| 1999  | 68       |

# Analisando o tempo de reprodução
No grafico de Regressão linear a baixo podemos ver que existe sim uma tendencia de redução no tempo de reprodução das músuca ao longo do ano.

![regressao](https://github.com/Francisco-Libanio/Analise_Musical/assets/75691960/885e65a4-de3e-41c9-a8db-3996efef6292)

Conseguimos evidenciar melhor essa tendencia usando um gráfico de linha com a média de tempo das músicas ao longo dos anos

![Linha-media](https://github.com/Francisco-Libanio/Analise_Musical/assets/75691960/c82211ea-d635-45ae-af66-fe3c46dc747c)

No gráfico a baixo temos as maiores e menores músicas de cada ano, um caso interessante é que as maiores músicas dos anos de 2020, 2021, 2022 e 2023 são pot pourri que é a Junção de mais de duas músicas em uma mesma execução.
Observamos também uma tendencia de queda no tempo das menores músicas de cada ano.

![maiores_e_menores](https://github.com/Francisco-Libanio/Analise_Musical/assets/75691960/a3dad9c3-c078-4b82-afe5-ee7ee3ff1b03)