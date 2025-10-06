gantt
    title Cronograma do Projeto - Sistema de Cadastro de Empresas Parceiras
    dateFormat  YYYY-MM-DD
    axisFormat  %d/%m
    section Planejamento e Análise
    Levantamento de requisitos           :a1, 2025-10-06, 10d
    Documentação funcional               :a2, after a1, 7d
    Design de interface (rascunhos e layout) :a3, after a2, 10d

    section Configuração Inicial
    Configuração do ambiente e Git       :b1, after a3, 7d
    Criação do banco de dados (MySQL)    :b2, after b1, 5d

    section Desenvolvimento
    Módulo de login (autenticação e recuperação de senha) :c1, after b2, 14d
    CRUD de empresas                     :c2, after c1, 21d
    Upload de logotipo                   :c3, after c2, 14d
    Relatórios em PDF e Excel            :c4, after c3, 14d
    Painel administrativo e permissões   :c5, after c4, 14d

    section Testes e Entrega
    Testes unitários e integração (QA)   :d1, after c5, 14d
    Testes de usabilidade                :d2, after d1, 7d
    Implantação e entrega final          :d3, after d2, 7d

    section Entregas Crystal Clear
    Entrega 1 - Login (Semana 3)         :milestone, m1, 2025-10-27, 0d
    Entrega 2 - CRUD de empresas (Semana 6) :milestone, m2, 2025-11-17, 0d
    Entrega 3 - Upload de logotipo (Semana 8) :milestone, m3, 2025-12-01, 0d
    Entrega 4 - Relatórios (Semana 10)   :milestone, m4, 2025-12-15, 0d
    Entrega 5 - Painel administrativo (Semana 12) :milestone, m5, 2025-12-29, 0d
    Entrega Final - Sistema completo (Mês 6) :milestone, m6, 2026-04-06, 0d
