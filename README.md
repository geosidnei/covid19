##Projeto de Mapeamento da Pandemia Covid 19
Made in ReactJS and PWA by (and Owner) Gustavo Pereira - Teacher at Digital Innovation One {gustavodio}
Objetivo: aprender como mapear os dados da Pandemia Covid 19 consumindo os dados da API de Javier Aviles (Murcia/España): {https://github.com/javieraviles}
Prazo de conclusão (deadline) A : 20/07/2020
Prazo de conclusão (deadline) B : 31/07/2020
Fonte dos dados: https://coronavirus-19-api.herokuapp.com/countries
Autor: Javier Aviles - Murcia (España) https://github.com/javieraviles
Uma ideia de melhoria: colocar a porcentagem de casos divididos pela população total\
dessa forma têm-se a real ideia da porcentagem da população afetada em cada nação.
Outra ideia dada pelo Gustavo é trocar o idioma: escreverei em alemão/legendado em inglês.

Estou analisando dados de alguns países  e mostrando um dashboard com seus principais dados.

p.s: Os códigos originais a serem abordados neste projeto são de Bruno Carneiro {instrutor na DIO/Araraquara - Brasil}

###bibliotecas e tecnologias utilizadas:
-ReactJS;
-PWA;
-Material UI.

#### exemplo de código javascript`````javascript
const path = 'https://coronavirus-19-api.herokkuapp.com/countries'

const headers = {
	method: 'get',
	mode:  'cors',
	cache: 'default'
}

function getCountry(country){
	return fetch(`${path})/s{country}`, headers)
	.then((response)) => response.json())
}

export default {
	getCountry
}
}
`````
#### Imagem provisória (da tela do projeto de Gustavo Pereira)
#####Em breve estará a imagem de meu projeto.


![dashboard](https://i.imgur.com/RDZiIAK.png "dashboard")
