---
titulo: "{{ Nome do Cargo }}"
area: "{{ Área principal (ex.: Blue Team, GRC, IAM, Red Team, Purple Team) }}"
nivel: "{{ Júnior/Pleno/Sênior }}"
tipo: "{{ Tipo de cargo (Analista, Engenheiro, Arquiteto, Consultor, Especialista) }}"
secframe_categoria: "{{ Categoria interna do SecFrame BR (ex.: Defesa Operacional, Governança, Identidade) }}"
secframe_subcategoria: ["{{ Subcategoria 1 }}", "{{ Subcategoria 2 }}"]
slug_arquivo: "{{ nome-do-arquivo-em-minusculas-com-hifens }}"
---

# {{ Nome do Cargo }}

## 📌 Escopo
Descreva de forma breve (2–3 frases) o objetivo principal do cargo.  
Exemplo: *Responsável por monitorar alertas de segurança, operar ferramentas de SOC e apoiar a resposta inicial a incidentes.*

---

## 🎯 Responsabilidades
Liste as principais atividades do cargo.  
Preencha de forma objetiva na tabela abaixo:

| Atividade | Entregável | Ferramentas |
|-----------|------------|-------------|
| {{ Ex.: Monitorar eventos no SIEM }} | {{ Tickets de incidente }} | {{ Splunk, QRadar }} |
| {{ ... }} | {{ ... }} | {{ ... }} |

---

## 🛠️ Competências Técnicas
Liste os conhecimentos técnicos mais comuns, classificando por domínio.

| Domínio | Subcompetências | Nível mínimo | Diferenciais |
|---|---|---|---|
| {{ Ex.: SIEM/SOAR }} | {{ Queries, automação }} | {{ Intermediário }} | {{ UEBA, Playbooks }} |
| {{ Redes }} | {{ TCP/IP, DNS }} | {{ Básico }} | {{ IDS/IPS }} |
| {{ ... }} | {{ ... }} | {{ ... }} | {{ ... }} |

---

## 🤝 Competências Comportamentais
Liste soft skills esperadas:  
- {{ Ex.: Comunicação clara }}  
- {{ Ex.: Trabalho em equipe }}  
- {{ Ex.: Pensamento crítico }}  
- {{ Ex.: Atenção a detalhes }}  

---

## 🧭 Matriz de Senioridade
Defina como o cargo evolui entre júnior, pleno e sênior.

| Aspecto | Júnior | Pleno | Sênior |
|---|---|---|---|
| Autonomia | {{ Execução guiada }} | {{ Autonomia moderada }} | {{ Referência técnica }} |
| Escopo | {{ Tarefas pontuais }} | {{ Fluxos completos }} | {{ Processos complexos }} |
| Liderança | {{ — }} | {{ Suporte a colegas }} | {{ Mentor, líder técnico }} |

---

## 🎓 Formação e Conhecimentos
Liste requisitos ou sugestões:  
- {{ Formação acadêmica sugerida ou experiência prática equivalente }}  
- {{ Conhecimentos básicos necessários (SO, redes, fundamentos de SI) }}  

---

## 📜 Certificações Recomendadas
Adicione certificações úteis para o cargo, sem exagerar.

| Área | Certificação | Nível | Fornecedor | Obrigatória? |
|---|---|---|---|:--:|
| {{ Blue/IR }} | {{ CompTIA Security+ }} | {{ Entry }} | {{ CompTIA }} | {{ Não }} |
| {{ IR }} | {{ GIAC GCIH }} | {{ Intermediário }} | {{ GIAC }} | {{ Opcional }} |

---

## 🔄 Interfaces
Liste as áreas/times com os quais este cargo interage.

| Área/Time | Interação típica | Tipo |
|---|---|---|
| {{ SOC N1 }} | {{ Escalonar alertas }} | R |
| {{ IR }} | {{ Apoiar resposta }} | C |
| {{ GRC }} | {{ Evidências de auditoria }} | I |

Legenda: **R** Responsável • **A** Aprovador • **C** Consultado • **I** Informado

---

## 📚 Referências Internas
Este cargo está classificado no **SecFrame BR** como parte da categoria *{{ Categoria }}* com subcategorias *{{ Subcategorias }}*.
