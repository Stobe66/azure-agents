# azure-agents
# Azure Agents – AI Agent Framework (Azure Foundry)

Tämä repositorio sisältää rakenteen ja esimerkkitoteutuksia tekoälyagenteille, jotka on rakennettu Azure Foundry -ympäristöön. Rakenne tukee useiden agenttien kehitystä, workflowjen hallintaa, konfiguraatioita ja iteratiivista prompttisuunnittelua.

## 🚀 Ominaisuudet

- Modulaarinen agenttiarkkitehtuuri
- Azure Foundry -yhteensopivat workflow-määrittelyt
- Selkeä kansiorakenne tuotantokoodille, konfiguraatioille ja kokeiluille
- Notebookit prompttien ja mallien testaukseen
- Esimerkkisovellukset ja testit

---

## 📁 Rakenne

### `src/agents/`
Sisältää agenttien perusluokan ja yksittäiset agentit.

### `src/workflows/`
Azure Foundry -workflowjen JSON/YAML-määrittelyt.

### `src/utils/`
Yhteiset apufunktiot (lokitus, konfiguraatiot, API-kutsut).

### `configs/`
Agenttien asetukset ja ympäristömuuttujien template-tiedostot.

### `notebooks/`
Prompttisuunnittelu, mallien evaluointi ja kokeilut.

### `tests/`
Yksikkötestit agenttilogiikalle ja apufunktioille.

### `examples/`
Käyttöesimerkkejä ja demoja.

---

## ▶️ Käyttö

### Asennus
This is my default repository for my Azure Agents
