# interactions directory

the interactions directory is designed to store, organize, and analyze insights gained from interacting with llms and specific personas. all files in this directory follow standardized naming conventions for easy organization and searchability.

## structure

- **interaction_logs/**: stores individual interaction logs, named by date and following the format `YYYY-MM-DD_interaction.md`. each file contains details of a specific interaction, allowing for chronological tracking.
  
- **insights_summary.md**: files summarizing recurring patterns, named by date and topic as `YYYY-MM-DD_insights_topic.md`. these files capture high-level insights and trends for future reference.

- **reflections.md**: files for personal reflections on interactions, named by date and topic as `YYYY-MM-DD_reflections_topic.md`. these reflections include subjective notes on interaction effectiveness, needed adjustments, and personal observations.

## directory structure

```markdown
interactions_directory/
│
├── interaction_logs/                     
│   ├── 2024-11-14_interaction.md         # example log file with date-based naming
│   ├── 2024-11-15_interaction.md         
│   └── [other interactions by date]
│
├── insights_summary/
│   ├── 2024-11-14_insights_persona.md    # example insights file by date and topic
│   ├── 2024-11-15_insights_projects.md   
│   └── [other insights files]
│
└── reflections/
    ├── 2024-11-14_reflections_persona.md # example reflections file by date and topic
    ├── 2024-11-15_reflections_methods.md 
    └── [other reflections files]
