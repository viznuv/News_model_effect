# News_model_effect
News Model Effect is a Python-based simulation tool designed to analyze how both positive and negative news impact a brand over time across various channels (e.g., social media and TV).
# News Model Effect

**Repository:** [viznuv/News_model_effect](https://github.com/viznuv/News_model_effect)

## Overview

*News Model Effect* is a Python-based simulation tool designed to analyze how both positive and negative news impact a brand over time across various channels (e.g., social media and TV). The model leverages concepts from marketing mix modeling—such as adstock (with Weibull decay), lag effects, and saturation (via the Hill function)—to simulate how news exposures accumulate and affect a brand's base value dynamically.

## Features

- **Multi-Channel Simulation:**  
  Model the impact of news across multiple channels (e.g., Twitter, Facebook, TV) with channel-specific parameters.

- **Dual News Streams:**  
  Simulate both **positive** and **negative** news exposures. Positive news increases the brand value, while negative news decreases it.

- **Adstock Effect (Weibull Decay):**  
  Incorporates a decaying memory effect where past news events influence the current period with diminishing weight.

- **Lag Effect:**  
  Introduces a delay between the news exposure and its effect on brand perception.

- **Saturation Effect (Hill Function):**  
  Models the diminishing incremental impact of high exposure levels.

- **Dynamic Brand Value Update:**  
  Continuously updates the base brand value over time by accumulating the net effect (positive minus negative) from all channels.

## Repository Structure

## Getting Started

### Prerequisites

- **Python:** Version 3.6 or higher.
- **Pip:** For managing Python packages.
- *(Optional)* A virtual environment for project isolation.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/viznuv/News_model_effect.git
   cd News_model_effect

