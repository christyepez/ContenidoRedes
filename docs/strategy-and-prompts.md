# Strategy & Dual-Language Prompts for Codex

## Sprint 1: Multi-Source Ingestion

- **English (Token Optimized):**
  `Act as Cloud Data Engineer. Create a Node.js script fetcher.js to collect official RSS feeds from AWS Architecture Blog, Microsoft Azure, Google Cloud, Databricks Engineering, GitHub Trending, and LinkedIn Engineering. Filter out marketing content; extract only titles, URLs, and summaries related to cloud architecture, data engineering, and machine learning. Save normalized output to raw_tech_articles.json.`
- **Español (Referencia):**
  `Actúa como Cloud Data Engineer. Crea un script fetcher.js en Node.js que recoja feeds oficiales de AWS Architecture, Microsoft Azure, Google Cloud, Databricks, GitHub Trending y LinkedIn Engineering. Filtra el marketing; extrae solo títulos, URLs y resúmenes de arquitectura cloud, ingeniería de datos y ML. Guarda la salida en raw_tech_articles.json.`

## Sprint 2: Editorial Engine & Visual Diagrams (Mermaid)

- **English (Token Optimized):**
  `Act as Enterprise Architect. Write generator.js to process raw_tech_articles.json using OpenAI GPT-4o. Prompt the model to write a direct, highly technical post (no fluff) containing: 1. Solved architecture/data problem. 2. Implemented technical solution with code snippet. 3. A Mermaid.js diagram block for automatic visual explanation. 4. Organic affiliate link injection from affiliates.json. Save markdown output to /drafts.`
- **Español (Referencia):**
  `Actúa como Enterprise Architect. Escribe generator.js para procesar raw_tech_articles.json usando OpenAI GPT-4o. Pide al modelo redactar un post directo y técnico (sin rodeos) que incluya: 1. Problema de arquitectura o datos resuelto. 2. Solución técnica con snippet de código. 3. Diagrama Mermaid.js explicativo. 4. Inyección de afiliado desde affiliates.json. Guarda en /drafts.`

## Sprint 3: Automated Publication & Cron Jobs

- **English (Token Optimized):**
  `Act as DevOps Specialist. Create publisher.js to automatically send markdown files from /drafts (including rendered Mermaid diagrams/visual text) to LinkedIn and X via official APIs. Provide exact instructions to set up a Linux/macOS Cron Job to run the full pipeline weekly in autopilot mode.`
- **Español (Referencia):**
  `Actúa como DevOps Specialist. Crea publisher.js para enviar automáticamente archivos .md de /drafts (con diagramas Mermaid) a LinkedIn y X vía API. Proporciona instrucciones exactas para configurar un Cron Job en Linux/macOS y ejecutar el pipeline semanalmente en piloto automático.`
