# Enterprise Challenge Sprint-2---Reply-sensores-e-graficos-

Enterprise Challenge - Sprint 1 - Reply
# FIAP - Inteligência artificial e data science

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# Nome do projeto
Fase 4 - Enterprise Challenge - Sprint 2

## Nome do grupo
20

## 👨‍🎓 Integrantes: 
- <a href="https://www.linkedin.com/company/inova-fusca">Guilherme Campos Hermanowski </a>
- <a href="https://www.linkedin.com/company/inova-fusca">Gabriel Viel </a>
- <a href="https://www.linkedin.com/company/inova-fusca">Fatima Candal</a>
- <a href="https://www.linkedin.com/company/inova-fusca"> Matheus Alboredo Soares</a> 
- <a href="https://www.linkedin.com/company/inova-fusca">Jonathan Willian Luft </a>

## 👩‍🏫 Professores:
### Tutor(a) 
- <a href="https://www.linkedin.com/company/inova-fusca">Leonardo Ruiz Orabona</a>
### Coordenador(a)
- <a href="https://www.linkedin.com/company/inova-fusca">ANDRÉ GODOI CHIOVATO</a>


## 📜 Justificativa do problema e descrição da solução proposta

<br>

Em cenários de produção onde há um grande número de maquinário atuando, é rotineiro que diferentes tipos de erros e falhas que acabem por gerar prejuízos e atrapalhar no andamento da produção aconteçam.
Mas e se esses prejuízos e paradas na produção pudessem ser previstos, e assim, antecipadamente evitados, dessa otimizando os processos de melhorando o fluxo de trabalho da empresa? É a partir dessa visão de negócio que surge nosso projeto. 
</p>
Nessa primeira etapa, focamos na construção de um algoritmo de simulação de sensores de monitoramento em equipamentos de produção, que posteriormente podem ser utilizados em dispositivos físicos reais, mas neste primeiro momento só simulamos para testes. Utilizando de sensores de temperatura, vibração, umidade e volume de produção, extraimos suas informações para um arquivo csv que posteriormente será utilizado para geração de gráficos para uma melhor análise e tomada de decisão.

## 🔧 Componentes
**Definição das tecnologias que serão utilizadas (linguagens de programação, sensores, plataformas de simulação, etc.):**

**Wokwi:**

  -	***Definição:*** Plataforma online para simulação de algoritmos para sensores e dispositivos físicos.<br>
  -	***Linguagem:*** C++.<br>
  -	***Propósito:*** O wokwi vem como uma plataforma para viabilizar os testes em sensores físicos, permitindo que seu usuário desenvolva códigos e organize sensores de maneira simulada antes de aplicar na prática, dessa forma evitando erros e danos aos dispositivos físicos.<br>
  -	***Funcionamento:*** permite criar, programar e testar projetos diretamente no navegador através de sesores simulados, assim, descartando a necessidade de hardware físico.<br>

**Sensores:**

  -	***DHT22:*** Armazenamento (S3) em nuvem e governança e controle de acesso sobre o armazenament (Lake Formation).<br>
  -	***MPU6050*** Através de replicação de dados do RDS e Lambda.<br>
  -	***BOTÃO:*** Ter um repositório sem impactar em ambiente produtivo (RDS) e também possibilitando uma futura fonte de dados para construção de Dashboards, além de servir de fonte de dados para a IA.<br>
  -	***Funcionamento:*** .<br>


## 🔧 Funcionamento
Preencher

## 👨‍🎓 Divisão de responsabilidades:
- Desenvolvimento do algoritmo de análise gráfica: <a href="https://www.linkedin.com/company/inova-fusca">Jonathan Willian Luft </a> e <a href="https://www.linkedin.com/company/inova-fusca">Fatima Candal</a>
- Testes de Sensores: <a href="https://www.linkedin.com/company/inova-fusca">Gabriel Viel </a>, <a href="https://www.linkedin.com/company/inova-fusca"> Matheus Alboredo Soares</a>,  e <a href="https://www.linkedin.com/company/inova-fusca">Guilherme  Campos Hermanowski </a>



## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>
