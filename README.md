# Cicero: controle de bases de dados públicas

*Síntese do projeto*

Cícero é um projeto para controle social de bases de dados públicas. 

*O que ele faz*

Na versão 1.0.0 Cícero é um bot que executa as seguintes ações:

1) Acessa a [URL](https://www.gov.br/receitafederal/pt-br/assuntos/orientacao-tributaria/cadastros/consultas/dados-publicos-cnpj) onde os dados públicos do CNPJ são disponibilizados pela Receita Federal;

2) Lê o conteúdo da página e coleta a "data da última extração" informada;

3) Verifica se a data coletada no passo anterior é inferior ou superior 30 dias;

3.1) Caso inferior, não faz nenhuma ação;

3.2) Caso superior, tuíta uma mensagem de alerta sobre isso no Twitter.

