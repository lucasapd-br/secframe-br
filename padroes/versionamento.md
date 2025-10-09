# 📌 Padrão de Versionamento — OCA

## 1. Status atual
O projeto **ainda não possui versão oficial (1.0.0)**.  
As primeiras versões públicas serão lançadas como **pré-releases**:  
- `v0.x.y-alpha` → versões iniciais em construção.  
- `v0.x.y-beta` → versões mais estáveis, preparatórias para a `v1.0.0`.

---

## 2. Versão do Framework (repositório)
Seguiremos **SemVer (Semantic Versioning)**:

`vMAJOR.MINOR.PATCH`

- **MAJOR** → mudanças incompatíveis.  
- **MINOR** → adições compatíveis.  
- **PATCH** → ajustes e correções.  
- **Pré-release**: `-alpha.N`, `-beta.N`, `-rc.N`.

---

## 3. Versão por Documento
Cada arquivo `.md` pode ter no front-matter:
```yaml
---
doc_version: "0.1.0"
status: "draft"   # draft | review | stable | deprecated
last_updated: "2025-10-09"
---
```

---

## 4. Deprecação
- Antes de remover um cargo ou área, marcar como **deprecated**.  
- Remoções apenas em uma próxima **MAJOR**.

---

## 5. Histórico de mudanças
- Manter **CHANGELOG.md** (modelo Keep a Changelog).

---

## 6. Primeira versão oficial
- Ciclo: `alpha` → `beta` → `1.0.0`.
