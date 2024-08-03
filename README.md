# DESAFIO-BEEDOO

## História de Usuário

### Título: Cadastro de Curso

Descrição: Como administrador, quero cadastrar um curso na plataforma Beedoo QA Challenge para poder oferecer aulas online ou presenciais.

Critérios de Aceitação:

* O formulário de criação de curso deve ter os campos: Nome do curso, Descrição do curso, Instrutor, URL da imagem de capa, Data de início, Data de fim, Número de vagas e Tipo de curso.
* Todos os campos são obrigatórios.
* A Data de Início deve ser anterior à Data de Término.
* Após a criação bem-sucedida, deve aparecer uma mensagem "curso cadastrado com sucesso" e o curso deve ser listado na página listar cursos.

 Casos de Teste em Gherkin

* Os casos de teste foram escritos em Gherkin e estão disponíveis no arquivo [Casos_de_Testes_Cadastro_de_Cursos]([gherkin/test_cases.feature](https://docs.google.com/spreadsheets/d/1WVsvQlN5Ayz0i4YyX3plAKyk3aG8yjqyn_LRLnXQLEI/edit?usp=sharing)). Este arquivo inclui todos os cenários de sucesso e erro identificados para o módulo de curso.

*  As evidências dos testes estão no formato MP4 diponíveis em [Evidencias_testes_cadastro_cursos](https://drive.google.com/drive/folders/1JGjZH-sndG1ZcPUy0zZ9iW4hUZMRe5qc?usp=sharing).

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

*  As evidências dos testes estão no formato MP4 diponíveis em [Evidencias_testes_exclusao_cursos]().

* O passo-a-passo para execução de cada caso de teste esta dísponível em [Exclusao_passo_a_passo_execução_caso_de_testes](https://docs.google.com/document/d/15BxOVWHtop44lK7349QxKgNtP41sifY-gJMIBzG5-7w/edit?usp=sharing).





> ## Como Foram Tomadas as Decisões
> Por não haver requisitos a serem seguidos, cada História de usuário foi escrita segundo pesquisas e boas práticas do desenvolvimento de software.
>
> ## História de usuário - Cadastro de Curso
> 1. **Pesquisa de Práticas Comuns:**
>    A decisão sobre os campos obrigatórios e os critérios de aceitação foram baseadas em uma pesquisa de plataformas de cursos online populares, como Coursera, Udemy e DIO. Essas plataformas possuem campos semelhantes, garantindo que se está alinhado com padrões de mercado.
>
> 2. **Princípios de UX:**
>    Garantir que todos os campos sejam obrigatórios e fornecer feedback imediato são práticas recomendadas em UX para evitar frustração do usuário e melhorar a experiência geral.
>
> 3. **Lógica e Validação:**
>    A restrição de que a Data de Início deve ser anterior à Data de Término é uma validação lógica necessária para garantir a consistência e integridade dos dados do curso.
