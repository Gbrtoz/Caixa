# Exercício individual - Testes Caixa Branca (ETAPA 1)

Teste 1 - Verificação do codigo para reallizar um Teste de Caixa Branca, conforme visto teoricamente na aula.

## Erros encontrados

<ol>
    <li>A DOCUMENTAÇÃO FOI DESCRITA NO CÓDIGO?
    <p>Não há documentação.</p>
    </li>
    <li>AS VARIÁVEIS E CONSTANTES POSSUEM BOA NOMENCLATURA?
    <p>Não, as variáveis não seguem o padrão solicitado em Java (CamelCase) </p>
    </li>
    <li>EXISTEM LEGIBILIDADE E ORGANIZAÇÃO NO CÓDIGO?
    <p>Não há uma boa identação de código no projeto.</p>
    </li>
    <li>TODOS OS NULLPOINTERS FORAM TRATADOS?
    <p>Não foram fechados corretamente, Se ocorrer um erro durante a conexão uma exceção será lançada, mas o código não trata essas exceções. </p>
    </li>
    <li>A ARQUITETURA UTILIZADA FOI DEVIDAMENTE RESPEITADA?
    <p></p>
    </li>Não
    <li>AS CONEXÕES UTILIZADAS FORAM FECHADAS?
    <p>Não há fechamento nas conexões.</p>
    </li>
</ol>

# Exercício individual -  Critérios de Caixa Branca (ETAPA 2) - (Grafo de Fluxo; Complexidade Ciclomática; Base de Caminhos)

# Código:

<img src='teste.png'>

## Grafo de Fluxo

<img src='fluxo.png'>

# Complexidade Ciclomática

V(G) = 11 - 10 + 3 = 4. >>> V(G) = 3 + 1 = 4.

#  Sequencia dos Caminhos

<ol>
    <li>Entrada >>> Conectar BD >>> URL >>> Tentativa de conexão >>> FIM</li>
    <li>Entrada >>> >>> verifica user >>> Início >>>  Instrução SQL >>> Consulta >>> Verificação >>> Obter dados >>> Retorno da função >> FIM</li>
</ol>
