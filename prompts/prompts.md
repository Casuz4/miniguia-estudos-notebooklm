# 📋 Engenharia de Prompts e Cicatrizes

## Como usar este documento
Para cada prompt testado, preencha um bloco abaixo.
Documente tudo — inclusive quando a IA errou ou foi vaga!

---

## PROMPT 01

**Prompt utilizado:**
```
Com base nas fontes, descreva o caso do Cuckoo's Egg 
de 1986: o que aconteceu, como o invasor foi rastreado 
e qual foi o impacto para a segurança de redes militares.
```

**Resposta obtida:**
> Resposta detalhada sobre Markus Hess invadindo o LBL em 1986,
> o método de monitoramento de Clifford Stoll, a armadilha com 
> arquivos fictícios sobre SDI e o impacto nas redes militares.

**Fontes citadas pelo NotebookLM:**
- Stalking the Wily Hacker — Clifford Stoll, 1988
- The Cuckoo's Egg (mencionado na resposta)

**Qualidade da resposta:** ⭐⭐⭐⭐⭐

**Cicatriz / Dificuldade encontrada:**
> Nenhuma — resposta completa e bem referenciada no primeiro prompt.

---

## PROMPT 02

**Prompt utilizado:**
```
Com base nas fontes, descreva o Morris Worm de 1988: 
como funcionava, qual vulnerabilidade explorou e 
qual foi seu impacto imediato.
```

**Resposta obtida:**
> Descreveu o Morris Worm como primeiro worm da internet, criado 
> por Robert T. Morris Jr. em 1988. Explicou o mecanismo de 
> autorreplicação, a paralisação de 6.000 computadores na ARPANET 
> e a primeira condenação sob o Computer Fraud and Abuse Act.

**Fontes citadas pelo NotebookLM:**
- 122246.122248.pdf
- História da guerra cibernética e os 5 ataques mais notórios - Fortinet
- Evolução da cibersegurança: Uma breve linha do tempo - ManageEngine Blog

**Qualidade da resposta:** ⭐⭐⭐⭐

**Cicatriz / Dificuldade encontrada:**
> O NotebookLM informou que as fontes não detalhavam as 
> vulnerabilidades técnicas específicas exploradas pelo worm. 
> As fontes cobriam o impacto e contexto, mas não os vetores 
> técnicos do ataque.

**Prompt reformulado:**
```
Quais foram as consequências legais e institucionais 
do Morris Worm? O que mudou na legislação e nas 
práticas de segurança após o incidente?
```

**Resposta do prompt reformulado:**
> Detalhou as consequências legais (primeira condenação sob o 
> Computer Fraud and Abuse Act) e institucionais: criação dos 
> primeiros CERTs, adoção de firewalls e controle de acesso 
> com senhas e criptografia.

**Lição aprendida neste prompt:**
> Quando a resposta inicial foi vaga sobre aspectos técnicos, 
> reformular o prompt com foco em consequências legais e 
> institucionais extraiu informações muito mais ricas e 
> conectadas ao tema central do projeto.

---

## PROMPT 03

**Prompt utilizado:**
```
Explique como o Stuxnet funcionava tecnicamente 
e por que ele foi considerado um marco na história 
da cibersegurança.
```

**Resposta obtida:**
> Explicou detalhadamente o funcionamento do Stuxnet: propagação 
> via USB com 4 vulnerabilidades zero-day, uso de certificados 
> digitais roubados, sabotagem física de centrífugas iranianas 
> e rootkit para PLCs que enganava os engenheiros com dados falsos.
> Destacou como primeiro malware com impacto físico real e marco 
> na segurança de sistemas industriais (OT/SCADA).

**Fontes citadas pelo NotebookLM:**
- artigo A GUERRA CIBERNÉTICA SOB A ÓTICA DE CLAUSEWITZ: UM ESTUDO DE CASO SOBRE O STUXNET - Portal de Revistas da USP
- “Fully Operational: Stuxnet 15 Years Later and the Evolution of Cyber Threats to Critical Infrastructure” - Homeland Security Committee
- w32_stuxnet_dossier.pdf

**Qualidade da resposta:** ⭐⭐⭐⭐⭐

**Cicatriz / Dificuldade encontrada:**
> Nenhuma — foi a resposta mais técnica e rica até agora.
> O NotebookLM cobriu propagação, exploração, sabotagem e impacto 
> geopolítico sem necessidade de reformulação.

---

## PROMPT 04

**Prompt utilizado:**
```
Compare os vetores de ataque do Cuckoo's Egg, 
do Morris Worm e do Stuxnet. O que eles têm 
em comum e o que os diferencia?
```

**Resposta obtida:**
> Análise comparativa dos três ataques. Em comum: todos 
> comprometeram infraestruturas críticas e exploraram falhas 
> sistêmicas básicas. Diferenças: ação humana vs. automação, 
> nível de sofisticação crescente, e impacto digital vs. físico. 
> Destaque para o Stuxnet como primeira arma cibernética com 
> destruição física real.

**Fontes citadas pelo NotebookLM:**
- 122246.122248.pdf
- STALKING THE WILY HACKER.pdf
- Evolução da cibersegurança: Uma breve linha do tempo - ManageEngine Blog

**Qualidade da resposta:** ⭐⭐⭐⭐⭐

**Cicatriz / Dificuldade encontrada:**
> Nenhuma — o prompt comparativo foi o que gerou a resposta 
> mais analítica e madura do projeto até agora. Prompts que 
> pedem comparação tendem a extrair mais profundidade do que 
> prompts descritivos simples.
> 
---

## PROMPT 05

**Prompt utilizado:**
```
Com base nos ataques estudados, quais práticas de 
segurança defensiva surgiram ou foram fortalecidas 
como resposta direta a esses incidentes? Organize 
por categoria: rede, endpoint, gestão de 
vulnerabilidades e resposta a incidentes.
```

**Resposta obtida:**
> Resposta organizada em 4 categorias com práticas defensivas 
> conectadas diretamente aos ataques estudados: firewalls e IDS 
> (Morris Worm), segmentação de rede (Stuxnet/WannaCry), controle 
> de mídias removíveis (Stuxnet), MFA (Cuckoo's Egg/Morris Worm), 
> criação dos CERTs (Morris Worm) e honeypots (Cuckoo's Egg).

**Fontes citadas pelo NotebookLM:**
- A Historia do Firewall - Alliances
- TENDÊNCIAS EM CIBERSEGURANÇA: uma análise em grupos de discussão - Even3
- História da guerra cibernética e os 5 ataques mais notórios - Fortinet
- NCCIC ICS_FactSheet_WannaCry_Ransomware_S508C.pdf
- “Fully Operational: Stuxnet 15 Years Later and the Evolution of Cyber Threats to Critical Infrastructure” - Homeland Security Committee

**Qualidade da resposta:** ⭐⭐⭐⭐⭐

**Cicatriz / Dificuldade encontrada:**
> Nenhuma — o prompt estruturado por categorias foi muito eficaz.
> Pedir organização por categoria gerou uma resposta diretamente 
> aproveitável como conteúdo final do miniguia.

---

## Lições Aprendidas
> 1. Prompts comparativos e estruturados por categoria extraem 
>    respostas mais ricas do que perguntas descritivas simples.
> 2. Quando a IA é vaga, reformular com foco em consequências 
>    em vez de técnica resolve a limitação.
> 3. Pedir organização explícita (por categoria, por formato) 
>    melhora muito a qualidade da resposta final.
```
