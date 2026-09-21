# Five-Day Work Plan

This document maps the project files to the five contributors and planned work days.

## Day 1 - Setup, Architecture, and Ingestion

Date: 2026-09-17

- Eshmaal: `config/data_generation_config.yaml` and project ignore rules.
- Ali: Python pipeline entry points and cleaning module structure.
- Hamza: Spark session and ingestion entry points in `spark_jobs/`.
- Farooq: Flask application entry point and base template.
- Zain: Global pytest configuration in `tests/python/conftest.py`.

## Day 2 - Data Modeling, Quality Checks, and UI Layout

Date: 2026-09-18

- Eshmaal: Relational schema in `database/schema.sql`.
- Ali: Python data-quality rules in `python_pipeline/cleaning/data_quality_check.py`.
- Hamza: Distributed validation schemas in `spark_jobs/schemas.py`.
- Farooq: Global dashboard styling in `static/css/styles.css`.
- Zain: Generator verification tests in `tests/python/test_generator.py`.

## Day 3 - Transformation, Processing, and Core Backend

Date: 2026-09-19

- Eshmaal: DineIQ data generators in `data_generator/`.
- Ali: Python cleaning and transformation logic.
- Hamza: Spark SQL processing entry points.
- Farooq: Pipeline API routes in `src/api/routes.py`.
- Zain: Cleaning verification tests in `tests/python/test_cleaning.py`.

## Day 4 - Analytics Models, System Engines, and UI Rendering

Date: 2026-09-20

- Eshmaal: Analytical processing in `python_pipeline/processing/`.
- Ali: Advanced analytics orchestration.
- Hamza: Spark ML model framework in `spark_jobs/mllib_models.py`.
- Farooq: Dashboard visualization code in `static/js/dashboard.js`.
- Zain: Advanced analytics tests.

## Day 5 - Integration, Auditing, and Verification

Date: 2026-09-21

- Eshmaal: Documentation, notebooks, requirements, and project guidance.
- Ali: Local processing outputs and processing tests.
- Hamza: Spark orchestration, reports, and setup script.
- Farooq: Backend scoring integration.
- Zain: Spark regression tests.

Each day has five commits, one for each contributor. The Git history is the authoritative record of the files included in each commit.