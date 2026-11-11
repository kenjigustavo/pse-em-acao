*PSE em Ação:*
AEP — 2ª entrega | Engenharia de Software | UniCesumar | 2026

Integrantes: Filipe Ghirotto da Cruz RA:26011324-2 e Gustavo Kenji Motomura RA:26006122-2.

*Sobre o projeto:*

O PSE em Ação é um programa de terminal desenvolvido em linguagem C para apoiar o planejamento e o acompanhamento de ações coletivas do Programa Saúde na Escola (PSE). O sistema utiliza dados fictícios e coletivos, sem informações clínicas individuais de estudantes.

*Funcionalidades:*

Cadastrar ação: registra código, escola, tema, data, público-alvo, responsável e participantes previstos.
Listar ações: apresenta as ações cadastradas.
Pesquisar ações: permite consultar por código, escola ou tema.
Atualizar situação: altera a situação para Planejada, Realizada ou Cancelada e registra os participantes efetivos quando a ação é realizada.
Gerar resumo: exibe os totais por situação e o percentual de participação das ações realizadas.
Validar entradas: verifica campos obrigatórios, códigos duplicados, datas, números e limites. Esta funcionalidade atua nas operações do programa e não aparece como opção separada do menu.

*Arquivos do repositório:*

pse_em_acao.c — código-fonte do programa.
README.md — apresentação e instruções resumidas de execução.

*Requisitos:*

Computador com compilador de C compatível com C99, como o GCC disponível no Dev-C++.
Não são necessárias bibliotecas externas nem banco de dados.
Como compilar e executar no Dev-C++
Baixe o arquivo pse_em_acao.c deste repositório.
Abra o Dev-C++ e selecione Arquivo > Abrir.
Selecione pse_em_acao.c e confirme que a extensão do arquivo é .c.
Clique em Compilar e Executar (ou no comando equivalente da versão instalada).
No terminal, escolha uma opção do menu digitando o número correspondente.

*Menu do sistema:*

1 - Cadastrar ação
2 - Listar ações
3 - Pesquisar ações
4 - Atualizar situação
5 - Gerar resumo
0 - Sair

*Exemplo de uso:*

Cadastre uma ação com código 101, escola Escola Modelo, tema Alimentação saudável, data 20/11/2026 e 25 participantes previstos.
Liste ou pesquise a ação cadastrada.
Atualize a situação para Realizada e informe 20 participantes efetivos.
Gere o resumo: nesse exemplo, o percentual de participação é 80%.

*Limitações:*

Capacidade máxima de 100 ações por execução.
Os dados ficam apenas na memória: ao encerrar o programa, os registros são perdidos.
Não há interface gráfica, banco de dados, exclusão de ações ou edição geral dos campos.

*Documentação da entrega:*

O documento acadêmico final da AEP, entregue separadamente no Studeo, reúne Engenharia de Software, manual de usuário (METEP), evidências de execução e os links da apresentação em vídeo e deste repositório.
             
