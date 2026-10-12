# SIGA_FATEC_REMAKE
Este repositório apresenta uma proposta de interface mais intuitiva e moderna para o SIGA da FATEC, oferecendo uma experiência mais clara para os alunos ao visualizar matrículas, notas, faltas, avisos e demais informações acadêmicas.


## TECNOLOGIAS
### FRONT-END
    
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### BACK-END
![node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)

### BANCO DE DADOS
![postgres](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

### NUVEM
![AW](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
          

## **LAYOUT FRONT-END**

Uma breve introdução de como foi planejado a interface do usuario, atendendo a todos os requisitos da plataforma e uma gama de cores mais amigavel

![layout_front-end](./docs_photo/image-1.png)

## **SCHEMA BANCO DE DADOS**

Foi proposto o PostgreSQL, planejado com usando as tabelas students, users, subjects, enrollments, grades, attendance e notices. As relações utilizam chaves primárias e estrangeiras para garantir a integridade dos dados.

![schema_bd](./squema_siga/mermaid-diagram.png)

## **MODELO DE DESENVOLVIMENTO**

Por ser um sistema público com regras definidas por legislação, inicialmente considerou-se o modelo cascata.
Entretanto, como este projeto é uma evolução do SIGA atual, adotou-se um modelo híbrido, onde cada etapa tradicional (requisitos, análise, implementação, testes) é tratada como um ciclo incremental.
Isso permite:

. Evolução gradual do sistema

. Correção de pontos problemáticos

. Adição de novas funcionalidades

. Análise contínua de riscos

. Testes e validações a cada entrega


## PROJETOS FUTUROS 

Para transformar este remake em um sistema acadêmico completo e robusto, algumas melhorias e tecnologias podem ser incorporadas futuramente:

🔐 Segurança

. Autenticação com JWT
. Hash seguro de senhas (bcrypt)

⚡ Escalabilidade

. Docker para containerização
. NGINX como proxy reverso

☁️ Infraestrutura em Nuvem

. AWS RDS para PostgreSQL gerenciado
. AWS S3 para armazenamento de documentos

## FEITO POR:

📚 Arthur Linhares 
