# DESAFIO-BEEDOO

## Histórias de Usuários

### Título: Cadastro de Curso

Descrição: Como administrador, quero cadastrar um curso na plataforma Beedoo QA Challenge para poder oferecer aulas online ou presenciais.

Critérios de Aceitação:

* O formulário de criação de curso deve ter os campos: Nome do curso, Descrição do curso, Instrutor, URL da imagem de capa, Data de início, Data de fim, Número de vagas e Tipo de curso.
* Todos os campos são obrigatórios.
* A Data de Início deve ser anterior à Data de Término.
* Após a criação bem-sucedida, deve aparecer uma mensagem "curso cadastrado com sucesso" e o curso deve ser listado na página listar cursos.

 Casos de Teste em Gherkin

* Os casos de teste foram escritos em Gherkin e estão disponíveis no arquivo [Casos_de_Testes_Cadastro_de_Cursos]([gherkin/test_cases.feature](https://docs.google.com/spreadsheets/d/1WVsvQlN5Ayz0i4YyX3plAKyk3aG8yjqyn_LRLnXQLEI/edit?usp=sharing)). Este arquivo inclui todos os cenários de sucesso e erro identificados para o módulo de curso.

*  As evidências dos testes estão no formato MP4 diponíveis em [Cadastro_evidencias_testes](https://drive.google.com/drive/folders/1JGjZH-sndG1ZcPUy0zZ9iW4hUZMRe5qc?usp=sharing).

* O passo-a-passo para execução de cada caso de teste esta dísponível em [Cadastro_passo_a_passo_execução_caso_de_testes](https://docs.google.com/document/d/1nelHOfyhvDeSziBeJ74c3qIh2a0NvcLkYMbjiEE9M7Q/edit?usp=sharing).

### Título: Exclusão de Curso

Descrição: Como administrador, quero excluir um curso na plataforma Beedoo QA Challenge para poder remover cursos desatualizados ou desnecessários.

Critérios de Aceitação:

* A lista de cursos deve ter um botão "Excluir" próximo a cada curso listado.
* Ao clicar no botão "Excluir", deve aparecer uma caixa de diálogo pedindo confirmação para excluir o curso.
* Se a exclusão for confirmada, o curso deve ser removido da lista de cursos e uma mensagem "Curso excluído com sucesso" deve ser exibida.
* Se a exclusão for cancelada, o curso não deve ser removido e a caixa de diálogo deve fechar.

Casos de Teste em Gherkin

* Os casos de teste foram escritos em Gherkin e estão disponíveis no arquivo [Casos_de_Testes_Exclusão_de_Curso](https://docs.google.com/spreadsheets/d/1h6Naz-2Gqw3Zp-Ke-nUdtrQsDuFq6QVWJcFdLhnJjQ8/edit?usp=sharing). Este arquivo inclui todos os cenários de sucesso e erro identificados para o módulo de curso.

*  As evidências dos testes estão no formato MP4 diponíveis em [Exclusao_evidencias_testes](https://drive.google.com/drive/folders/1DhZZGkWEKU6X57vjNlFpELjpGoQSjIzn?usp=sharing).

* O passo-a-passo para execução de cada caso de teste esta dísponível em [Exclusao_passo_a_passo_execução_caso_de_testes](https://docs.google.com/document/d/15BxOVWHtop44lK7349QxKgNtP41sifY-gJMIBzG5-7w/edit?usp=sharing).

### Título: Listar Cursos

Descrição: Como administrador, quero listar todos os cursos na plataforma Beedoo QA Challenge para visualizar e gerenciar os cursos existentes.

Critérios de Aceitação:

* Todos os cursos cadastrados devem ser exibidos na lista.
* Após a criação bem-sucedida, o curso deve aparecer no início da lista de cursos.
* As informações do curso devem ser exibidas corretamente, incluindo Nome do curso, Descrição do curso, instrutor, imagem de capa, data de início e fim, número de vagas, e tipo de curso (presencial/online).

Casos de Teste em Gherkin

* Os casos de teste foram escritos em Gherkin e estão disponíveis no arquivo [Casos_de_Testes_Listar_de_Curso](https://docs.google.com/spreadsheets/d/1qQVKDGRN0Pkcw4FzLFVROJJKLeWl3CPV1O8jndQ6hVs/edit?usp=sharing). Este arquivo inclui todos os cenários de sucesso e erro identificados para o módulo de curso.

*  As evidências dos testes estão no formato MP4 diponíveis em [Listar_evidencias_testes](https://drive.google.com/drive/folders/1P15KMGwj5qnqgN2Y2AtVcZlitU25iE9j?usp=sharing).

* O passo-a-passo para execução de cada caso de teste esta dísponível em [Listar_passo_a_passo_execução_caso_de_testes](https://docs.google.com/document/d/1CMm4OrhbqmLVGDWvfgPHrnGcly3_NrJ0iL6kN2gukxQ/edit?usp=sharing).

> ## Como Foram Tomadas as Decisões
> 
> Por não haver requisitos a serem seguidos, cada história de usuário foi escrita segundo pesquisas e boas práticas do desenvolvimento de software.
> 
> ### História de Usuário - Cadastro de Curso
> 1. **Pesquisa de Práticas Comuns:**
>    A decisão sobre os campos obrigatórios e os critérios de aceitação foram baseadas em uma pesquisa de plataformas de cursos online populares, como Coursera, Udemy e DIO. Essas plataformas possuem campos semelhantes, garantindo que se está alinhado com padrões de mercado.
>
> 2. **Princípios de UX:**
>    Garantir que todos os campos sejam obrigatórios e fornecer feedback imediato são práticas recomendadas em UX para evitar frustração do usuário e melhorar a experiência geral.
>
> 3. **Lógica e Validação:**
>    A restrição de que a Data de Início deve ser anterior à Data de Término é uma validação lógica necessária para garantir a consistência e integridade dos dados do curso.
> 
> ### História de Usuário - Exclusão de Curso
> 1. **Análise de Requisitos:**
>    Avaliei a funcionalidade atual do módulo de curso e identifiquei a necessidade de uma funcionalidade que permitisse a remoção de cursos desatualizados ou desnecessários.
>
> 2. **Identificação de Problemas:**
>    Realizei testes exploratórios para identificar problemas existentes na funcionalidade de exclusão de cursos, garantindo que todas as interações do usuário fossem cobertas.
>
> 3. **Foco na Experiência do Usuário:**
>    Incluir uma caixa de diálogo para confirmação de exclusão é uma prática recomendada para evitar exclusões acidentais, melhorando a experiência e a segurança do usuário.
> 
> ### História de Usuário - Listar Cursos
> 1. **Utilização de Boas Práticas:**
>    Segui boas práticas de QA para garantir a criação de histórias de usuários e casos de teste abrangentes e relevantes, alinhando a funcionalidade com padrões de mercado.
>
> 2. **Análise de Requisitos:**
>    Avaliei a necessidade de uma listagem completa e precisa dos cursos cadastrados para facilitar a gestão e visualização dos cursos pelo administrador.
>
> 3. **Foco na Experiência do Usuário:**
>    Garantir que os cursos recém-cadastrados apareçam no início da lista e que todas as informações sejam exibidas corretamente, melhorando a experiência de gerenciamento dos cursos.


## Descrição de um Bug Identificado

**Bug:** Problema ao tentar excluir um curso

**Passos para Reproduzir:**
1. Acesse a plataforma Beedoo QA Challenge.
2. Navegue até a página "Listar Cursos".
3. Clique no botão "Excluir" próximo a qualquer curso listado.

**Comportamento Observado:**
- Ao clicar no botão "Excluir", a mensagem "Curso excluído com sucesso" aparece, mas o curso não é removido da lista.
- Cada vez que o botão "Excluir" é clicado, um número de contagem vermelho aparece ao lado da mensagem, indicando o número de vezes que a exclusão foi tentada.

**Gravidade:** Alta

**Causa Provável:** O endpoint de exclusão de curso no servidor pode estar incorreto ou não implementado corretamente, ou há um problema no front-end que impede a remoção visual do curso.

**Impacto:** Os usuários não conseguem excluir cursos, o que compromete a capacidade de gerenciamento de conteúdo na plataforma e pode levar a confusão e frustração.

## Vulnerabilidades na Criação de Curso

**Vulnerabilidades Identificadas:**

1. **Ausência de Limites de Caracteres:**
   - **Descrição:** Todos os campos de texto permitem a inserção de um número ilimitado de caracteres.
   - **Impacto:** Pode causar problemas de layout, como o aumento desproporcional das caixas de texto, resultando em cursos que sobrepõem uns aos outros. Também pode afetar o desempenho do sistema.
   - **Exemplo:** Quando um nome ou descrição de curso muito longo é inserido, a "caixa" que contém o curso aumenta, levando a sobreposição com outros cursos ao lado.

2. **Validação Inadequada de Datas:**
   - **Descrição:** Permite inserir datas de início em anos anteriores ao atual e datas de término que vêm antes da data de início.
   - **Impacto:** Pode resultar em informações inválidas e cronogramas inconsistentes, causando confusão para os usuários.
   - **Exemplo:** Um curso com data de início em 2022 e data de término em 2021 pode ser salvo.

3. **Campo Número de Vagas:**
   - **Descrição:** Permite inserir valores negativos, zero ou valores excessivamente altos.
   - **Impacto:** Pode resultar em informações inválidas, afetando a gestão de inscrições e logística do curso.
   - **Exemplo:** Um curso pode ser salvo com -5 vagas ou 0 vagas.

4. **Campos Obrigatórios:**
   - **Descrição:** Permite salvar o curso sem preencher campos obrigatórios como nome do curso, descrição, instrutor, e tipo de curso.
   - **Impacto:** Pode levar a dados incompletos ou inválidos, dificultando a identificação e gestão dos cursos.
   - **Exemplo:** Um curso pode ser salvo sem nome do instrutor ou sem especificar se é online ou presencial.

5. **Campos Numéricos e Textuais:**
   - **Descrição:** Permite que campos textuais como nome do curso e descrição sejam preenchidos apenas com números ou caracteres especiais.
   - **Impacto:** Pode resultar em dados não informativos e difíceis de interpretar.
   - **Exemplo:** Um curso pode ser salvo com o nome "12345" ou "!!!@@@".

**Técnicas para Identificar Outras Potenciais Vulnerabilidades em uma Plataforma Web:**

1. **Teste de Fuzzing:** Enviar grandes quantidades de dados aleatórios, incluindo strings maliciosas, para o sistema web através dos formulários para identificar falhas. Focar especialmente em entradas como campos de texto, URLs e parâmetros de API.

2. **Análise Estática de Código:** Usar ferramentas automatizadas específicas para análise de código web, como SonarQube, para identificar vulnerabilidades como XSS (Cross-Site Scripting), SQL Injection, e outros tipos de ataques comuns em aplicações web.

3. **Revisão de Código:** Realizar revisões manuais do código, focando em áreas críticas como validação de entrada, autenticação, autorização e manipulação de dados. Procure por práticas de codificação seguras e uso correto de bibliotecas e frameworks web.

4. **Teste de Penetração (Pentest):** Simular ataques maliciosos específicos para aplicações web, como SQL Injection, XSS, CSRF (Cross-Site Request Forgery), e outras vulnerabilidades OWASP Top 10. Utilizar ferramentas como OWASP ZAP, Burp Suite, e Kali Linux para realizar esses testes.

5. **Varredura de Vulnerabilidades (Vulnerability Scanning):** Utilizar ferramentas de varredura como Nessus, OpenVAS, e Qualys para detectar vulnerabilidades conhecidas na infraestrutura web, como servidores, bancos de dados, e componentes de rede.

6. **Monitoramento de Segurança:** Implementar e monitorar logs de segurança para detectar atividades suspeitas e anômalas. Ferramentas como Splunk e ELK Stack podem ser úteis para análise de logs e detecção de intrusões.

7. **Verificação de Configurações de Segurança:** Revisar e testar as configurações de segurança do servidor web, banco de dados, e serviços de terceiros. Assegurar que as práticas recomendadas, como HTTPS, CORS (Cross-Origin Resource Sharing) corretamente configurado, e políticas de segurança de conteúdo (CSP), estejam implementadas.
