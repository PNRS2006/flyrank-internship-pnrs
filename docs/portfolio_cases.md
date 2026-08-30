# Portfolio Case — Urban Heat Risk Intelligence System

## Voice Card

**Direct, clear, practical, specific, honest, technical**

---

# Urban Heat Risk Intelligence System

## The Problem

Urban heat is not the same across an entire city. Different areas can have different levels of heat because of factors such as vegetation, built-up surfaces, roads, land-surface temperature, weather conditions, and population exposure.

A weather station can provide useful measurements for its location, but it does not show how heat conditions vary across smaller areas of a city.

I wanted to build a system that could combine these different signals and identify areas where urban heat risk is higher, so that those areas could be investigated and prioritized for possible intervention.

## What I Did

I framed the problem as an **ML classification task** combined with GIS-based spatial analysis.

The planned system represents the study area using **500 m × 500 m spatial grid cells**. Each cell can be described using environmental, geographical, urban-form, and exposure-related features such as temperature, humidity, land-surface temperature, vegetation indicators, built-up fraction, road density, population density, and elevation.

The model is intended to classify each grid cell into five heat-risk categories:

* Very Low
* Low
* Moderate
* High
* Very High

I chose classification because the final output needs to be understandable on a map and useful for prioritizing locations rather than producing only a single numerical prediction.

I also decided that the model should be compared with a simple rule-based baseline. This prevents me from assuming that machine learning is automatically better just because the problem uses ML.

For evaluation, I plan to focus on recall for the High and Very High risk classes, along with macro F1-score, precision, recall, and a confusion matrix.

## What Came of It

The project has moved from a broad idea into a defined ML and GIS problem.

I now have a clear unit of analysis, target direction, initial feature set, evaluation approach, and system architecture. The current work is focused on building the real spatial dataset and testing whether the proposed ML approach provides useful improvement over a transparent baseline.

The intended outcome is a spatial heat-risk map that can help identify areas that deserve closer assessment or possible cooling and adaptation interventions.

I am treating the system as **decision support**, not as an official heat-health warning system.

---

# Bio

I'm a Computer Science and Data Science student interested in building practical systems with machine learning, data, and software.

I like taking real-world problems that involve messy data and turning them into systems that can be tested, explained, and used. My current work focuses on machine learning, geospatial analysis, data visualization, full-stack development, and AI-powered applications.

---

# Contact / CTA

## Let's connect

Interested in the work? **Explore the project or get in touch.**

---

# Before / After

## Generic AI Version

> I developed an innovative AI-powered geospatial solution that leverages machine learning and multiple data sources to provide actionable insights into urban heat risk.

## My Edited Version

> I'm building a system that maps where urban heat risk is concentrated by combining weather, satellite, built-environment, and population data on a common city grid.

## Why I Changed It

The edited version describes what I am actually building instead of using broad claims. It removes phrases such as "innovative," "leverages," and "actionable insights" and focuses on the data, spatial structure, and intended output.
