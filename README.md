# Grafana

> Grafana Docker Compose setup for local development

# Getting started
1. Create a `secrets.env` file from [secrets.env.example](secrets.env.example);
2. Set password for clickhouse;
3. Run `docker compose up -d` in the project root;

# Features
- [ ] Local development;
  - [x] Basic configuration for provisioning plugins, dashboard and datasources;
  - [ ] Description of development workflow;
- [ ] Git versioning;
  - [ ] Setup for proper secrets management;
- [ ] Infra
  - [ ] IaC configuration for deployment;
- [ ] CI/CD;
  - [ ] Git and deployment integration;

# Questions to solve
- What to do with plugins? Put them under version control or just configuration for them?
