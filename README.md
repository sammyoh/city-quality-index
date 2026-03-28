# City Quality Index

Baltimore-focused quality-of-life project for comparing parts of the city across affordability, safety, amenities, green space, and other everyday livability signals.

This repository is currently scoped to the project definition and source planning layer, not the ingestion layer. Raw data pulls, ingestion scripts, and generated datasets are intentionally excluded from this repo.

## Project direction

The goal is to build a neighborhood intelligence product that helps answer questions like:
- where is Baltimore most affordable relative to income
- which parts of the city have the strongest park and amenity access
- how do safety, food access, and things-to-do vary across the city
- which areas look strongest for different lifestyles and priorities

## Focus areas

- cost of living
- rent and housing context
- crime and public safety
- restaurants and things to do
- grocery access
- parks and green space
- education and family-friendliness

## Source planning

The current source inventory lives in [docs/source_catalog.md](docs/source_catalog.md).

That catalog focuses on:
- official Baltimore and federal data sources where possible
- practical open-data sources for amenities and livability signals
- notes on which sources are easier or harder to automate

## Repository scope

Included here:
- project framing
- source planning
- future modeling and dashboard documentation

Excluded here:
- ingestion scripts
- raw and processed datasets
- local pipeline outputs
