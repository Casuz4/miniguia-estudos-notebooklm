# 📖 Miniguia de Estudo
## Como os grandes ataques históricos moldaram a cibersegurança moderna

---

## 1. Resumo Estruturado dos Ataques

### Cuckoo's Egg
- **Ano:** 1986
- **Vetor de ataque:** Acesso remoto manual via modems e rede X.25, usando sistemas universitários como pontes para redes militares
- **Vulnerabilidade explorada:** Senhas padrão, contas compartilhadas e bugs não corrigidos no Gnu-Emacs
- **Impacto:** Invasão de 30+ instalações militares, espionagem internacional
- **Legado defensivo:** Monitoramento de tráfego, expiração de senhas, honeypots

### Morris Worm
- **Ano:** 1988
- **Vetor de ataque:** Código autônomo autorreplicante via ARPANET
- **Vulnerabilidade explorada:** Conexões de rede abertas e erro de lógica no código
- **Impacto:** Paralisação de 6.000 sistemas, primeiro DoS da história, primeira condenação sob o Computer Fraud and Abuse Act
- **Legado defensivo:** Criação dos CERTs, adoção de firewalls

### Stuxnet
- **Ano:** 2010
- **Vetor de ataque:** Drives USB para transpor air-gap, propagação via 4 vulnerabilidades zero-day do Windows
- **Vulnerabilidade explorada:** Zero-days do Windows, certificados digitais roubados, senhas hardcoded no WinCC
- **Impacto:** Destruição física de ~1.000 centrífugas iranianas, primeira arma cibernética cinética
- **Legado defensivo:** Segurança de redes OT/SCADA, controle de mídias removíveis, segmentação de rede

---

## 2. Glossário

| Termo | Definição |
|---|---|
| Worm | Programa autossuficiente que se autorreplica via rede sem interação do usuário |
| Zero-day | Vulnerabilidade desconhecida pelo fabricante, sem correção disponível |
| PLC | Controlador industrial que monitora e controla equipamentos físicos |
| SCADA | Sistema de monitoramento e controle de processos industriais complexos |
| Air-gap | Rede completamente isolada da internet por barreira física |
| DoS | Ataque que sobrecarrega um sistema tornando-o indisponível |
| Rootkit | Ferramentas que ocultam atividades maliciosas e mantêm acesso root |
| ARPANET | Precursora da internet moderna, interligava instalações militares e acadêmicas |
| Certificado Digital | Documento eletrônico que valida autenticidade e integridade de arquivos |
| Payload | Parte do malware responsável pela ação destrutiva final |
| Malware | Programa malicioso que compromete confidencialidade, integridade ou disponibilidade |
| Firewall | Mecanismo que monitora e limita tráfego de rede para bloquear acessos não autorizados |
| CERT | Equipe especializada em resposta coordenada a incidentes de segurança |
| SMB | Protocolo de compartilhamento de rede explorado pelo Stuxnet para propagação |
| Vulnerabilidade | Fraqueza em um sistema que pode ser explorada por um invasor |

---

## 3. Prompts Reutilizáveis para Revisão

**P1 — Cuckoo's Egg e Honeypots:**
> Qual foi a estratégia inovadora criada pela equipe do LBL para rastrear o invasor no caso Cuckoo's Egg, e como ela influencia as tecnologias de Deception e Honeypots hoje?

**P2 — Morris Worm e Resposta a Incidentes:**
> Qual foi a principal consequência institucional do Morris Worm para a comunidade de segurança, e como ela moldou a resposta coordenada a incidentes modernos?

**P3 — Stuxnet e Redes Isoladas:**
> O que o Stuxnet ensinou sobre a segurança de redes air-gap e qual foi o vetor inicial utilizado para contornar essa barreira física?

**P4 — Stuxnet e Impacto Físico:**
> Como o Stuxnet atuava sobre os PLCs para causar destruição física nas centrífugas, e como ele impedia que os operadores notassem o problema?

**P5 — Legado e Segurança Moderna:**
> Por que práticas como Segmentação de Rede e Zero Trust se tornaram fundamentais para proteger infraestruturas críticas considerando as lições dos ataques históricos estudados?
