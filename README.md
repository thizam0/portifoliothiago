# portifoliothiago
# SOC OPS 

**SOC OPS** é um laboratório prático que simula operações reais de um SOC (Security Operations Center).  
O projeto cobre desde ingestão de logs e detecção de ameaças até automação de resposta, forense e hunting,  
mostrando na prática como investigar, conter e documentar incidentes de segurança.

> Objetivo: demonstrar experiência prática aplicada em **SIEM, EDR, Threat Hunting, Forense e Automação**,  


---

##  Principais Capacidades Demonstradas
- **SIEM/EDR**: ingestão de logs, dashboards e correlação de eventos (Wazuh/ELK, Splunk Free, osquery, Sysinternals)  
- **Threat Hunting**: queries mapeadas para MITRE ATT&CK e investigações guiadas  
- **Forense**: análise rápida de memória e extração de evidências com Volatility  
- **Automação (SOAR)**: scripts Python/PowerShell para resposta automatizada  
- **Resposta a Incidentes**: playbooks padronizados, timelines e relatórios de incidentes  
- **Documentação Profissional**: todos os labs incluem evidências (PCAPs, logs, screenshots e relatórios markdown)  

---

##  Estrutura do Projeto
- `labs/` → relatórios técnicos e evidências de cada simulação  
- `scripts/` → automações (Python / PowerShell)  
- `dashboards/` → consultas e visualizações SIEM/EDR  
- `docs/` → playbooks de resposta a incidentes e hunting guides  

---

##  Destaques para Entrevista
- **Dashboards de detecção** → login falho + execução de processo suspeito  
- **Query MITRE ATT&CK** → hunting contra execução de PowerShell obfuscado  
- **Playbook IR** → phishing com exfiltração HTTP (simulado, detectado, contido e documentado)  
- **Automação SOAR** → script para isolar host comprometido diretamente do SIEM  

---

##  Roadmap (8 semanas)
Cada semana foca em um pilar do SOC:  
1. Logs e triagem inicial (Windows/Linux)  
2. SIEM caseiro (Wazuh/ELK/Splunk)  
3. Visibilidade de endpoint (osquery / Sysinternals)  
4. Hunting com MITRE ATT&CK  
5. Forense rápida (Volatility)  
6. Automação / SOAR com scripts  
7. Playbooks de resposta a incidentes  
8. **Capstone** — simulação de ataque completo (Phishing → Execução → Exfiltração)  

---

##  Tech Stack
- **SIEM/Logs**: Wazuh, ELK, Splunk Free, Beats  
- **EDR**: osquery, Sysinternals  
- **Hunting**: MITRE ATT&CK, SPL/KQL/Elastic queries  
- **Forense**: Volatility  
- **Automação**: Python, PowerShell  
- **Infra**: VMs Windows/Linux, Wireshark  

---

##  Autor
**Thiago (thizam0)** — Analista de Segurança da Informação  
Focado em Threat Hunting, Redução de Falsos positivos, Resposta a Incidentes e Automação de SOC.  
