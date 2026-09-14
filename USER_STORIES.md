# Fleetspan — User stories

**Product:** [PRODUCT.md](./PRODUCT.md)


### Marketplace data scientist

- As a data scientist, I want to generate a city-dimension training set with Spark/SQL jobs, so that Cairo and emerging cities are not forced into one distribution.
- As a data scientist, I want to train with the library that fits the problem, so that the platform does not dictate CatBoost vs. TensorFlow dogma.
- As a data scientist, I want a shared ETA benchmark dataset, so that I can compete and collaborate on quality transparently.

### ML engineer / platform

- As an ML engineer, I want one real-time API that selects the right dimension model per request, so that booking services do not embed routing logic.
- As an ML engineer, I want one-click refresh of a city model, so that drift fixes ship in minutes, not days.
- As an ML engineer, I want Airflow-ready pipeline scaffolding for new projects, so that training is production-grade by default.

### Marketplace product manager

- As a product manager, I want city-level A/B of ETA models against cancellation and wait-time KPIs, so that rollouts are evidence-based.
- As a product manager, I want a health view of which dimensions are stale or drifting, so that ops can prioritize retrains.

### City ops / SRE

- As city ops, I want to onboard a new city dimension without a full platform project, so that market expansion is not blocked on ML plumbing.
- As an SRE, I want latency and error budgets on the ETA ML API, so that marketplace booking SLOs are protected.
- As a privacy officer, I want prediction-log retention limits on precise coordinates, so that we do not hoard location history without purpose.
- As a captain-experience lead, I want batch simulations of ETA changes before city-wide live traffic, so that we avoid surprising field behavior.
