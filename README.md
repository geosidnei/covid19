##Projeto de Mapeamento da Pandemia Covid 19
This Project will be made in ReactJS and PWA 
Sugested by Gustavo Pereira - Teacher at Digital Innovation One {Araraquara/SP/Brazil}
Objective: to learn how to map the info about Covid 19 Pandemia
using  the source data from Javier Aviles (Murcia/España) API: 
{https://github.com/javieraviles}
Deadline A: 31/12/2020; 
Deadline B: 31/07/2021; 
Source: https://coronavirus-19-api.herokuapp.com/countries
Autor: Javier Aviles - Murcia (España) https://github.com/javieraviles
An improvement idea: insert the percentage of total population with covid in each country;
This shows the real situation in each country.
Another idea: write this site in some languages like German (with subtitles in English or Spanish, perhapes);
I will analize dataset from some countryes und show a dashboard with more important numbers.
p.s: The original code will by searched in all dev community around this bad world.
###bibliotecs and technologies used:
-ReactJS;
-PWA;
-Material UI.

#### JavaScript cdde example: ````javascript
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

https://i.imgur.com/RDZiIAK.png

####Em breve estará a imagem de meu projeto.

https://imgur.com/gallery/ADS4ike
