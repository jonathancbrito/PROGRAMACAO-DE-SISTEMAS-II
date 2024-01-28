# PROGRAMACAO-DE-SISTEMAS-II
Material de Avaliação Prática - PROGRAMAÇÃO DE SISTEMAS II - Engenharia de Software 10/2023
#
QUESTAO

Caro(a) estudante!

Temos por certo que os desafios sempre contribuem para a aquisição de conhecimentos e competências desejadas. Assim, faz-se necessário relacionar o que se aprende com situações reais que podem ser encontradas no cotidiano. Nesta atividade, você é convidado(a) a realizar uma atividade para verificar como a disciplina em questão pode contribuir na sua experiência e formação profissional. 

Atente-se para as informações e realize um ótimo trabalho!
-----------------

Um shopping instalou uma nova atração para as crianças, uma área grande com cama elástica e outras atividades, o custo é controlado pelo tempo que a criança fica no brinquedo. Os responsáveis podem deixar a criança lá enquanto fazem compra no shopping, pois tem cuidadores especializados. Precisa-se de um sistema para fazer o cadastro, controle e a cobrança das horas utilizadas pela criança e, para isso, como desenvolvedor Java, você foi designado a criar um cadastro e controle de cobrança para este shopping.

O sistema deve ser criado utilizando Java Swing, e o processo deve conter três telas que serão executadas sequencialmente:

A Tela 1 deve armazenar dados do responsável.
A Tela 2 deve armazenar dados da criança.
A Tela 3 deve armazenar dados do tempo no brinquedo, bem como mostrar o resumo da utilização e o valor a ser cobrado.

Esse programa deve ser desenvolvido utilizando os conceitos de Orientação a Objetos, portanto deve ter as classes:

<p>- Responsável com nome, CPF, telefone, e-mail, endereço e idade.</p>
<p>- Criança com Responsável, nome, idade e sexo.</p>
<p>- Estadia com Responsável, Criança e tempo utilizado.</p>

O programa deve seguir as seguintes regras:

Para ser responsável, a pessoa tem que ser maior de idade, portanto, no cadastro de idade, é necessário verificar se a idade é igual ou superior a 18.
Para a criança poder brincar ela tem que ter menos de 10 anos, portanto, no cadastro, é necessário verificar se a idade da criança é igual ou menor que 10.
Para estadia, deve ser cobrado o valor do minuto (R$1,50); para tempo superior a 20 minutos deve conceder 5% de desconto; para mais de 40 minutos conceder 10%; e mais de 60 minutos conceder 15% de desconto.

Observações:

- Essas regras devem ser implementadas nos métodos das classes do domínio, separando assim a tela da regra de negócio.
- Os objetos cadastrados devem ser passados por parâmetros para próxima tela.

Veja a seguir o modelo proposto para criação:

![image](https://github.com/jonathancbrito/PROGRAMACAO-DE-SISTEMAS-II/assets/73788864/ba1302b1-43c4-474c-95f5-f89770547729)

![image](https://github.com/jonathancbrito/PROGRAMACAO-DE-SISTEMAS-II/assets/73788864/365fe38b-ed0f-4515-abb3-8467c8b17cd1)

![image](https://github.com/jonathancbrito/PROGRAMACAO-DE-SISTEMAS-II/assets/73788864/2c7f02ea-c890-42bd-8416-2755d9d2b181)

![image](https://github.com/jonathancbrito/PROGRAMACAO-DE-SISTEMAS-II/assets/73788864/4a06c985-034b-4fe6-838b-9531b1233ac2)

Fonte: (o autor).

Ao terminar a sua atividade, lembre-se de exportar seu projeto no formato .zip.

Para exportar no NetBeans, siga os passos: Arquivo > Exportar Projeto > Para ZIP.

ATENÇÃO: a entrega de sua atividade deve ser feita exclusivamente por meio de UM único arquivo nos formatos .zip. 
