# Career Strategy

> Strategic career development plan for advancing into data engineering and AI roles

This repository documents my structured approach to career advancement in data engineering and AI development, with a target timeline of April-October 2025.

## Project Overview

This project uses software engineering principles (Domain Driven Design, Test Driven Development, and Agile methodologies) to manage the career advancement process. The repository contains tools, documentation, and portfolio projects built to showcase my skills.

### Goals

- Systematically assess my current skills against data engineering & AI requirements
- Identify and close critical skill gaps through targeted learning
- Build a compelling portfolio demonstrating data engineering capabilities
- Streamline the job application process with automated tracking
- Successfully secure a data/AI role by October 2025

## Repository Structure

- **[assessments/](./assessments/)**: Tools and data for skills gap analysis
- **[job_tracker/](./job_tracker/)**: Automated system for job application management
- **[portfolio/](./portfolio/)**: Portfolio projects demonstrating relevant skills
- **[learning/](./learning/)**: Learning progress and resources
- **[docs/](./docs/)**: Documentation including sprint plans and career roadmap

## Transition Strategy

### Phase 1: Assessment (April-May)
- Collect and analyze job market data
- Identify critical skills and personal gap analysis
- Establish baseline measurements and goals

### Phase 2: Foundations & Learning (May-July)
- Focus on closing critical skill gaps
- Begin building portfolio projects
- Establish professional presence in data communities

### Phase 3: Portfolio Development (June-August)
- Complete and refine 3-5 portfolio projects
- Document projects professionally
- Develop case studies demonstrating problem-solving approach

### Phase 4: Active Job Search (August-October)
- Implement systematic job application process
- Conduct targeted networking
- Focus on interview preparation

## Agile Sprint Planning

This transition is managed in 2-week sprints, with clearly defined goals and retrospectives for each sprint. The current sprint details can be found in [docs/sprints/](./docs/sprints/).

## Technical Tools

This repository includes several custom-built tools to support the transition:

1. **Skills Assessment Tool**: Python-based system for analyzing job requirements and personal skill gaps
2. **Job Application Tracker**: Automated tracking and follow-up system
3. **Portfolio Projects**: Demonstrating relevant technical capabilities

## Development

This project uses modern Python development practices:
- `uv` for dependency management
- `pyproject.toml` for project configuration
- pytest for testing

To set up the development environment:
```bash
# Clone the repository
git clone https://github.com/yourusername/career-strategy.git
cd career-strategy

# Install uv if not already installed
# curl -fsSL https://install.uv.dev | sh

# Install dependencies
uv sync --all-extras --dev

# Run tests
uv run pytest