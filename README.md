# Apra PD 2025 - R Workshop

This repository contains materials for an R workshop focused on advanced reporting and presentation techniques using R Markdown, the `targets` package, and PowerPoint integration.

## Workshop Overview

Learn to create reproducible reports and presentations using modern R tools and workflows. This workshop demonstrates practical applications of R for data analysis, visualization, and automated report generation.


## Repository Structure

```
apra_pd_2025_r/
├── 00_install_pkgs.R                  # Package installation and dependency management
├── 01_introduction_agenda.Rmd         # Workshop and Rmarkdown introduction, agenda, and presenter bio
├── 02_demo_rmarkdown.Rmd             # Basic R Markdown demonstration
├── 03_simple_analysis.Rmd            # Palmer Penguins data analysis with commented sections
├── 04_parameterized_analysis.Rmd     # Parameterized reporting with species filtering
├── 05_powerpoint_officer.R           # Basic PowerPoint generation with officer
├── 06_custom_powerpoint_officer.R    # Advanced PowerPoint with custom Canva templates
├── 07_genai_analysis.R               # GenAI integration with Anthropic Claude
├── _targets.R                        # Targets workflow configuration
├── target_functions.R                # Helper functions for targets pipeline
```

## Workshop Agenda

1. **Introduction and Setup** (`01_introduction_agenda.Rmd`, `00_install_pkgs.R`)
   - Presenter introduction and LinkedIn QR code
   - Package installation with dependency management
   - Workshop objectives and scope

2. **R Markdown Fundamentals** (`02_demo_rmarkdown.Rmd`)
   - Document structure and YAML headers
   - Code chunks and output formatting
   - Multi-format output (HTML, PDF)

3. **Data Analysis Workflow** (`03_simple_analysis.Rmd`)
   - Palmer Penguins dataset exploration
   - Data visualization with ggplot2 and viridis colors
   - Commented code sections for presentation flexibility

4. **Parameterized Reporting** (`04_parameterized_analysis.Rmd`)
   - Species-specific analysis with parameters
   - Dynamic filtering and model building
   - Automated table generation with gt and gtsummary
   - Island-specific regression models

5. **Targets Package Pipeline** (`_targets.R`, `target_functions.R`)
   - Reproducible data pipelines
   - Function-based workflow design
   - Dependency management and caching

6. **PowerPoint Automation** (`05_powerpoint_officer.R`, `06_custom_powerpoint_officer.R`)
   - Basic PowerPoint generation with officer
   - Custom Canva template integration
   - Advanced chart styling and layout positioning
   - Automated slide population with data insights

7. **GenAI Integration** (`07_genai_analysis.R`)
   - Anthropic Claude API integration via ellmer
   - Structured data extraction and analysis
   - AI-powered insights generation
   - Automated content creation workflows

## Prerequisites

- Basic R programming knowledge
- Familiarity with data manipulation and visualization
- RStudio or similar IDE installed

## Installation

1. Clone or download this repository
2. Open the R project file: `apra_pd_2025_r.Rproj`
3. Run the setup script to install required packages:

```r
source("00_install_pkgs.R")
```

## Key Dependencies

- **Core Packages**: `tidyverse`, `rmarkdown`, `targets`
- **Data & Analysis**: `palmerpenguins`, `summarytools`, `e1071`, `dplyr`, `readr`
- **Visualization**: `ggplot2`, `ggthemes`, `viridis`, `scales`
- **Tables & Reporting**: `gt`, `gtsummary`, `flextable`
- **PowerPoint Generation**: `officer`
- **AI Integration**: `openai`, `ellmer`
- **Utilities**: `qrcode`, `RJSONIO`

## Getting Started

1. **Setup Environment**: Run `source("00_install_pkgs.R")` to install all dependencies
2. **Explore Introduction**: Open `01_introduction_agenda.Rmd` for workshop overview
3. **Learn R Markdown**: Start with `02_demo_rmarkdown.Rmd`
4. **Simple Analysis**: Review `03_simple_analysis.Rmd` with Palmer Penguins data
5. **Parameterized Reports**: Experiment with `04_parameterized_analysis.Rmd`
6. **Build Targets Pipeline**: Execute `targets::tar_make()` to run the workflow
7. **Generate PowerPoint**: Run `05_powerpoint_officer.R` and `06_custom_powerpoint_officer.R`
8. **AI Integration**: Explore `07_genai_analysis.R` for GenAI workflows

## File Details

### Core Analysis Files
- **`03_simple_analysis.Rmd`**: Demonstrates Palmer Penguins analysis with toggleable code sections using commented blocks for presentation flexibility
- **`04_parameterized_analysis.Rmd`**: Shows parameterized reporting with species filtering, dynamic model building, and island-specific analysis
- **`07_genai_analysis.R`**: Integrates Anthropic Claude for automated data insights with structured output formatting

### PowerPoint Generation
- **`05_powerpoint_officer.R`**: Basic officer usage with Titanic dataset, multiple slide layouts, and chart integration
- **`06_custom_powerpoint_officer.R`**: Advanced implementation with custom Canva templates, precise positioning, and enhanced styling

### Pipeline Management  
- **`_targets.R`**: Targets pipeline configuration with data loading and processing steps
- **`target_functions.R`**: Modular functions for data preparation, modeling, and visualization


## What This Workshop Does NOT Cover

- Basic R syntax and programming fundamentals
- Detailed data manipulation techniques
- Quarto (focus is on R Markdown)
- LaTeX typesetting

## Resources

- **Data Science for Fundraising Book**: https://ds4fr.nandeshwar.info/
- **Author's Books on Amazon**: [Soar](https://www.amazon.com/Soar-Become-Extraordinary-Successful-Career-ebook/dp/B09ZKF8P61)

## License

This project is created for educational purposes. Please respect all data sources and third-party package licenses.

## Contact

For questions or feedback about this workshop:
- **LinkedIn**: [Ashutosh Nandeshwar](https://www.linkedin.com/in/ashutoshnandeshwar/)
- **Website**: [nandeshwar.info](https://nandeshwar.info)