# 🌳 Áreas Verdes de São Paulo

Este projeto apresenta um **mapa interativo das áreas verdes da cidade de São Paulo**, integrando dados abertos do overpass turbo (https://overpass-turbo.eu/).  

O objetivo é explorar como parques, praças, florestas urbanas e outras áreas verdes estão distribuídas no município, permitindo análises de **acessibilidade urbana** e **qualidade de vida**.

---

## ⚙️ Funcionalidades
- Visualização interativa em navegador (HTML + Leaflet.js).  
- Camadas de:
  - **Parques públicos** (leisure=park)  
  - **Outras áreas verdes** (forest, grass, meadow, garden, protected_area)  
  - **Bairros/distritos** (GeoSampa)  
- Possibilidade de expandir para análises como:
  - Área verde por habitante (per capita)  
  - Desigualdade socioambiental  
  - Acessibilidade por transporte público e ciclovias  

---

## 📂 Estrutura do Repositório
/data → arquivos GeoJSON (parques, áreas verdes)
/maps → mapa interativo pronto em HTML
README.md → documentação do projeto

---

## 🌐 Acesse o mapa
🔗 
---

## 📊 Dados utilizados
- **OpenStreetMap** (via Overpass Turbo) → parques e áreas verdes  

---

## 🛠️ Tecnologias
- [Leaflet.js](https://leafletjs.com/) → visualização em mapa  
- [Overpass Turbo](https://overpass-turbo.eu/) → coleta de dados do OSM  

---

## 📌 Próximos Passos
- Calcular **m² de área verde por habitante** em cada distrito.  
- Comparar áreas verdes com dados de **vulnerabilidade social**.  
- Incluir camadas de **mobilidade urbana** (metrô, ônibus, ciclovias).  

