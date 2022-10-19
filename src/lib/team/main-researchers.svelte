<script>
	import { language } from '$lib/language';
	import Face from './face.svelte';
</script>

<div class="position-relative ">
	<div class="row align-items-md-center">
		<div class="col-12 col-md-5 mb-6 mb-md-0">
			<h1 class="mb-0 lh-sm font-heading">
				{#if $language === 'pt'}
					Investigadoras Responsáveis
				{:else}
					Responsible Researchers
				{/if}
			</h1>
		</div>
	</div>
</div>
<div class="row mt-20 mt-xl-24 border-bottom pb-12 mb-24">
	<div class="col-6 mb-14">
		<Face
			name="Filipa Roldão"
			description="Centro de História da Universidade de Lisboa"
			link="https://www.cienciavitae.pt/1F12-45E5-8629"
			image="https://i.imgur.com/gYuWrF5.png"
			topics="Áreas de investigação (máximo 4): História Política e Institucional das cidades (séculos XII a XVII); Práticas de escrita e arquivos em meio urbano (séculos XII a XVII); Diplomática municipal; Paleografia medieval e moderna. "
			topicsEn="Political and Institutional History of cities (12th -17th centuries); Writing practices and archives in cities (12th -17th centuries); Municipal Diplomatics; Medieval and Modern Palaeography. "
		>
			<span slot="pt">
				Filipa Roldão é licenciada em História (2003) e mestre em Paleografia e Diplomática (2007)
				pela Universidade de Lisboa. Em 2011, obteve o seu doutoramento em História Medieval, pela
				mesma instituição, com uma tese intitulada «A memória da cidade. Administração urbana e
				práticas de escrita em Évora (1415-1536)». Em 2012, iniciou uma bolsa de pós-doutoramento
				atribuída pela Fundação para a Ciência e Tecnologia, com o seguinte tema de investigação:
				“Cidades do Reino. Cidades da Ásia: modelos e práticas de administração municipal (séculos
				XVI e XVII). De Évora a Cochim e Macau”. É, atualmente, investigadora integrada do Centro de
				História da Universidade de Lisboa (desde 2019). Participa regularmente em conferências
				nacionais e internacionais, assim como tem já diversas publicações em livros e revistas
				internacionais. Foi ou é hoje membro da equipa de três projetos de investigação nacionais,
				financiados pela Fundação para a Ciência e Tecnologia: Despertar dos Forais Manuelinos: a
				obra-prima vista à luz da ciência e tecnologia (2011-2014); Juiz da terra, juiz de fora.
				Justiça e comunidades num período de transição. 1481-1580 (2012-2015); Pensa em grande as
				pequenas cidades: Alto Alentejo e Alta Estremadura Leonesa. Séculos XIII e XVI (2021-2024).
				Atualmente, é investigadora responsável do projeto iForal. É membro da Sociedade Portuguesa
				de Estudos Medievais e colaboradora no IEM/FCSH-NOVA. É subdiretora do Centro de História da
				Universidade de Lisboa para a área das Humanidades Digitais.
			</span>
			<span slot="en">
				Filipa Roldão has completed a B.A. in History (2003) and a Master in Palaeography and
				Diplomatics (2007) at the University of Lisbon. In 2011, she has completed a Ph.D. (2011) on
				Medieval History at the same institution with a thesis entitled «A memória da cidade.
				Administração urbana e práticas de escrita em Évora (1415-1536)». In 2012, she was granted a
				post-doctoral fellowship by the Foundation for Science and Technology, entitled «Cities of
				the Kingdom. Cities of Asia: models and practices of municipal administration (16th and 17th
				centuries). From Évora to Cochim and Macao». She is now PhD Researcher at the Centre for
				History of the University of Lisbon (since 2019). She frequently participates in
				international and national conferences, and she has several publications in international
				books and journal articles. She was/is member of the research team of three national
				projects funded by Foundation for Science and Technology: The awakening of the Manuelin
				foral charters: science and technology insights into the masterpiece (2011-2014); Meet the
				Judge. Justice and Communities in a transitional period. 1481-1580 (2012-2015); Think big on
				small frontier towns: Alto Alentejo and Alta Extremadura Leonesa.13th - 16th centuries
				(2021-2024). Currently, she is the principal Investigator of iForal project. She is a member
				of the Portuguese Society for Medieval Studies, and a collaborator researcher of the
				IEM/FCSH-NOVA. She is sub-director of the Centre for History of the University of Lisbon in
				the field of Digital Humanities.
			</span>
		</Face>
	</div>
	<div class="col-6 mb-14">
		<Face
			name="Joana Serafim"
			link="https://www.cienciavitae.pt/portal/3311-416A-8567"
			description="Universidade de Zurique / Centro de Linguística da Universidade de Lisboa"
			image="https://i.imgur.com/ZGmIJwK.png"
			topics="Filologia latina e portuguesa, crítica textual, latim medieval"
			topicsEn="Latin and Portuguese philology, textual criticism, medieval Latin"
		>
			<span slot="pt">
				Joana Serafim é licenciada em Línguas e Literaturas Clássicas pela Faculdade de Letras da
				Universidade de Lisboa e doutorada em Literatura pela Universidade de Aveiro com a tese
				intitulada Traduções portuguesas do Pro Archia, de Cícero (2009). Lecionou em diferentes
				instituições de ensino superior, sendo atualmente docente de Língua Portuguesa e Literaturas
				em Português na Universidade de Zurique e diretora da Cátedra Carlos de Oliveira. Joana
				Serafim é investigadora integrada do grupo de Filologia do Centro de Linguística da
				Universidade de Lisboa desde 2009, tendo como principal área de investigação a Crítica
				Textual (textos medievais latinos e portugueses). É co-investigadora responsável do projeto
				“Forais medievais portugueses: uma perspetiva histórica e linguística na era digital”
				(projeto financiado pela Fundação para a Ciência e a Tecnologia: PTDC/HAR- HIS/5065/2020).
			</span>
			<span slot="en">
				Joana Serafim is graduated in Classical Languages and Literatures from Faculdade de Letras
				da Universidade de Lisboa and completed a PhD in Literature at Universidade de Aveiro (2009)
				with the thesis Portuguese Translations of Cicero's Pro Archia (2009). She has taught at
				different higher education institutions, and is currently Professor of Portuguese Language
				and Literature in Portuguese at the University of Zurich and Director of the Cátedra Carlos
				de Oliveira. Joana Serafim is integrated researcher of the Philology group of Centro de
				Linguística da Universidade de Lisboa since 2009 and her main research area concerns Textual
				Criticism (Latin and Portuguese medieval texts). She is co-investigator in the project
				"Portuguese municipal charters in the Middle Ages: an historical and linguistic approach in
				the digital era" (project funded by the Fundação para a Ciência e a Tecnologia: PTDC/HAR-
				HIS/5065/2020).
			</span>
		</Face>
	</div>
</div>
