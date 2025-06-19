# Equifax Simulation – DevSecOps Demo

Este projeto simula o caso Equifax, utilizando uma versão vulnerável do Apache Struts (`2.3.31`) para demonstrar como ferramentas de análise de dependências (SCA) podem detectar falhas conhecidas (CVE-2017-5638).

## Ferramentas usadas
- Snyk (via GitHub Actions)
- OWASP Dependency-Check (opcional)

## Executando a análise
1. Configure seu token Snyk em `Settings > Secrets` com `SNYK_TOKEN`.
2. Faça um push no repositório.
3. A pipeline irá executar automaticamente e falhará ao encontrar a vulnerabilidade.

## Atenção ⚠️
Este projeto é estritamente educacional e não deve ser usado em ambientes de produção.