# 🧭 Projeto – TechConnect Solutions
[![Status do Projeto](https://img.shields.io/badge/Status-Em%20Planejamento-blue.svg)](https://github.com/seu-usuario/techconnect-solutions)
[![Prazo](https://img.shields.io/badge/Prazo-6%20Meses-green.svg)](https://github.com/seu-usuario/techconnect-solutions)
[![Metodologia](https://img.shields.io/badge/Metodologia-Crystal%20Clear-orange.svg)](https://github.com/seu-usuario/techconnect-solutions)



## 📘 Enunciado
A empresa **TechConnect Solutions** foi contratada por uma **rede de associações comerciais** para desenvolver um **Sistema de Cadastro de Empresas Parceiras**.  
O prazo de entrega é de **6 meses**, com uma equipe composta por:

- 👨‍💼 1 Gerente de Projetos  
- 💻 1 Analista de Sistemas  
- 👩‍💻 2 Desenvolvedores  
- 🎨 1 Designer de Interface  
- 🧪 1 Tester (QA)

O sistema incluirá: login, CRUD de empresas, upload de logotipo, relatórios em PDF/Excel, painel administrativo, interface responsiva e banco de dados seguro.

---

## 📊 Gráfico de Gantt (Mermaid)

```mermaid
gantt
    title Cronograma do Projeto - TechConnect Solutions (6 meses)
    dateFormat  YYYY-MM-DD
    axisFormat  %b

    section Planejamento
    Levantamento de requisitos          :a1, 2025-01-01, 14d
    Documentação funcional              :a2, after a1, 7d

    section Design
    Design de interface                 :a3, after a2, 14d

    section Desenvolvimento
    Configuração do ambiente            :a4, after a3, 7d
    Criação do banco de dados           :a5, after a4, 7d
    Módulo de login                     :a6, after a5, 14d
    CRUD de empresas                    :a7, after a6, 14d
    Upload de logotipo                  :a8, after a7, 14d
    Relatórios PDF/Excel                :a9, after a8, 14d
    Painel administrativo               :a10, after a9, 14d

    section Testes e Entrega
    Testes e QA                         :a11, after a10, 21d
    Implantação e validação final       :a12, after a11, 7d
