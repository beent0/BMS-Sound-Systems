# BMS Sound Systems
A MySQL Workbench project example for a Festival Sound Systems company

TO-DO after feedback
- [ ] Sem pastas
- [ ] Nome dos ficheiros
- [ ] Screenshot do diagrama
- [x] Tem q ser |1 Consumiveis:LinhaConsumivel M0
- [x] Obrigarotiedade do |Tecnico-Serviço0
- [x] Obrigatoriedade |IVA - Resto0
- [x] Equipamento não pode ter stock
- [x] Tirar Quantidade Fornecida da LinhaConsumivel
- [x] Tirar Keys do IVA
- [x] Duraçao do trabalhador ServiçoTecnico
- [ ] Contrato = aluger Equi?
- [x] Tecnico só com horas
- [ ] Aluguer ao dia
- [ ] Datas na linha equipamento != datas contrato
- [x] Tipo de tecnico + preço desse tipo Nova Tabela ligada aos técnicos
- [ ] Verificar se FK Tecnico - TipoTecnico estão corretas
- [ ] Confirmar multiplicidade relatorio - diagrama
- [ ] Valor do iva na fatura (E se o IVA mudar?)

TO-DO Entrega Final

- [ ] Criar os dados
- [ ] Carregar os dados para a base de dados
- [ ] Ver Operações de Aluger, Devolução, Manutenção, Faturação, e restantes operações
- [ ] Operações de **Alteração, Eliminação e Inserção**
- [ ] Pelo menos **10 Querries** interessantes e adequadas ao domínio do trabalho respetivas descrições textuais e objetivos e pelo menos três vistas que possam ser utilizadas por aplicações do sistema de informação. 
- [ ] O relatório deve incluir o objetivo das consultas/operações, descritos com precisão, assim como os resultados para os dados criados (incluindo as vistas/views)


A base de dados deve ser carregada com dados criados criteriosamente pelo grupo, que permitam testar e validar operações de aluguer, devolução, manutenção, faturação e restantes operações implementadas nos capítulos seguintes.
É avaliada a coerência e adequação do esquema relacional, a normalização das entidades criadas, a utilização de entidades associativas, assim como as multiplicidades e obrigatoriedades dos relacionamentos. Avalia-se, ainda, a implementação das restrições de
integridade e os domínios dos atributos implementados.



3. Consultas e vistas
    O trabalho deverá contemplar, para além de consultas sobre a base de dados,
    operações de alteração, eliminação e inserção de dados que façam sentido no
    contexto do negócio imaginado
    Deverão incluir, pelo menos, dez queries em SQL, interessantes e adequadas ao
    domínio do trabalho, com a as respetivas descrições textuais e objetivos e pelo menos
    três vistas que possam ser utilizadas por aplicações do sistema de informação.
    O relatório deve incluir o objetivo das consultas/operações, descritos com precisão,
    assim como os resultados para os dados criados (incluindo as vistas/views). Inclua
    também o código SQL (em separado).
    Inclua nas vistas e/ou queries o código para obter os seguintes resultados:
        1. Apresente os dados necessários para obter o total do orçamento de um
        aluguer+serviço (incluído nos dados inseridos na BD) com a duração de 2,5
        unidades de faturação (por exemplo 2,5 dias ou outro período de faturação previsto
        no serviço escolhido) e que inclua 2 consumíveis distintos com, respetivamente, 1
        unidade e 2 unidades.
        2. Calcule quais os clientes que tiveram os 3 valores mais altos de faturação nos
        últimos 12 meses (nome, morada e valor total de faturação no período).
        3. Determinar qual o técnico com maior número de unidades de serviço (dias, horas
        ou outro período de faturação previsto no serviço escolhido) durante o mês anterior
        ao corrente.
        As consultas e vistas são avaliadas em termos do grau de interesse/adequação para o
        negócio, complexidade, eficácia, rigor no código e otimização.
        (10,0 val.)



4. Gatilhos / Triggers
    Os triggers podem usar vistas criadas no ponto anterior. Inclua o código SQL no
    relatório. Deve incluir dois, um dos quais para obter o seguinte resultado:
        - Despoletar um aviso caso o número total de unidades de serviço a faturar por
        um pedido seja inferior a determinado valor, por exemplo 1 dia (mas podem
        estabelecer outro valor e unidade).
        Os triggers são avaliados em termos de correção do código, complexidade, otimização e
        utilidade dos resultados no contexto do negócio.
    (1,5 val.)



5. Conclusões, dados e instruções de utilização
    Inclua nesta secção uma discussão de limitações/opções tomadas para a
    implementação do trabalho.
    Inclua ainda um pequeno manual de utilização (instruções), que explique como usar
    a base de dados (criar, inserir os dados previamente preparados, …). Esse manual
    deverá incluir indicação de sequências de passos/operações que demonstre o
    funcionamento básico da base de dados e do código, bem como outras
    funcionalidades que os alunos achem relevantes para a avaliação.
    Neste capítulo será avaliada a relevância dos dados de teste, o grau de conhecimento sobre as
    limitações do modelo de dados implementado e da concretização em SQL da base de dados.
    O manual é avaliado pela funcionalidade e abrangência.
    (1,0 val.)



Apresentação escrita do trabalho
    O relatório final de projeto deve conter as secções 1 a 5 atrás descritas de forma
    sucinta, não ultrapassando um total de 20 páginas. As listagens com o código de
    criação da BD, código das questões (queries) e gatilhos e respetivos outputs devem
    ser colocadas em anexos, bem como outra informação acessória que considerarem
    necessário incluir.
    Avalia-se a organização do relatório, correção e utilização da linguagem escrita e o grau de
    conhecimento dos assuntos demonstrado.
    (3,5 val.)



Apresentação oral do trabalho
    Os grupos defendem os seus trabalhos perante a docente, apresentando as queries,
    vistas e triggers a funcionar e respondendo às questões da docente. É obrigatória a
    participação na apresentação oral. A avaliação da participação de cada estudante
    na(s) apresentação(ões) constitui o fator de ponderação da nota do estudante no
    trabalho documentado.