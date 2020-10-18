#   EnjoyIt-PL3 

##  Team 

|           Name          |   Number   |               Role               |
|:-----------------------:|:----------:|:--------------------------------:|
|   Ana Beatriz Marques   | 2018274233 |              Gestão              |
|       André Silva       | 2018277921 |            Requisitos            |
|    Barbara Gonçalves    | 2018295452 |            Requisitos            |
|      Dinis Carvalho     | 2018278118 |          Desenvolvimento         |
| Diogo Ferreira Sobreira | 2018294861 |             Ambiente             |
|       Duarte Dias       | 2018293526 |            Requisitos            |
|    Francisca Calisto    | 2018290275 |            Requisitos            |
|     Francisca Sousa     | 2018279514 |              Gestão              |
|   Francisco Fernandes   | 2018278239 |          Desenvolvimento         |
|    Gabriel Fernandes    | 2018288117 |            Requisitos            |
|       João Antunes      | 2018287319 |          Desenvolvimento         |
| João Oliveira das Neves | 2018287319 |          Desenvolvimento         |
|        João Cruz        | 2018288464 |            Requisitos            |
|  João Pimentel Teixeira | 2018278532 |          Desenvolvimento         |
|      José Esperança     | 2018278596 |          Desenvolvimento         |
|         Marcelo         | 2017279510 |          Desenvolvimento         |
|    Maria Paula Viegas   | 2017125592 |              Gestão              |
|      Mariana Loreto     | 2018280762 |          Desenvolvimento         |
|       Mário Daniel      | 2018272507 |          Desenvolvimento         |
|      Miguel Rabuge      | 2018293728 |            Requisitos            |
|        Nuno Tiago       | 2017276208 |             Ambiente             |
|     Pedro Rodrigues     | 2018283166 |          Desenvolvimento         |
|     Rafael Baptista     | 2018277007 |              Gestão              |

- Pedro Rodrigues: Team Leader
- João Teixeira: Team Co-Leader / Development Leader
- Ana Beatriz Marques:Team Project Manager / Management Leader
- Francisca Calisto: Requirements Leader
- Diogo Sobreira: Environment Leader



## Project Structure

 	- Entregáveis
 		- organizados em pastas por sprints (sprint1, sprint2,...)
	- Gestão de projecto
	- Gestão de Qualidade (GQ)
		- manual de qualidade
		- gestão de configuração
		- atas da GQ
		- relatórios de progresso
		- plano de projecto
		- garantias de qualidade
	- Requisitos
	- Arquitectura
	- Design detalhado
	- Testes
	- Plano
		- Aceitação
		- Instalação
	- Manuais de utilização
	- Documentação (inputs, pesquisas, docs, artigos, etc. organizados por temas)
As componentes de desenvolvimento (o código e testes unitários) ficam na plataforma de desenvolvimento (Outsystems)


## Rules 

- Comentar __sempre__ os *Commits* com a informação __resumida__ e __clara__ do que foi alterado

- Só são dados *Pushes* para a __master__ de versões __funcionais__, __estáveis__ e devidamente __testadas__ pela equipa de Testes. 

- A __master__ deve ser uma versão pronta para entregar ao cliente em __qualquer altura__

- Em caso de acréscimo de funcionalidades deve ser criada uma *branch* específica para a nova versão para não destabilizar a *master*

- Cada um deve fazer constantemente *fetches* de forma a manter o seu repositório local __atualizado__ com o remoto

## In Development 

### Manual de Qualidade:

O Manual de Qualidade (MQ) descreve ‘tudo’. Imaginem que alguém entrava hoje para a equipa e era necessário explicar-lhe onde está a informação e como se usa e como é que e equipa trabalha. Este documento deve responder a todas essas dúvidas.

Trata-se de um documento vivo (daí ser comum usar wikis) e que deve estar sempre acessível a toda a equipa. Sendo um documento vivo sempre que são definidos novos procedimentos e/ou actualizados ele deve ser modificado e uma nova versão criada. Sempre que alguém detecta uma omissão ou erro deve poder pedir que ele seja alterado ou (se for uma wiki) alterar logo e notificar os ‘owners’ do MQ. Toda a equipa deve ser informada de alterações ao MQ e das razões dessa alteração. Daí que deve haver um canal interno próprio para notificar toda a equipa das alterações/actualizações ao MQ. O MQ não é todo escrito pela equipa de qualidade, mas sim por quem está perto do assunto em causa: questões de gestão por quem está agerir, questões de desenvolvimento por quem está a desenvolver, etc. Qualquer membro da equipa deve poder propor alterações à forma da equipa trabalhar e deve existir um mecanismo explicito para recolher e discutir essas propostas. Afinal, trata-se da ‘legislação’ que rege o funcionamento da equipa. A equipa de qualidade é a responsável pela manutenção ‘saudável’, actualizada e sem inconsistências do MQ.

- Página de rosto: nome da equipa, logotipo e contacto(s)
	 - Qual é a estrutura da equipa; quais as responsabilidades envolvidas? Quais os roles/papéis?
	 - Como são planeadas as actividades da equipa?
	 - Como são atribuídas tarefas? Como estimam o esforço envolvido? E como sabem que uma tarefa (qualquer tarefa) foi efectivamente realizada?
	 - Como é que monitorizam e acompanham as tarefas e o projecto como um todo?
- Gestão do produto (solução técnica)
    - Como são recolhidos, descritos e acompanhados os requisitos; onde e como estão armazenados?
    - Qual a estrutura da solução? (arquitectura e design)
    - Qual o aspecto visual e de interacção da solução?
    - Como se coordena a actividade da equipa de desenvolvimento?
    - Como é testado o produto e seus componentes?
    - Como são integrados os diversos componentes do produto?
    - Como é validado o produto desenvolvido?
    - Como se sabe se o cliente apreciou o produto desenvolvido (ou uma iteração)?
    - Como identificam e gerem riscos que podem afectar o projecto?
- Qualidade
    - Quais os procedimentos/práticas da equipa como um todo?
    - Como é garantido que esses procedimentos estão a ser efectivamente seguidos?
    - Que práticas correntes existem para melhorar todos os procedimentos definidos?
    - Como medem a qualidade dos processos?
    - Como medem a qualidade do produto?
    - Com garantem que cada membro da equipa tem as competências necessárias para desempenhar as suas responsabilidades?(treino e formação)
- Actividades transversais a toda a equipa
    - Como são tomadas decisões?
    - Como são resolvidos os conflitos?
    - Como são geridos os artefactos produzidos pela equipa? (código, binários, configurações, documentos, registos, atas de reuniões, entregáveis, imagens, etc.)
    - Quais e como são recolhidas métricas de todas as actividades realizadas?
    - Como se por quem (roles, não pessoas) são analizadas essas métricas?
- Anexos
    - Identificação da equipa: nomes, contactos (mail telefone, opcional), photo
    - identificação de todas as ferramentas e plataformas usadas pela equipa.
    - Formulários adoptados pela equipa
    - AOB (any other business)
### Documento de Requisitos 
- Casos de uso
- Mockups
- Mapa de navegação entre écrans

### Demo de leitura/escrita de um dispositio usb


## Client Contact 

- [Client Slack](https://app.slack.com/client/T01B5GBRC3C/C01B2DQR8AZ)

##  Contactos

 - Team e-mail: [esenjoyit@gmail.com](mailto:esenjoyit@gmail.com)

- Team Leader email: [pedror@student.dei.uc.pt](mailto:pedror@student.dei.uc.pt)

