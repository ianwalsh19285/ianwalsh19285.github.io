---
layout: page
---

<div class="project-shell">

<div class="project-hero">
  <h1>Prague Metro Analytics Pipeline</h1>
  <p class="project-subtitle">Advanced data engineering project</p>
</div>

<img class="project-image" src="/assets/img/projects/milestone_5.png" alt="Wait time dashboard">

<div class="project-copy">
  <p>
    This three-month project focused on building and extending a realistic analytics pipeline around a simulated Prague metro system. Working in a team-based course environment, I extracted and integrated data from PostgreSQL, MongoDB, Neo4j, and Kafka-based event streams, then moved that data through an end-to-end workflow using S3-style object storage, Airflow DAGs, a PostgreSQL warehouse, and dbt dimensional models. The deliverables for this project consisted of five milestones which each required us to answer important questions about the metro system with a complete dashboard.
  </p>

  <h2>What I built</h2>
  <ul>
    <li>An end-to-end pipeline that ingested metro data from multiple source systems, including a relational database, a document database, a graph database, and event-driven Kafka feeds.</li>
    <li>Snapshot-based ingestion workflows that stored data source extracts in S3-compatible object storage before loading them into a PostgreSQL analytics warehouse.</li>
    <li>Airflow DAGs to facilitate ingestion, warehouse loading, and milestone-specific analytics.</li>
    <li>Dimensional models in dbt to support milestone analysis, including facts and dimensions for line-level demand, station-level demand, ride durations, adjacent-station segment traffic, and wait times.</li>
    <li>Dashboard workflows in Grafana that turned warehouse outputs into milestone-specific visual analysis for decision-making and project evaluation.</li>
    <li>A development workflow built around SSH remotes, Docker, SQL, Python, DuckDB, JSON, Parquet, and documentation practices to support project handoffs.</li>
  </ul>

  <h2>Key outcomes</h2>
  <ul>
    <li>Built a reusable multi-source data pipeline that connected transactional, document, graph, and streaming data into one analytical system.</li>
    <li>Delivered five milestone dashboards, each centered on a distinct operational question.</li>
    <li>Strengthened practical experience with modern data engineering patterns, including object-storage snapshots, orchestrated warehouse loading, dbt-based transformation, lineage-aware documentation, and dashboard delivery.</li>
    <li>Worked in a realistic collaborative setting where pipeline documentation, maintainability, and handoff quality mattered because teams inherited and extended one another’s work over the semester.</li>
  </ul>
</div>

</div>