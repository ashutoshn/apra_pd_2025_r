# Apra PD 2025 - R Workshop

This repository contains materials for an R workshop focused on advanced reporting and presentation techniques using R Markdown, the `targets` package, and PowerPoint integration.

## Workshop Overview

Learn to create reproducible reports and presentations using modern R tools and workflows. This workshop demonstrates practical applications of R for data analysis, visualization, and automated report generation.


## Repository Structure

```
apra_pd_2025_r/
├── 00_install_pkgs.R              # Package installation and setup
├── 000_introduction_agenda.Rmd    # Workshop introduction and agenda
├── 01_demo_rmarkdown.Rmd         # Basic R Markdown demonstration
├── 02_simple_analysis.Rmd        # Simple data analysis example
├── 03_parameterized_analysis.Rmd # Parameterized reporting
├── 004_powerpoint_officer.R      # PowerPoint generation with officer
├── 005_custom_powerpoint_officer.R # Custom PowerPoint templates
├── 006_genai_analysis.R          # GenAI integration examples
├── _targets.R                    # Targets workflow configuration
├── target_functions.R            # Custom functions for targets pipeline
```

## Workshop Agenda

1. **Basic Introduction to R Markdown**
   - Document structure and syntax
   - Code chunks and output formatting
   - HTML, PDF, and presentation outputs

2. **Simple Data Analysis**
   - Exploratory data analysis
   - Data visualization with ggplot2
   - Summary statistics and tables

3. **Parameterized Analysis**
   - Creating flexible, reusable reports
   - Parameter-driven analysis workflows
   - Automated report generation

4. **Targets Package Workflow**
   - Reproducible data pipelines
   - Dependency management
   - Caching and performance optimization

5. **Advanced PowerPoint with Officer**
   - Programmatic PowerPoint creation
   - Custom templates and branding
   - Automated slide generation

6. **GenAI Integration**
   - AI-powered analysis and insights
   - Automated content generation
   - Modern AI workflows in R

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

- **Core**: `tidyverse`, `rmarkdown`, `targets`
- **Analysis**: `e1071`, `palmerpenguins`, `summarytools`
- **Visualization**: `ggplot2`, `ggthemes`, `viridis`, `scales`
- **Tables**: `gt`, `gtsummary`, `flextable`
- **Presentations**: `officer` (for PowerPoint generation)
- **AI Integration**: `openai`, `ellmer`

## Getting Started

1. **Explore Basic R Markdown**: Start with `01_demo_rmarkdown.Rmd`
2. **Run Simple Analysis**: Review `02_simple_analysis.Rmd`
3. **Try Parameterized Reports**: Experiment with `03_parameterized_analysis.Rmd`
4. **Build Targets Pipeline**: Execute `targets::tar_make()` to run the workflow
5. **Generate PowerPoint**: Run scripts in `004_powerpoint_officer.R`


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