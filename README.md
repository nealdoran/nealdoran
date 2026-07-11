## Dr. Neal A. Doran

**Geoscientist & Scientific Data Engineer**

I build production data pipelines, spatial databases, and applied AI/ML systems on massive scientific datasets. Backed by a PhD in geological sciences (micropaleontology) and two decades of hands-on domain experience with deep-time geological, paleontological, and spatial data, I bridge the gap between highly complex natural-science datasets and robust, verifiable computational engineering.

### Core Projects

- **Unified PostgreSQL/PostGIS Research Database** — Integrated global geology, stratigraphy, paleobiology, and a 25GB biology dataset on a single PostgreSQL/PostGIS instance. Migrated via pgloader with row-count verification (which caught a silent schema-target failure), custom non-standard projection resolved to a user-defined SRID, and strict model-vs-observation provenance quarantine. The geospatial layers are engineered to act as a common spatial key across domains. 👉 [View Project](https://github.com/nealdoran/Global-surface-geology-by-era)

- **Global Geology PostGIS Analysis** — A PostgreSQL/PostGIS spatial database integrating USGS World Geology and State Geologic Map Compilation datasets (148.3M km² of mapped geology), using spatial SQL to compute continental-scale geologic surface exposure by period. 👉 [View Project](https://github.com/nealdoran/global-geology-postgis)

- **Geostatistical Depositional-Environment Pipeline** — An uncertainty-quantified kriging pipeline (reliability-weighted, declustered ordinary kriging via PyKrige / scikit-gstat) that estimates marine-vs-terrestrial depositional probability from integrated fossil-occurrence and stratigraphic data. Its uncertainty layer desaturates where data is sparse, making confidence visible rather than assumed. Reproducible method demonstration; full analysis in preparation for peer review. 👉 [View Project](https://github.com/nealdoran/cenozoic-env-kriging)

- **Spatial Biodiversity Gap Audit Platform** — An automated ETL pipeline and live analytical dashboard cross-auditing global IUCN Red List conservation data against a 26-million-record GBIF occurrence dataset. 👉 [Launch Deployed App](https://nealdoran-biodiversity-gap-audit.streamlit.app/)

- **Semantic Socratic Tutor** — A retrieval-augmented generation (RAG) system grounded in a specialized scientific corpus, using all-MiniLM-L6-v2 embeddings, NumPy cosine-similarity retrieval, and the Anthropic Claude API. 👉 [Launch Deployed App](https://socratic-tutor-ascznqxqjn6mrpzqc6gopp.streamlit.app/)

### Technical Stack

- **Languages & Databases:** Python, SQL, PostgreSQL, PostGIS, SQLite, R
- **Geospatial & Geostatistics:** Spatial SQL, PostGIS, GeoPandas, kriging (PyKrige, scikit-gstat), uncertainty quantification, spatial indexing, equal-area projection, custom SRID/projection handling
- **Data Engineering:** ETL pipelines (pgloader), database normalization and migration, large-scale ingestion, row-count verification, model-vs-observation provenance discipline
- **AI/ML & NLP:** Retrieval-Augmented Generation (RAG), vector embeddings, semantic search, LLM API integration
- **Deployment & UI:** Streamlit, Streamlit Cloud, interactive dashboards

---

*Professor of Biology, Bryan College · PhD Geoscientist building the tools that turn complex scientific data into rigorous, queryable systems.*
