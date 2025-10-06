gantt
    title Gráfico de Gantt - Desenvolvimento do Sistema de Cadastro de Empresas Parceiras
    dateFormat  YYYY-MM-DD
    axisFormat %W  ;; Formato de eixo em semanas (ex: 1 para semana 1)
    todayMarker off

    section Planejamento e Requisitos
    Levantamento de Requisitos (Gerente/Analista) :req1, 2024-01-01, 14d
    Documentação Funcional (Analista) :doc1, after req1, 14d

    section Design
    Rascunhos de Telas (Designer) :design1, 2024-01-08, 21d
    Layout Definitivo (Designer) :design2, after design1, 21d

    section Desenvolvimento
    Configuração do Ambiente (Dev Team) :dev1, 2024-01-15, 14d
    Criação do Banco de Dados (Analista/Devs) :dev2, after dev1, 7d
    Módulo de Login e Autenticação (Devs) :dev3, after dev2, 14d
    CRUD de Empresas (Devs) :dev4, after dev3, 21d
    Upload de Logotipo (Devs) :dev5, after dev4, 14d
    Relatórios em PDF/Excel (Devs) :dev6, after dev5, 14d
    Painel Administrativo e Permissões (Devs) :dev7, after dev6, 14d

    section Testes
    Testes Unitários e Integração (QA/Devs) :test1, after dev7, 42d
    Testes de Usabilidade (QA/Usuários) :test2, after test1, 14d

    section Implantação
    Implantação Final e Validação (Gerente/QA) :deploy1, after test2, 14d

    section Entregas Parciais (Crystal Clear)
    Entrega 1: Módulo de Login :milestone1, 2024-01-22, 0d
    Entrega 2: CRUD de Empresas :milestone2, 2024-02-12, 0d
    Entrega 3: Upload de Logotipo :milestone3, 2024-02-26, 0d
    Entrega 4: Relatórios :milestone4, 2024-03-11, 0d
    Entrega 5: Painel Administrativo :milestone5, 2024-03-25, 0d
    Entrega Final: Sistema Completo :milestone6, 2024-06-30, 0d
