
# Vitor_Emanuel

---

- [Vitor\_Emanuel](#vitor_emanuel)
- [1. Introdução](#1-introdução)
- [2. Descrições do negócio](#2-descrições-do-negócio)
  - [2.1 Descrição do negócio](#21-descrição-do-negócio)
  - [2.2 Requisitos do Sistema](#22-requisitos-do-sistema)
    - [2.2.1 Requisitos Funcionais](#221-requisitos-funcionais)
    - [2.2.2 Requisitos não funcionais](#222-requisitos-não-funcionais)
- [3. Visão geral do sistema](#3-visão-geral-do-sistema)
  - [3.1. Descrição do sistema do ponto de vista do usuário final](#31-descrição-do-sistema-do-ponto-de-vista-do-usuário-final)
- [4. Diagrama ER](#4-diagrama-er)
- [5. Diagrama de classes](#5-diagrama-de-classes)
- [6. Casos de uso](#6-casos-de-uso)
  - [6.1 Diagrama de Casos de Uso](#61-diagrama-de-casos-de-uso)
  - [6.2 Histórias de Usuário - Clínica Veterinária](#62-histórias-de-usuário---clínica-veterinária)
    - [1. Cadastro de Animais Permitidos](#1-cadastro-de-animais-permitidos)
    - [2. Cadastro de Clientes e Animais](#2-cadastro-de-clientes-e-animais)
    - [3. Informar Condições de Chegada do Animal](#3-informar-condições-de-chegada-do-animal)
    - [4. Informar Tipo de Ração](#4-informar-tipo-de-ração)
    - [5. Informar Hábitos do Animal](#5-informar-hábitos-do-animal)
    - [6. Atendimento por Múltiplos Veterinários](#6-atendimento-por-múltiplos-veterinários)
    - [7. Atendimentos Agendados](#7-atendimentos-agendados)
    - [8. Ficha e Prontuário do Animal](#8-ficha-e-prontuário-do-animal)
    - [9. Marcação de Horários Futuros](#9-marcação-de-horários-futuros)
    - [10. Receita Gerada Após Atendimento](#10-receita-gerada-após-atendimento)
    - [12.2. Atendimento por Atendente](#122-atendimento-por-atendente)
    - [13. Verificação de Disponibilidade na Agenda](#13-verificação-de-disponibilidade-na-agenda)
    - [14. Inserção em Fila de Espera](#14-inserção-em-fila-de-espera)
    - [15. Encaminhamento para o Veterinário](#15-encaminhamento-para-o-veterinário)
    - [16. Entrevista com o Dono do Animal](#16-entrevista-com-o-dono-do-animal)
    - [17. Formulário de Entrevista](#17-formulário-de-entrevista)
    - [17. Exame do Animal e Observações](#17-exame-do-animal-e-observações)
    - [18. Emissão de Receita](#18-emissão-de-receita)
    - [19. Solicitação de Exames Complementares](#19-solicitação-de-exames-complementares)
    - [20. Agendamento de Horário](#20-agendamento-de-horário)
    - [21. Cancelamento ou Remarcação de Consulta](#21-cancelamento-ou-remarcação-de-consulta)
    - [22. Registro de Alergias ou Restrições Alimentares](#22-registro-de-alergias-ou-restrições-alimentares)
    - [23. Solicitação de Vacinação](#23-solicitação-de-vacinação)
    - [24. Programa de Fidelidade](#24-programa-de-fidelidade)
    - [25. Identificação de Animais com RFID](#25-identificação-de-animais-com-rfid)
    - [26. Serviços de Banho e Tosa](#26-serviços-de-banho-e-tosa)
    - [27. Venda de Rações e Medicamentos](#27-venda-de-rações-e-medicamentos)
    - [28. Controle de Estoque de Medicamentos](#28-controle-de-estoque-de-medicamentos)
    - [29. Histórico de Atendimento e Exames](#29-histórico-de-atendimento-e-exames)
    - [30. Parcerias com Pet Shops e Laboratórios](#30-parcerias-com-pet-shops-e-laboratórios)
- [7. Diagrama de componentes](#7-diagrama-de-componentes)
- [8. Diagrama de implantação](#8-diagrama-de-implantação)
- [9. Diagrama C4](#9-diagrama-c4)
  - [9.1 Diagrama de Contexto](#91-diagrama-de-contexto)
  - [9.2 Diagrama de Container](#92-diagrama-de-container)
  - [9.3 Diagrama de Componente](#93-diagrama-de-componente)
  - [9.4 Diagrama de Código](#94-diagrama-de-código)
- [10. Protótipo de telas](#10-protótipo-de-telas)
  - [10.1. Tela Menu](#101-tela-menu)
  - [10.2. Telas de Cadastro](#102-telas-de-cadastro)
    - [10.2.1 Cadastro de Agenda](#1021-cadastro-de-agenda)
    - [10.2.2 Cadastro de Animal](#1022-cadastro-de-animal)
    - [10.2.3 Cadastro de Atendente](#1023-cadastro-de-atendente)
    - [10.2.4 Cadastro de Atendimento](#1024-cadastro-de-atendimento)
    - [10.2.5 Cadastro de Cliente](#1025-cadastro-de-cliente)
    - [10.2.6 Cadastro de Exame](#1026-cadastro-de-exame)
    - [10.2.7 Cadastro de Ficha](#1027-cadastro-de-ficha)
    - [10.2.8 Cadastro de Parceria](#1028-cadastro-de-parceria)
    - [10.2.9 Cadastro de Produto](#1029-cadastro-de-produto)
    - [10.2.10 Cadastro de Servico](#10210-cadastro-de-servico)
    - [10.2.11 Cadastro de Vacina](#10211-cadastro-de-vacina)
    - [10.2.12 Cadastro de Venda](#10212-cadastro-de-venda)
    - [10.2.13 Cadastro de Veterinario](#10213-cadastro-de-veterinario)
  - [10.3 Telas de Gráficos](#103-telas-de-gráficos)
    - [10.3.1 Gráfico de Estoque](#1031-gráfico-de-estoque)
    - [10.3.1 Gráfico de Vendas](#1031-gráfico-de-vendas)
  - [10.4 Tela de Dashboard](#104-tela-de-dashboard)
- [11. Diagrama de navegação de telas](#11-diagrama-de-navegação-de-telas)
- [12. Pilha tecnológica](#12-pilha-tecnológica)
  - [12.1. Gráfico da Pilha](#121-gráfico-da-pilha)
  - [12.2. Detalhamento das Camadas da Pilha](#122-detalhamento-das-camadas-da-pilha)
    - [12.2.1 **Linux** (Sistema Operacional):](#1221-linux-sistema-operacional)
    - [12.2.2. **Apache (Servidor Web)**:](#1222-apache-servidor-web)
    - [12.2.3. **Back-End (PHP - ScriptCase)**:](#1223-back-end-php---scriptcase)
    - [12.2.4. **Banco de Dados (MySQL)**:](#1224-banco-de-dados-mysql)
    - [12.2.5. **Front-End (HTML, CSS, Bootstrap, JavaScript)**:](#1225-front-end-html-css-bootstrap-javascript)
- [13. Requisitos de sistemas](#13-requisitos-de-sistemas)
  - [13.1. Requisitos do Lado Cliente](#131-requisitos-do-lado-cliente)
    - [13.1.1. Dispositivos:](#1311-dispositivos)
    - [13.1.2. Navegadores Web:](#1312-navegadores-web)
    - [13.1.3. Interface de Usuário:](#1313-interface-de-usuário)
    - [13.1.4. Autenticação:](#1314-autenticação)
    - [13.1.5. Funcionalidades Disponíveis:](#1315-funcionalidades-disponíveis)
  - [13.2. Requisitos do Lado Servidor](#132-requisitos-do-lado-servidor)
    - [13.2.1. Servidor de Aplicação:](#1321-servidor-de-aplicação)
    - [13.2.2. Servidor de Banco de Dados:](#1322-servidor-de-banco-de-dados)
    - [13.2.3. Servidor Web:](#1323-servidor-web)
    - [13.2.4. API REST:](#1324-api-rest)
    - [13.2.5. Funcionalidades do Servidor:](#1325-funcionalidades-do-servidor)
- [14. Considerações sobre segurança](#14-considerações-sobre-segurança)
  - [14.1. Lado Cliente](#141-lado-cliente)
    - [Regras de Senha](#regras-de-senha)
    - [Política de Segurança](#política-de-segurança)
  - [14.2. Lado Servidor](#142-lado-servidor)
    - [Sistema Operacional](#sistema-operacional)
    - [Política de Backup](#política-de-backup)
    - [Políticas de Acesso e Privacidade](#políticas-de-acesso-e-privacidade)
    - [Medidas de Segurança Adicionais](#medidas-de-segurança-adicionais)
- [15. Instalação, Manutenção e Novas Funcionalidades](#15-instalação-manutenção-e-novas-funcionalidades)
  - [15.1. Instalação](#151-instalação)
  - [15.2. Manutenção](#152-manutenção)
  - [15.3. Novas Funcionalidades](#153-novas-funcionalidades)
- [16. Treinamento](#16-treinamento)
  - [16.1. Treinamento dos Usuários](#161-treinamento-dos-usuários)
  - [16.2. Treinamento do Administrador do Sistema](#162-treinamento-do-administrador-do-sistema)
- [17. Script SQL](#17-script-sql)
  - [17.1 Script para criar as tabelas](#171-script-para-criar-as-tabelas)
  - [17.2 Scrip para inserir dados fictícios](#172-scrip-para-inserir-dados-fictícios)


# 1. Introdução

[(voltar ao início)](#vitor_emanuel)

O projeto a seguir apresenta um sistema desenvolvido para uma petshop. A empresa é considerada uma microempresa e iniciou as atividades recentemente. Ao possuir serviços exclusivos, os sistemas presentes no mercado não se enquadra, desta forma, os proprietários decidiram desenvolver uma solução própria. Esta solução é detalhada a seguir

---

# 2. Descrições do negócio

[(voltar ao início)](#vitor_emanuel)
## 2.1 Descrição do negócio

Descrição do cenário onde o sistema deverá funcionar:
1. Uma clínica veterinária atende apenas os animais: gatos e cachorros.
2. Os clientes devem fazer um cadastro de si e dos animais.
3. Os clientes devem informar as condições nas quais os animais chegam.
4. Os clientes devem informar o tipo de ração que o animal come.
5. O cliente deve informar hábitos do animal.
6. Para cada animal é possível que mais de um veterinário o atenda.
7. Os animais podem chegar e serem atendidos de acordo com uma agenda do dia.
8. Cada animal atendido receberá uma ficha e um prontuário.
9.  Outros dono podem querer marcar horários de atendimento futuro.
10. O atendimento gera uma receita para o animal.
11. Quando um cliente chega na clínica veterinária ele é atendido por um atendente.
12. O atendente deve verificar se existe agenda disponível com um veterinário.
13. O atendente deve colocar o cliente e seu animal na fila de espera, se for o caso.
14. O atendente deve levar o cliente e o animal até o veterinário.
15. O veterinário deve realizar uma entrevista com o dono do animal.
16. O resultado da entrevista deve ir para um formulário.
17. O veterinário deverá examinar o animal e anotar em prontuário(ficha) suas observações.
18. Dependendo da situação do animal este receberá uma receita.
19. Dependendo da situação do animal, o veterinário pode solicitar exames complementares, como exames de sangue e radiografias. Esses exames devem ser registrados no prontuário do animal e uma agenda específica para exames deve ser gerenciada.
20. O cliente pode solicitar o agendamento de horário.
21. Um cliente pode desejar cancelar ou remarcar uma consulta previamente agendada. O sistema deve permitir que o atendente faça essa alteração na agenda.
22. A ficha do animal deve conter alergias ou restrições alimentares que o animal possa ter, garantindo que o veterinário tenha essas informações no momento da consulta.
23. O cliente pode solicitar a vacinação de seu pet.
24. A clínica avisa os clientes quando um animal estiver próximo do prazo para tomar uma vacina de reforço ou realizar algum procedimento periódico.
25. A petshop pode marcar os animais com RFID.
26. A petshop oferece serviços de banho e tosa.
27. A petshop vende rações e medicamentos para cães e gatos.
28. A petshop controla o estoque de medicamentos e rações usados na clínica. Quando o veterinário prescreve um medicamento ou ração especial, isso deve ser registrado e o estoque atualizado automaticamente.
29. Cada animal deve ter um histórico detalhado de todas as consultas, exames, receitas e tratamentos realizados, com a possibilidade de o cliente acessar essas informações, se autorizado.
30. Novos veterinários ou funcionários da clínica podem ser cadastrados, associando as especialidades e funções de cada um para facilitar o agendamento e a triagem de casos.

## 2.2 Requisitos do Sistema
### 2.2.1 Requisitos Funcionais
```mermaid
classDiagram
class RequisitosFuncionais {
    - RF01: Cadastro de Clientes e Animais
    - RF02: Registro das Condições do Animal
    - RF03: Registro de Tipo de Ração e Hábitos do Animal
    - RF04: Gerenciamento de Agenda Diária de Atendimentos
    - RF05: Criação de Ficha e Prontuário para cada Animal
    - RF06: Agendamento de Consultas Futuras
    - RF07: Geração de Receita após Atendimento
    - RF08: Verificação e Controle de Agenda pelo Atendente
    - RF09: Gerenciamento da Fila de Espera
    - RF10: Realização de Entrevista e Registro em Formulário
    - RF11: Registro de Observações e Exames no Prontuário
    - RF12: Solicitação de Exames Complementares e Agenda para Exames
    - RF13: Agendamento de Consultas e Exames pelo Cliente
    - RF14: Cancelamento ou Remarcação de Consultas pelo Atendente
    - RF15: Registro de Alergias ou Restrições Alimentares
    - RF16: Agendamento e Controle de Vacinação
    - RF17: Marcação de Animais com RFID
    - RF18: Serviços de Banho e Tosa
    - RF19: Venda de Rações e Medicamentos
    - RF20: Controle de Estoque de Medicamentos e Rações
    - RF21: Histórico Detalhado de Atendimentos e Acesso pelo Cliente
    - RF22: Cadastro de Veterinários e Funcionários com Especialidades
}
```

### 2.2.2 Requisitos não funcionais
```mermaid
classDiagram
class RequisitosNaoFuncionais {
    - RNF01: Segurança e Privacidade dos Dados do Cliente e Animal
    - RNF02: Interface Intuitiva e de Fácil Navegação
    - RNF03: Compatibilidade com Dispositivos Móveis
    - RNF04: Sistema de Notificação Automática para Vacinação e Procedimentos
    - RNF05: Atualização Automática do Estoque após Prescrição
    - RNF06: Alta Disponibilidade e Desempenho do Sistema
    - RNF07: Capacidade de Escalabilidade para Suporte a Múltiplas Clínicas
    - RNF08: Acesso Restrito por Níveis de Permissão para Funcionários
    - RNF09: Conformidade com Regulamentações de Saúde Animal
    - RNF10: Backup e Recuperação de Dados Automatizados
}
```

---

# 3. Visão geral do sistema

[(voltar ao início)](#vitor_emanuel)

O sistema desenvolvido para a clínica veterinária tem como objetivo otimizar e gerenciar o atendimento aos animais de forma eficiente, proporcionando uma experiência fluida tanto para os usuários quanto para os atendentes. 

## 3.1. Descrição do sistema do ponto de vista do usuário final

Para o usuário final, que pode ser um atendente, veterinário ou cliente, o sistema oferece uma interface amigável e intuitiva. As principais funcionalidades incluem:

- **Cadastro de Clientes e Animais**: Usuários podem cadastrar facilmente informações sobre clientes e seus animais, garantindo que todos os dados necessários estejam acessíveis durante o atendimento.
  
- **Agendamento de Consultas e Exames**: O sistema permite que os usuários agendem consultas e exames com veterinários, garantindo que as informações de disponibilidade estejam sempre atualizadas.

- **Gerenciamento de Atendimento**: Os atendentes podem registrar o histórico de atendimentos, emitir receitas e gerenciar fichas médicas de cada animal, facilitando o acompanhamento do tratamento.

- **Notificações e Lembretes**: O sistema envia notificações automáticas aos clientes sobre vacinas e procedimentos, melhorando a comunicação e o cuidado com os animais.

- **Relatórios e Análises**: Usuários têm acesso a relatórios de vendas, estoque e gráficos que ajudam a visualizar o desempenho da clínica e a tomar decisões informadas.

- **Segurança e Acesso**: A autenticação é simples e segura, garantindo que apenas usuários autorizados tenham acesso às informações sensíveis.

Em resumo, o sistema proporciona uma solução integrada que melhora a eficiência operacional da clínica veterinária, garante a segurança dos dados e oferece um atendimento de qualidade aos clientes e seus animais.

---

# 4. Diagrama ER

[(voltar ao início)](#vitor_emanuel)

```mermaid
erDiagram
    CLIENTE {
        int id_cliente
        string nome
        string endereco
        string telefone
        string email
    }
    
    ANIMAL {
        int id_animal
        string nome
        string tipo
        string condicao
        string habitos
        string tipo_racao
        string alergias
    }
    
    VETERINARIO {
        int id_veterinario
        string nome
        string especialidade
    }
    
    ATENDENTE {
        int id_atendente
        string nome
    }

    FICHA {
        int id_ficha
        string observacoes
        string receita
    }

    EXAME {
        int id_exame
        string tipo
        string resultado
        date data_exame
    }

    AGENDA {
        int id_agenda
        date data_consulta
        time hora_consulta
        boolean disponivel
    }

    VACINA {
        int id_vacina
        string tipo
        string fabricante
    }
    
    PRODUTO {
        int id_produto
        string nome
        string categoria
        int estoque
    }

    CLIENTE ||--o{ ANIMAL : "possui"
    ANIMAL ||--o{ FICHA : "tem"
    ANIMAL ||--o{ VACINA : "pode_receber"
    ANIMAL ||--o{ EXAME : "pode_realizar"
    ANIMAL ||--o{ AGENDA : "marcado_em"
    ANIMAL ||--o{ PRODUTO : "consome"
    FICHA ||--o{ EXAME : "relaciona_com"
    AGENDA ||--o{ VETERINARIO : "atende_por"
    AGENDA ||--o{ ATENDENTE : "agendado_por"
    VETERINARIO ||--o{ EXAME : "solicita"
    CLIENTE ||--o{ AGENDA : "pode_remarcar"
    PRODUTO ||--o{ ANIMAL : "usado_para"
    CLIENTE ||--o{ PRODUTO : "compra"
    VETERINARIO ||--o{ FICHA : "preenche"
    AGENDA ||--o{ ANIMAL : "para"
```
---

# 5. Diagrama de classes

[(voltar ao início)](#vitor_emanuel)

```mermaid
classDiagram
    class Cliente {
        +int id_cliente
        +string nome
        +string endereco
        +string telefone
        +string email
        +cadastrarAnimal(Animal animal)
        +marcarConsulta(Animal animal, Agenda agenda)
        +remarcarConsulta(Agenda agenda)
        +cancelarConsulta(Agenda agenda)
        +comprarProduto(Produto produto)
    }

    class Animal {
        +int id_animal
        +string nome
        +string tipo
        +string condicao
        +string habitos
        +string tipo_racao
        +string alergias
        +Ficha ficha
        +historicoAtendimentos : List~Atendimento~
        +adicionarHistorico(Atendimento atendimento)
    }

    class Veterinario {
        +int id_veterinario
        +string nome
        +string especialidade
        +realizarConsulta(Animal animal, Cliente cliente)
        +prescreverReceita(Animal animal, string receita)
        +solicitarExame(Animal animal, string tipoExame)
    }

    class Atendente {
        +int id_atendente
        +string nome
        +agendarConsulta(Cliente cliente, Animal animal, Agenda agenda)
        +remarcarConsulta(Cliente cliente, Agenda agenda)
        +cancelarConsulta(Cliente cliente, Agenda agenda)
        +adicionarAEspera(Cliente cliente, Animal animal)
    }

    class Ficha {
        +int id_ficha
        +string observacoes
        +string receita
        +registrarExame(Exame exame)
        +atualizarFicha(string observacao)
    }

    class Exame {
        +int id_exame
        +string tipo
        +string resultado
        +date dataExame
    }

    class Agenda {
        +int id_agenda
        +date data_consulta
        +time hora_consulta
        +bool disponivel
        +marcarHorario(Cliente cliente, Animal animal)
        +verificarDisponibilidade() : bool
    }

    class Produto {
        +int id_produto
        +string nome
        +string categoria
        +int estoque
        +vender(Cliente cliente)
        +atualizarEstoque(int quantidade)
    }

    class Vacina {
        +int id_vacina
        +string tipo
        +string fabricante
        +vacinarAnimal(Animal animal)
    }

    class Atendimento {
        +int id_atendimento
        +date data_atendimento
        +Veterinario veterinario
        +registrarAtendimento(Animal animal, Cliente cliente)
    }

    Cliente "1" --> "*" Animal : "possui"
    Animal "1" --> "*" Ficha : "tem"
    Animal "1" --> "*" Atendimento : "histórico"
    Animal "1" --> "*" Exame : "pode realizar"
    Animal "1" --> "*" Vacina : "pode receber"
    Atendimento "*" --> "1" Veterinario : "realizado por"
    Agenda "*" --> "1" Veterinario : "agendado com"
    Agenda "*" --> "1" Atendente : "agendado por"
    Exame "*" --> "1" Ficha : "registrado em"
    Produto "*" --> "1" Animal : "usado por"
    Produto "*" --> "1" Cliente : "comprado por"
    Cliente "1" --> "*" Agenda : "agenda"
    Veterinario "*" --> "*" Ficha : "preenche"
```
---

# 6. Casos de uso

[(voltar ao início)](#vitor_emanuel)

## 6.1 Diagrama de Casos de Uso
![Figura 1: Diagrama de casos de uso](https://github.com/VitorSauzen/vitor_emanuel/blob/main/src/images/diagrama_casos_uso.png)

## 6.2 Histórias de Usuário - Clínica Veterinária
:bulb: **Dica** Situações de utilização  

### 1. Cadastro de Animais Permitidos
```
**Como** uma clínica veterinária,  
**Eu quero** atender apenas gatos e cachorros,  
**Para** garantir que os serviços oferecidos sejam especializados para esses tipos de animais.
```

### 2. Cadastro de Clientes e Animais
```
**Como** cliente,  
**Eu quero** fazer o cadastro de meus dados pessoais e dos meus animais,  
**Para** poder agendar consultas e utilizar os serviços da clínica.
```

### 3. Informar Condições de Chegada do Animal
```
**Como** cliente,  
**Eu quero** informar as condições em que meu animal chegou à clínica,  
**Para** que o veterinário saiba como o animal estava ao chegar.
```

### 4. Informar Tipo de Ração
```
**Como** cliente,  
**Eu quero** informar o tipo de ração que meu animal consome,  
**Para** garantir que o veterinário tenha essa informação no histórico do animal.
```

### 5. Informar Hábitos do Animal
```
**Como** cliente,  
**Eu quero** informar os hábitos do meu animal,  
**Para** que o veterinário tenha uma visão completa do comportamento do pet.
```

### 6. Atendimento por Múltiplos Veterinários
```
**Como** administrador da clínica,  
**Eu quero** que um animal possa ser atendido por mais de um veterinário,  
**Para** garantir uma avaliação completa do estado de saúde do pet.
```

### 7. Atendimentos Agendados
```
**Como** administrador da clínica,  
**Eu quero** organizar os atendimentos de acordo com a agenda do dia,  
**Para** garantir uma gestão eficiente do tempo e evitar superlotação.
```

### 8. Ficha e Prontuário do Animal
```
**Como** veterinário,  
**Eu quero** criar uma ficha e um prontuário para cada animal atendido,  
**Para** registrar o histórico médico e de saúde do animal.
```

### 9. Marcação de Horários Futuros
```
**Como** cliente,  
**Eu quero** marcar horários futuros de atendimento para meu animal,  
**Para** garantir que ele seja atendido na data e horário mais convenientes.
```

### 10. Receita Gerada Após Atendimento
```
**Como** veterinário,  
**Eu quero** emitir uma receita para o animal após o atendimento,  
**Para** prescrever medicamentos ou tratamentos necessários.
```

### 12.2. Atendimento por Atendente
```
**Como** cliente,  
**Eu quero** ser recebido por um atendente ao chegar à clínica,  
**Para** ser orientado sobre o processo de consulta e atendimento.
```

### 13. Verificação de Disponibilidade na Agenda
```
**Como** atendente,  
**Eu quero** verificar se há vagas disponíveis na agenda dos veterinários,  
**Para** encaixar novos atendimentos.
```

### 14. Inserção em Fila de Espera
```
**Como** atendente,  
**Eu quero** colocar clientes e seus animais na fila de espera,  
**Para** organizar os atendimentos de acordo com a disponibilidade dos veterinários.
```

### 15. Encaminhamento para o Veterinário
```
**Como** atendente,  
**Eu quero** acompanhar o cliente e seu animal até o veterinário,  
**Para** garantir que o processo de atendimento seja fluido e organizado.
```

### 16. Entrevista com o Dono do Animal
```
**Como** veterinário,  
**Eu quero** realizar uma entrevista com o dono do animal,  
**Para** coletar informações importantes sobre o pet antes de iniciar o exame.
```

### 17. Formulário de Entrevista
```
**Como** veterinário,  
**Eu quero** registrar as informações da entrevista em um formulário,  
**Para** documentar as respostas e usá-las no diagnóstico.
```

### 17. Exame do Animal e Observações
```
**Como** veterinário,  
**Eu quero** examinar o animal e anotar as observações no prontuário,  
**Para** ter um registro claro das condições de saúde do pet.
```

### 18. Emissão de Receita
```
**Como** veterinário,  
**Eu quero** emitir uma receita após o atendimento,  
**Para** prescrever os medicamentos ou tratamentos adequados para o animal.
```

### 19. Solicitação de Exames Complementares
```
**Como** veterinário,  
**Eu quero** solicitar exames complementares, como exames de sangue e radiografias,  
**Para** ter um diagnóstico mais detalhado da condição do animal.
```

### 20. Agendamento de Horário
```
**Como** cliente,  
**Eu quero** agendar horários respeitando a disponibilidade dos veterinários,  
**Para** garantir que meu pet seja atendido no momento ideal.
```

### 21. Cancelamento ou Remarcação de Consulta
```
**Como** cliente,  
**Eu quero** cancelar ou remarcar uma consulta previamente agendada,  
**Para** ajustar o horário da consulta às minhas necessidades.
```

### 22. Registro de Alergias ou Restrições Alimentares
```
**Como** veterinário,  
**Eu quero** registrar alergias e restrições alimentares na ficha do animal,  
**Para** evitar complicações durante o atendimento.
```

### 23. Solicitação de Vacinação
```
**Como** cliente,  
**Eu quero** solicitar a vacinação do meu animal,  
**Para** garantir que ele receba as vacinas necessárias para sua saúde.
```

### 24. Programa de Fidelidade
```
**Como** cliente frequente,  
**Eu quero** participar de um programa de fidelidade,  
**Para** obter descontos em consultas e vacinas.
```

### 25. Identificação de Animais com RFID
```
**Como** pet shop,  
**Eu quero** marcar os animais com RFID,  
**Para** facilitar o controle de identificação e serviços prestados.
```

### 26. Serviços de Banho e Tosa
```
**Como** cliente,  
**Eu quero** agendar serviços de banho e tosa para o meu animal,  
**Para** manter a higiene e aparência do meu pet.
```

### 27. Venda de Rações e Medicamentos
```
**Como** pet shop,  
**Eu quero** vender rações e medicamentos específicos para cães e gatos,  
**Para** oferecer uma solução completa de saúde e alimentação.
```

### 28. Controle de Estoque de Medicamentos
```
**Como** administrador da clínica,  
**Eu quero** registrar a prescrição de medicamentos no sistema,  
**Para** controlar o estoque disponível de forma eficiente.
```

### 29. Histórico de Atendimento e Exames
```
**Como** veterinário,  
**Eu quero** manter um histórico atualizado dos atendimentos e exames do animal,  
**Para** garantir que todas as informações estejam disponíveis nas consultas futuras.
```

### 30. Parcerias com Pet Shops e Laboratórios
```
**Como** administrador da clínica,  
**Eu quero** estabelecer parcerias com pet shops e laboratórios,  
**Para** facilitar o acesso dos clientes a produtos e exames complementares.
```

---

# 7. Diagrama de componentes

[(voltar ao início)](#vitor_emanuel)

![Figura : Diagrama de Componentes](https://github.com/VitorSauzen/vitor_emanuel/blob/main/src/images/diagrama_componente.png)

---

# 8. Diagrama de implantação

[(voltar ao início)](#vitor_emanuel)

![Figura : Diagrama de Implantação](https://github.com/VitorSauzen/vitor_emanuel/blob/main/src/images/diagrama_implantacao.png)

---

# 9. Diagrama C4
[(voltar ao início)](#vitor_emanuel)

## 9.1 Diagrama de Contexto
```mermaid
flowchart TB
    Cliente -->|Informa dados, agenda consultas| Atendimento
    Cliente -->|Fornece informações do animal| Cadastro
    Atendimento -->|Organiza fila e agenda| Veterinário
    Atendimento -->|Registra consulta e exames| Prontuário
    Veterinário -->|Realiza consulta, anota no prontuário| Prontuário
    Veterinário -->|Prescreve receitas e exames| Estoque
    Prontuário -->|Consulta histórico| Cliente
    Estoque -->|Atualiza medicamentos e ração| Prontuário
    Veterinário -->|Solicita exames e tratamento| Exames
    Exames -->|Agenda exames e armazena resultados| Prontuário
    Atendimento -->|Gerencia reagendamentos| Agenda
    Atendimento -->|Gerencia notificações| Notificações

```

## 9.2 Diagrama de Container
```mermaid
flowchart TB
    subgraph Sistema Veterinário
        Atendimento["Container: Atendimento"]
        Cadastro["Container: Cadastro de Cliente e Animal"]
        Agenda["Container: Gerenciamento de Agenda"]
        Prontuário["Container: Prontuário e Histórico Médico"]
        Exames["Container: Gerenciamento de Exames"]
        Notificações["Container: Notificações e Alertas"]
        Estoque["Container: Controle de Estoque"]
        Petshop["Container: Petshop - Venda de produtos"]
    end

    Cliente --> Atendimento
    Cliente --> Cadastro
    Atendimento --> Agenda
    Atendimento --> Prontuário
    Atendimento --> Notificações
    Prontuário --> Exames
    Prontuário --> Estoque
    Petshop --> Estoque

```

## 9.3 Diagrama de Componente
```mermaid
flowchart TB
    subgraph Sistema Veterinário
        subgraph Atendimento
            Atendimento_UI["Componente: Interface de Atendimento"]
            Verifica_Agenda["Componente: Verificação de Agenda"]
            Gerencia_Fila["Componente: Gerenciamento de Fila"]
            Notifica_Cliente["Componente: Notificação de Cliente"]
        end
        
        subgraph Cadastro
            Cadastro_Cliente["Componente: Cadastro de Cliente"]
            Cadastro_Animal["Componente: Cadastro de Animal"]
            Ficha_Medica["Componente: Ficha Médica do Animal"]
        end

        subgraph Prontuário
            Consulta["Componente: Consulta e Histórico"]
            Prescrição["Componente: Prescrição Médica"]
            Notas_Exames["Componente: Notas de Exames"]
        end
        
        subgraph Exames
            Exame_Solicitacao["Componente: Solicitação de Exames"]
            Exame_Resultados["Componente: Resultados de Exames"]
            Agendamento_Exames["Componente: Agendamento de Exames"]
        end
        
        subgraph Estoque
            Controle_Estoque["Componente: Controle de Estoque"]
            Registro_Produto["Componente: Registro de Produto"]
            Atualiza_Estoque["Componente: Atualização de Estoque"]
        end
    end
    
    Atendimento_UI --> Verifica_Agenda
    Verifica_Agenda --> Gerencia_Fila
    Gerencia_Fila --> Notifica_Cliente
    Cadastro_Cliente --> Cadastro_Animal
    Cadastro_Animal --> Ficha_Medica
    Consulta --> Prescrição
    Prescrição --> Notas_Exames
    Exame_Solicitacao --> Exame_Resultados
    Exame_Solicitacao --> Agendamento_Exames
    Controle_Estoque --> Atualiza_Estoque

```

## 9.4 Diagrama de Código
```mermaid
classDiagram
    class Atendimento {
        +agendarConsulta(cliente, animal, data)
        +verificarAgenda(veterinario, data)
        +adicionarNaFila(cliente, animal)
    }
    
    class Veterinario {
        +realizarConsulta(animal)
        +prescreverReceita(animal, medicamento)
        +solicitarExame(animal, tipoExame)
    }
    
    class Animal {
        -nome: String
        -idade: Int
        -habitos: String
        -restricoes: String
        +registrarCondicao(condicao)
        +adicionarFichaMedica(ficha)
    }
    
    class FichaMedica {
        -observacoes: String
        -diagnostico: String
        -receitas: List~Receita~
        -exames: List~Exame~
        +adicionarReceita(receita)
        +adicionarExame(exame)
    }
    
    class Estoque {
        -medicamentos: List~Medicamento~
        -racoes: List~Racao~
        +atualizarEstoque(item)
        +registrarVenda(cliente, item)
    }
    
    class Exame {
        -tipo: String
        -data: Date
        -resultado: String
    }
    
    Atendimento --> Veterinario : "agendamento"
    Atendimento --> Animal : "atualiza dados"
    Veterinario --> FichaMedica : "anota consulta"
    Veterinario --> Estoque : "prescreve"
    FichaMedica --> Exame : "solicita"
    Estoque --> Medicamento : "gerencia"

```

---

# 10. Protótipo de telas

[(voltar ao início)](#vitor_emanuel)

## 10.1. Tela Menu
![Figura : Tela Menu](https://github.com/VitorSauzen/vitor_emanuel/blob/main/src/images/tela_menu.png)

## 10.2. Telas de Cadastro
### 10.2.1 Cadastro de Agenda
![Figura : cadastro de agenda](https://github.com/VitorSauzen/vitor_emanuel/blob/main/src/images/tela_cadastro_agenda.png)
### 10.2.2 Cadastro de Animal
![Figura : cadastro de animal](https://github.com/VitorSauzen/vitor_emanuel/blob/main/src/images/tela_cadastro_animal.png)
### 10.2.3 Cadastro de Atendente
![Figura : cadastro de atendente](https://github.com/VitorSauzen/vitor_emanuel/blob/main/src/images/tela_cadastro_atendente.png)
### 10.2.4 Cadastro de Atendimento
![Figura : cadastro de atendimento](https://github.com/VitorSauzen/vitor_emanuel/blob/main/src/images/tela_cadastro_atendimento.png)
### 10.2.5 Cadastro de Cliente
![Figura : cadastro de cliente](https://github.com/VitorSauzen/vitor_emanuel/blob/main/src/images/tela_cadastro_cliente.png)
### 10.2.6 Cadastro de Exame
![Figura : cadastro de exame](https://github.com/VitorSauzen/vitor_emanuel/blob/main/src/images/tela_cadastro_exame.png)
### 10.2.7 Cadastro de Ficha
![Figura : cadastro de ficha](https://github.com/VitorSauzen/vitor_emanuel/blob/main/src/images/tela_cadastro_ficha.png)
### 10.2.8 Cadastro de Parceria
![Figura : cadastro de parceria](https://github.com/VitorSauzen/vitor_emanuel/blob/main/src/images/tela_cadastro_parceria.png)
### 10.2.9 Cadastro de Produto
![Figura : cadastro de produto](https://github.com/VitorSauzen/vitor_emanuel/blob/main/src/images/tela_cadastro_produto.png)
### 10.2.10 Cadastro de Servico
![Figura : cadastro de servico](https://github.com/VitorSauzen/vitor_emanuel/blob/main/src/images/tela_cadastro_servico.png)
### 10.2.11 Cadastro de Vacina
![Figura : cadastro de vacina](https://github.com/VitorSauzen/vitor_emanuel/blob/main/src/images/tela_cadastro_vacina.png)
### 10.2.12 Cadastro de Venda
![Figura : cadastro de venda](https://github.com/VitorSauzen/vitor_emanuel/blob/main/src/images/tela_cadastro_venda.png)
### 10.2.13 Cadastro de Veterinario
![Figura : cadastro de veterinario](https://github.com/VitorSauzen/vitor_emanuel/blob/main/src/images/tela_cadastro_veterinario.png)

## 10.3 Telas de Gráficos
### 10.3.1 Gráfico de Estoque
![Figura : grafico de estoque](https://github.com/VitorSauzen/vitor_emanuel/blob/main/src/images/tela_grafico_estoque.png)
### 10.3.1 Gráfico de Vendas
![Figura : grafico de vendas](https://github.com/VitorSauzen/vitor_emanuel/blob/main/src/images/tela_grafico_vendas.png)

## 10.4 Tela de Dashboard
![Figura : dashboard](https://github.com/VitorSauzen/vitor_emanuel/blob/main/src/images/tela_dashboard.png)

---

# 11. Diagrama de navegação de telas

[(voltar ao início)](#vitor_emanuel)

```mermaid
graph LR
    A[Login] --> B[Menu]
    B -->|Clique no dashboard| D[Dashboard]
    B -->|Clique em gráficos| E[Gráficos]
    B -->|Clique no menu lateral| C[Cadastros]
    
    C --> F[Cadastro de Agenda]
    C --> G[Cadastro de Animal]
    C --> H[Cadastro de Atendente]
    C --> I[Cadastro de Atendimento]
    C --> J[Cadastro de Cliente]
    C --> K[Cadastro de Exame]
    C --> L[Cadastro de Ficha]
    C --> M[Cadastro de Parceria]
    C --> N[Cadastro de Produto]
    C --> O[Cadastro de Servico]
    C --> P[Cadastro de Vacina]
    C --> Q[Cadastro de Venda]
    C --> R[Cadastro de Veterinario]
    
    E --> S[Gráfico de Estoque]
    E --> T[Gráfico de Vendas]
```

---

# 12. Pilha tecnológica

[(voltar ao início)](#vitor_emanuel)

## 12.1. Gráfico da Pilha

```mermaid
graph TD
    subgraph "Pilha Tecnológica - Clínica Veterinária"
        A[Linux]
        B[Apache - Servidor Web]
        
        subgraph "Back-End"
            C[PHP - ScriptCase Framework]
            D[APIs Internas e Externas]
        end

        subgraph "Banco de Dados"
            E[MySQL]
            F[Tabelas Relacionais]
            G[Armazenamento de Histórico Clínico]
        end

        subgraph "Front-End"
            H[HTML/CSS]
            I[Bootstrap]
            J[JavaScript]
            K[Gráficos e Dashboard Interativos]
        end
    end

    A --> B
    B --> C
    C --> D
    C --> E
    E --> F
    E --> G
    D --> H
    H --> I
    I --> J
    J --> K
```

## 12.2. Detalhamento das Camadas da Pilha
 
### 12.2.1 **Linux** (Sistema Operacional): 
   - Sistema operacional de base que hospeda o servidor web, escolhendo uma distribuição que seja compatível com Apache e MySQL.

### 12.2.2. **Apache (Servidor Web)**:
   - Responsável por gerenciar requisições HTTP e servir os arquivos da aplicação ao cliente.
   - Configurado para suportar **PHP** e se comunicar com o **MySQL** para processamento de dados e consultas.

### 12.2.3. **Back-End (PHP - ScriptCase)**:
   - **PHP com ScriptCase**: Framework que facilita o desenvolvimento de aplicações web com geração automática de formulários, dashboards e gráficos.
   - **APIs Internas e Externas**: Para funcionalidades como controle de estoque, registros de consultas, e gráficos, além de integração com sistemas de terceiros, se necessário.
   - **Gerenciamento de Sessões**: Para login seguro e controle de permissões, essencial para o acesso de veterinários, clientes e atendentes ao sistema.

### 12.2.4. **Banco de Dados (MySQL)**:
   - **Tabelas Relacionais**: Estruturadas para armazenar dados de clientes, animais, atendimentos, prontuários, etc.
   - **Armazenamento de Histórico Clínico**: Estrutura de dados para o registro detalhado de consultas, exames e procedimentos, que facilita a consulta e histórico do animal.

### 12.2.5. **Front-End (HTML, CSS, Bootstrap, JavaScript)**:
   - **HTML/CSS**: Estrutura e estilização das páginas.
   - **Bootstrap**: Framework CSS integrado ao ScriptCase, que permite um design responsivo e consistente.
   - **JavaScript**: Para funcionalidades interativas, como formulários dinâmicos e navegação fluida.
   - **Gráficos e Dashboard Interativos**: Utilização de bibliotecas JavaScript para gráficos interativos e visualização de dados da clínica, como estoque e número de atendimentos.


---

# 13. Requisitos de sistemas

[(voltar ao início)](#vitor_emanuel)

## 13.1. Requisitos do Lado Cliente

### 13.1.1. Dispositivos:
   - O sistema é acessível a partir de PCs, tablets e smartphones, para facilitar o uso tanto por funcionários quanto por clientes.

### 13.1.2. Navegadores Web:
   - Compatível com navegadores modernos, como **Google Chrome**, **Mozilla Firefox**, e **Microsoft Edge** para melhor acessibilidade e experiência do usuário.

### 13.1.3. Interface de Usuário:
   - A interface é construída com **React.js** e **Bootstrap** para uma experiência de usuário responsiva e interativa.

### 13.1.4. Autenticação:
   - Os usuários precisam autenticar-se por meio de login para acessar as funcionalidades, garantindo segurança e controle de acesso.

### 13.1.5. Funcionalidades Disponíveis:
   - **Notificações** de vacinas e procedimentos periódicos.
   - **Agendamento** de consultas e exames.
   - **Acesso ao histórico** completo do animal, incluindo exames e tratamentos.
   - **Formulários** para cadastro, atendimento e exames.
   - **Marcação e cancelamento** de consultas de forma simplificada.


## 13.2. Requisitos do Lado Servidor

### 13.2.1. Servidor de Aplicação:
   - O **Node.js** serve como o servidor de aplicação principal, gerenciando a lógica de negócios e as interações do cliente com o sistema.

### 13.2.2. Servidor de Banco de Dados:
   - Utilização do **MySQL** para dados relacionais (clientes, animais, veterinários, consultas)
   - **MongoDB** para dados não relacionais, como logs e histórico clínico dos animais.

### 13.2.3. Servidor Web:
   - O **Apache** é o servidor web responsável por servir conteúdo estático e lidar com requisições dinâmicas para o backend.

### 13.2.4. API REST:
   - A **API** baseada em **Express.js** é o ponto de comunicação entre o cliente e o servidor, facilitando o envio de dados e recebimento de respostas.

### 13.2.5. Funcionalidades do Servidor:
   - **Autenticação JWT**: Garante que os usuários autenticados tenham acesso seguro às funcionalidades.
   - **Gestão de Usuários e Permissões**: Controle de acesso baseado em permissões.
   - **Gestão de Agenda**: Organização de horários de consultas e exames.
   - **Gestão de Estoque**: Controle automatizado do estoque de medicamentos e rações.
   - **Cadastro de Animais e Veterinários**: Registro de novos pacientes e profissionais.
   - **Prontuário e Ficha Médica**: Registro de saúde completo do animal.
   - **Controle de Exames Complementares**: Registros e agendamento de exames adicionais.
   - **Emissão de Receitas**: Gerenciamento de prescrições de medicamentos.
   - **Backup e Recuperação**: Sistema automático de backup e restauração de dados.
   - **Integração com Pagamentos**: Sistema de pagamento para consultas e produtos.
   - **Monitoramento e Logs**: Armazenamento e rastreamento de atividades e eventos do sistema.


---

# 14. Considerações sobre segurança

[(voltar ao início)](#vitor_emanuel)

A segurança é um aspecto essencial na arquitetura de um sistema para garantir a proteção de dados sensíveis, prevenir ataques cibernéticos, e assegurar que o software esteja em conformidade com regulamentações. Uma abordagem preventiva é fundamental para a confiança dos usuários e para a estabilidade da aplicação.

## 14.1. Lado Cliente

### Regras de Senha
- **Força da senha**: Exige no mínimo 8 caracteres, com pelo menos uma letra maiúscula, uma minúscula, um número e um caractere especial.
- **Autenticação de Dois Fatores (2FA)**: Requer um segundo fator de autenticação, como código por SMS ou aplicativo autenticador.
- **Recuperação de Senha com E-mail**: Para redefinir a senha, o usuário recebe um link ou código no e-mail cadastrado, mantendo um fluxo seguro de recuperação.

### Política de Segurança
- **Captcha**: Adicionado em formulários de login para evitar ataques de bots.
- **Antivírus**: Recomenda-se que os dispositivos do cliente tenham antivírus atualizado para evitar roubo de credenciais e outros tipos de malware.

## 14.2. Lado Servidor

### Sistema Operacional
- **Linux**: O servidor de aplicação e o banco de dados operam sobre uma distribuição Linux (como Ubuntu Server ou CentOS) devido à estabilidade, segurança e personalização oferecidas pela plataforma para ambientes web.

### Política de Backup
- **Backups Diários Incrementais**: Realizados no final de cada dia para registrar mudanças recentes.
- **Backups Quinzenais Completos**: Realizados a cada 15 dias para assegurar uma cópia integral do sistema.
- **Backup Mensal Completo**: Realizado uma vez por mês e armazenado em uma localização segura fora do ambiente principal do servidor, como um armazenamento externo ou na nuvem.
- **Monitoramento de Backup**: Realizado por ferramentas automatizadas que garantem que os backups ocorram conforme planejado, com notificações sobre falhas.

### Políticas de Acesso e Privacidade
- **Administração Restrita**: O administrador do sistema não tem acesso aos dados sensíveis dos usuários, apenas a permissões e funções administrativas necessárias para manter o funcionamento do sistema.
- **Acesso Baseado em Funções (RBAC)**: Permissões são gerenciadas com base nas funções dos usuários, restringindo ações de leitura e escrita aos dados relevantes.

### Medidas de Segurança Adicionais
- **Firewall**: Proteção do servidor com firewall configurado para limitar acessos apenas a portas necessárias, como 80 (HTTP) e 443 (HTTPS).
- **Criptografia**: Dados sensíveis, como senhas e informações médicas, são armazenados criptografados no banco de dados. A transmissão de dados entre cliente e servidor é feita via HTTPS.
- **Logs de Segurança e Monitoramento**: Ferramentas de monitoramento e logs de auditoria para rastrear atividades e detectar tentativas de intrusão.


---

# 15. Instalação, Manutenção e Novas Funcionalidades

[(voltar ao início)](#vitor_emanuel)

Este tópico descreve os processos necessários para a instalação, manutenção e expansão de funcionalidades do sistema, incluindo critérios para avaliação de novas demandas.

## 15.1. Instalação

Para garantir que o sistema seja configurado corretamente, seguem as diretrizes de instalação:

- **Ambiente do Servidor**:
  - Verificar se o servidor possui uma distribuição Linux (Ubuntu Server recomendado) ou compatível com as exigências do sistema.
  - Instalar o Apache como servidor web e garantir que o PHP (versão compatível com o ScriptCase) esteja configurado.
  - Configurar o banco de dados MySQL e MongoDB, criando os usuários e as permissões necessárias.
  - Configurar variáveis de ambiente para armazenar credenciais e dados sensíveis de forma segura.
  - Utilizar HTTPS para comunicação segura e configurar o firewall para liberar apenas as portas necessárias (80 e 443).

- **Clientes**:
  - O cliente acessa o sistema pelo navegador, dispensando instalações adicionais no dispositivo.
  - Garantir a compatibilidade com navegadores modernos (Chrome, Firefox, Edge).
  - Instruir o cliente a manter o antivírus atualizado e seguir políticas de senha seguras.

## 15.2. Manutenção

A manutenção contínua é essencial para a estabilidade e segurança do sistema. As regras incluem:

- **Backups Regulares**:
  - Verificar e armazenar os backups diários incrementais e completos quinzenais e mensais.
  - Monitorar a integridade dos backups e a frequência dos procedimentos para evitar falhas de recuperação.

- **Atualizações de Segurança**:
  - Atualizar regularmente os pacotes de software (Apache, PHP, e MongoDB) e garantir que estejam protegidos contra vulnerabilidades conhecidas.
  - Realizar atualizações de segurança nos scripts de autenticação e APIs REST, conforme surgirem novas práticas ou regulamentações.

- **Monitoramento e Logs**:
  - Manter logs de auditoria para rastrear atividades e detectar tentativas de acesso indevido ou anomalias no sistema.
  - Monitorar o desempenho do sistema para identificar gargalos e otimizar o funcionamento conforme necessário.

## 15.3. Novas Funcionalidades

Para solicitações de novas funcionalidades, devem ser consideradas as seguintes diretrizes:

- **Procedimentos e Limitações**:
  - O cliente deve formalizar o pedido por meio de um documento ou formulário específico, detalhando a nova funcionalidade desejada.
  - O cliente não interfere na escolha de tecnologias ou design técnico, mantendo-se focado na funcionalidade e usabilidade.

- **Critérios de Viabilidade**:
  - **Equipe tem tempo?**: A equipe possui recursos e disponibilidade para trabalhar na nova funcionalidade sem comprometer outros processos?
  - **É economicamente viável?**: O custo e o esforço de desenvolvimento estão dentro do orçamento disponível?
  - **É tecnologicamente viável?**: A nova funcionalidade é compatível com a infraestrutura existente e as tecnologias empregadas?

Se a funcionalidade não atender a todos os critérios acima, o desenvolvimento deve ser cancelado, adiado ou reavaliado para uma nova fase do projeto.

Essas políticas garantem que o sistema permaneça estável e seguro, além de oferecer uma expansão bem planejada, evitando sobrecargas e instabilidades.


---

# 16. Treinamento

[(voltar ao início)](#vitor_emanuel)

Para assegurar que o sistema seja utilizado de maneira eficaz, é necessário oferecer treinamentos específicos para os usuários finais e para o administrador do sistema. Esses treinamentos ajudarão a garantir que todos os envolvidos saibam utilizar as funcionalidades disponíveis, evitando erros e aumentando a eficiência operacional.

## 16.1. Treinamento dos Usuários

O treinamento dos usuários será focado nas principais funcionalidades que eles utilizarão no dia a dia. Seguem os pontos principais:

- **Público-Alvo**: Atendentes, veterinários e profissionais de suporte.
- **Conteúdo do Treinamento**:
  - **Navegação no Sistema**: Explicação do layout, das telas de login, dashboard e menu principal.
  - **Cadastro de Dados**: Passo a passo de como cadastrar clientes, animais, fichas de atendimento e agendamentos.
  - **Agendamentos e Filas**: Como consultar a agenda de atendimentos e agendar exames ou consultas futuras.
  - **Consulta e Atualização de Fichas**: Instruções sobre o preenchimento de fichas médicas, anotação de exames, vacinas, e inclusão de novas observações.
  - **Relatórios e Gráficos**: Como acessar e interpretar relatórios de vendas, estoque e gráficos gerados pelo sistema.
  - **Regras de Segurança**: Recomendações sobre a importância do uso de senhas fortes, logoff após o uso e boas práticas de proteção de dados.

- **Metodologia**: Treinamentos presenciais com duração de uma a duas horas, com recursos audiovisuais e materiais de apoio. Haverá também vídeos tutoriais e guias rápidos disponíveis para consulta posterior.

## 16.2. Treinamento do Administrador do Sistema

O treinamento do administrador do sistema é mais técnico e abrange aspectos de configuração, segurança e manutenção. Ele deve estar preparado para lidar com problemas, executar backups e monitorar o sistema.

- **Conteúdo do Treinamento**:
  - **Gerenciamento de Usuários e Permissões**: Como adicionar, remover e ajustar permissões dos usuários do sistema.
  - **Configuração e Atualização do Sistema**: Procedimentos para atualizar o sistema, configurar parâmetros de segurança e gerenciar o banco de dados.
  - **Monitoramento e Logs**: Análise de logs e monitoramento do sistema para identificação de possíveis problemas ou atividades suspeitas.
  - **Backups e Recuperação de Dados**: Execução de backups e restauração de dados em caso de falhas ou perda de informações.
  - **Segurança e Acesso**: Implementação de autenticação de dois fatores, gerenciamento de senhas de administrador e práticas para garantir a segurança do sistema.
  - **Manutenção Preventiva**: Procedimentos de manutenção regular para garantir que o sistema esteja funcionando corretamente, incluindo testes de performance e atualizações de pacotes.

- **Metodologia**: Treinamento presencial com maior duração e profundidade, com simulações práticas para realizar backup, restaurar dados e gerenciar permissões. Manuais técnicos e instruções detalhadas também estarão disponíveis para consulta.


---

# 17. Script SQL

[(voltar ao início)](#vitor_emanuel)

## 17.1 Script para criar as tabelas
```SQL
-- Tabela de Clientes
CREATE TABLE Cliente (
    id_cliente INT AUTO_INCREMENT PRIMARY KEY,
    cpf VARCHAR(11) NOT NULL UNIQUE,
    nome VARCHAR(100) NOT NULL,
    endereco VARCHAR(255),
    telefone VARCHAR(15),
    email VARCHAR(100),
    fidelidade BOOLEAN DEFAULT FALSE
);

-- Tabela de Animais
CREATE TABLE Animal (
    id_animal INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(100) NOT NULL,
    tipo ENUM('gato', 'cachorro') NOT NULL, -- Somente gatos e cachorros
    condicao VARCHAR(255),
    habitos TEXT,
    tipo_racao VARCHAR(100),
    alergias TEXT,
    id_cliente INT,
    FOREIGN KEY (id_cliente) REFERENCES Cliente(id_cliente)
);

-- Tabela de Veterinários
CREATE TABLE Veterinario (
    id_veterinario INT AUTO_INCREMENT PRIMARY KEY,
    cpf VARCHAR(11) NOT NULL UNIQUE,
    nome VARCHAR(100) NOT NULL,
    endereco VARCHAR(255),
    telefone VARCHAR(15),
    email VARCHAR(100),
    especialidade VARCHAR(100)
);

-- Tabela de Atendentes
CREATE TABLE Atendente (
    id_atendente INT AUTO_INCREMENT PRIMARY KEY,
    cpf VARCHAR(11) NOT NULL UNIQUE,
    nome VARCHAR(100) NOT NULL,
    endereco VARCHAR(255),
    telefone VARCHAR(15),
    email VARCHAR(100)
);

-- Tabela de Fichas/Prontuários
CREATE TABLE Ficha (
    id_ficha INT AUTO_INCREMENT PRIMARY KEY,
    id_animal INT,
    observacoes TEXT,
    receita TEXT,
    FOREIGN KEY (id_animal) REFERENCES Animal(id_animal)
);

-- Tabela de Exames
CREATE TABLE Exame (
    id_exame INT AUTO_INCREMENT PRIMARY KEY,
    tipo_exame VARCHAR(100) NOT NULL,
    resultado TEXT,
    data_exame DATE NOT NULL,
    id_ficha INT,
    FOREIGN KEY (id_ficha) REFERENCES Ficha(id_ficha)
);

-- Tabela de Agendas
CREATE TABLE Agenda (
    id_agenda INT AUTO_INCREMENT PRIMARY KEY,
    data_consulta DATE NOT NULL,
    hora_consulta TIME NOT NULL,
    disponivel BOOLEAN DEFAULT TRUE,
    id_animal INT,
    id_veterinario INT,
    id_atendente INT,
    FOREIGN KEY (id_animal) REFERENCES Animal(id_animal),
    FOREIGN KEY (id_veterinario) REFERENCES Veterinario(id_veterinario),
    FOREIGN KEY (id_atendente) REFERENCES Atendente(id_atendente)
);

-- Tabela de Vacinas
CREATE TABLE Vacina (
    id_vacina INT AUTO_INCREMENT PRIMARY KEY,
    tipo_vacina VARCHAR(100) NOT NULL,
    fabricante VARCHAR(100),
    id_animal INT,
    FOREIGN KEY (id_animal) REFERENCES Animal(id_animal)
);

-- Tabela de Produtos (vendidos pela clínica)
CREATE TABLE Produto (
    id_produto INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(100) NOT NULL,
    categoria ENUM('racao', 'medicamento', 'outros') NOT NULL,
    estoque INT NOT NULL
);

-- Tabela de Vendas de Produtos
CREATE TABLE Venda (
    id_venda INT AUTO_INCREMENT PRIMARY KEY,
    id_cliente INT,
    id_produto INT,
    quantidade INT,
    valor_total DECIMAL(10, 2) NOT NULL, -- Valor total da venda
    data_venda DATE NOT NULL,
    FOREIGN KEY (id_cliente) REFERENCES Cliente(id_cliente),
    FOREIGN KEY (id_produto) REFERENCES Produto(id_produto)
);

-- Tabela de Histórico de Atendimentos
CREATE TABLE Atendimento (
    id_atendimento INT AUTO_INCREMENT PRIMARY KEY,
    data_atendimento DATE NOT NULL,
    id_veterinario INT,
    id_animal INT,
    id_ficha INT,
    FOREIGN KEY (id_veterinario) REFERENCES Veterinario(id_veterinario),
    FOREIGN KEY (id_animal) REFERENCES Animal(id_animal),
    FOREIGN KEY (id_ficha) REFERENCES Ficha(id_ficha)
);

-- Tabela de Parcerias (com pet shops ou laboratórios)
CREATE TABLE Parceria (
    id_parceria INT AUTO_INCREMENT PRIMARY KEY,
    nome_parceria VARCHAR(100) NOT NULL,
    tipo_parceria ENUM('petshop', 'laboratorio') NOT NULL,
    descricao TEXT
);

-- Tabela de Serviços (Banho e Tosa)
CREATE TABLE Servico (
    id_servico INT AUTO_INCREMENT PRIMARY KEY,
    tipo_servico ENUM('banho', 'tosa') NOT NULL,
    preco DECIMAL(10, 2) NOT NULL,
    id_animal INT,
    data_servico DATE NOT NULL,
    FOREIGN KEY (id_animal) REFERENCES Animal(id_animal)
);
```

## 17.2 Scrip para inserir dados fictícios
```SQL
-- Inserindo registros na tabela Cliente
INSERT INTO Cliente (cpf, nome, endereco, telefone, email, fidelidade) VALUES
('12345678901', 'João Silva', 'Rua A, 123', '11999999999', 'joao@gmail.com', TRUE),
('23456789012', 'Maria Souza', 'Rua B, 456', '11988888888', 'maria@yahoo.com', FALSE),
('34567890123', 'Pedro Lima', 'Rua C, 789', '11977777777', 'pedro@hotmail.com', TRUE),
('45678901234', 'Ana Oliveira', 'Rua D, 101', '11966666666', 'ana@empresa.com', FALSE),
('56789012345', 'Lucas Costa', 'Rua E, 202', '11955555555', 'lucas@outlook.com', TRUE);

-- Inserindo registros na tabela Animal
INSERT INTO Animal (nome, tipo, condicao, habitos, tipo_racao, alergias, id_cliente) VALUES
('Rex', 'cachorro', 'saudável', 'dorme muito', 'Ração Premium', NULL, 1),
('Mimi', 'gato', 'machucado', 'gosta de caçar', 'Ração para gatos', 'Peixe', 2),
('Thor', 'cachorro', 'resfriado', 'muito agitado', 'Ração de frango', NULL, 3),
('Luna', 'gato', 'saudável', 'adora brincar', 'Ração sem corantes', 'Frango', 4),
('Bobby', 'cachorro', 'alérgico', 'passeios curtos', 'Ração especial', 'Carne', 5);

-- Inserindo registros na tabela Veterinario
INSERT INTO Veterinario (cpf, nome, endereco, telefone, email, especialidade) VALUES
('98765432100', 'Dr. Carlos Mendes', 'Av. X, 1010', '11944444444', 'carlos@clinica.com', 'Cirurgia'),
('87654321099', 'Dra. Fernanda Almeida', 'Av. Y, 2020', '11933333333', 'fernanda@clinica.com', 'Dermatologia'),
('76543210988', 'Dr. Lucas Pereira', 'Av. Z, 3030', '11922222222', 'lucas@clinica.com', 'Ortopedia'),
('65432109877', 'Dra. Paula Lima', 'Rua W, 4040', '11911111111', 'paula@clinica.com', 'Cardiologia'),
('54321098766', 'Dr. José Neto', 'Rua V, 5050', '11900000000', 'jose@clinica.com', 'Oftalmologia');

-- Inserindo registros na tabela Atendente
INSERT INTO Atendente (cpf, nome, endereco, telefone, email) VALUES
('11223344556', 'Camila Santos', 'Rua P, 100', '11999998888', 'camila@clinica.com'),
('22334455667', 'Bruno Nascimento', 'Rua Q, 200', '11988887777', 'bruno@clinica.com'),
('33445566778', 'Sara Oliveira', 'Rua R, 300', '11977776666', 'sara@clinica.com'),
('44556677889', 'Eduardo Gomes', 'Rua S, 400', '11966665555', 'eduardo@clinica.com'),
('55667788990', 'Laura Martins', 'Rua T, 500', '11955554444', 'laura@clinica.com');

-- Inserindo registros na tabela Ficha
INSERT INTO Ficha (id_animal, observacoes, receita) VALUES
(1, 'Exame geral. Animal saudável.', 'Vitaminas diárias'),
(2, 'Machucado na pata. Recomendado repouso.', 'Anti-inflamatório'),
(3, 'Resfriado leve. Prescrever antibióticos.', 'Amoxilina 250mg'),
(4, 'Animal em boas condições.', 'Nenhum medicamento'),
(5, 'Alergia a alimentos. Precaução com ração.', 'Antialérgico');

-- Inserindo registros na tabela Exame
INSERT INTO Exame (tipo_exame, resultado, data_exame, id_ficha) VALUES
('Exame de Sangue', 'Resultados normais', '2024-09-10', 1),
('Raio-X', 'Fratura detectada', '2024-09-11', 2),
('Ultrassom', 'Resfriado detectado', '2024-09-12', 3),
('Exame de Sangue', 'Resultados normais', '2024-09-13', 4),
('Raio-X', 'Nenhuma anormalidade', '2024-09-14', 5);

-- Inserindo registros na tabela Agenda
INSERT INTO Agenda (data_consulta, hora_consulta, disponivel, id_animal, id_veterinario, id_atendente) VALUES
('2024-09-20', '10:00:00', FALSE, 1, 1, 1),
('2024-09-21', '11:00:00', FALSE, 2, 2, 2),
('2024-09-22', '12:00:00', TRUE, NULL, 3, 3),
('2024-09-23', '13:00:00', TRUE, NULL, 4, 4),
('2024-09-24', '14:00:00', TRUE, NULL, 5, 5);

-- Inserindo registros na tabela Vacina
INSERT INTO Vacina (tipo_vacina, fabricante, id_animal) VALUES
('Antirrábica', 'VeterMed', 1),
('V8', 'PetPharm', 2),
('Antirrábica', 'VetPro', 3),
('V10', 'PetCare', 4),
('Leptospirose', 'AnimalHealth', 5);

-- Inserindo registros na tabela Produto
INSERT INTO Produto (nome, categoria, estoque) VALUES
('Ração Premium', 'racao', 50),
('Antibiótico', 'medicamento', 20),
('Ração para Gatos', 'racao', 30),
('Antialérgico', 'medicamento', 10),
('Brinquedo para Cães', 'outros', 100);

-- Inserindo registros na tabela Venda
INSERT INTO Venda (id_cliente, id_produto, quantidade, valor_total, data_venda) VALUES
(1, 1, 2, 100.00, '2024-09-15'),
(2, 2, 1, 50.00, '2024-09-16'),
(3, 3, 3, 90.00, '2024-09-17'),
(4, 4, 1, 20.00, '2024-09-18'),
(5, 5, 5, 150.00, '2024-09-19');

-- Inserindo registros na tabela Atendimento
INSERT INTO Atendimento (data_atendimento, id_veterinario, id_animal, id_ficha) VALUES
('2024-09-20', 1, 1, 1),
('2024-09-21', 2, 2, 2),
('2024-09-22', 3, 3, 3),
('2024-09-23', 4, 4, 4),
('2024-09-24', 5, 5, 5);

-- Inserindo registros na tabela Parceria
INSERT INTO Parceria (nome_parceria, tipo_parceria, descricao) VALUES
('PetShop Amigo', 'petshop', 'Venda de ração e brinquedos para animais'),
('LabVet', 'laboratorio', 'Realização de exames de sangue e imagem'),
('PetCenter', 'petshop', 'Descontos em produtos para clientes da clínica'),
('LabVet Premium', 'laboratorio', 'Exames avançados para animais de grande porte'),
('PetPlus', 'petshop', 'Programa de descontos e vendas de produtos para cães e gatos');

-- Inserindo registros na tabela Servico
INSERT INTO Servico (tipo_servico, preco, id_animal, data_servico) VALUES
('banho', 50.00, 1, '2024-09-18'),
('tosa', 60.00, 2, '2024-09-19'),
('banho', 50.00, 3, '2024-09-20'),
('tosa', 60.00, 4, '2024-09-21'),
('banho', 50.00, 5, '2024-09-22');
```

[(voltar ao início)](#vitor_emanuel)