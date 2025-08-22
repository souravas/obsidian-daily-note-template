# Obsidian Daily Note Templates

A complete structured journal template system for Obsidian featuring daily, weekly, monthly, quarterly, and yearly notes with anti-goals, reflection prompts, and seamless navigation.

## 🎯 Features

- **Complete Periodic Note System**: Daily, weekly, monthly, quarterly, and yearly templates
- **Anti-Goals Planning**: Focus on what NOT to do across all time periods
- **Structured Reflections**: Thoughtful prompts for growth and learning
- **Seamless Navigation**: Links between periods and time-based navigation
- **Cursor Positioning**: Templates open with cursor at the most important section
- **Hierarchical Organization**: Clear folder structure for all note types

## 📋 Template Structure

### Daily Notes
- One Big Thing (outcome-focused goal)
- Task management
- Structured reflection with productivity, learning, and gratitude prompts
- Navigation to previous/next day

### Weekly Notes
- Weekly focus areas with anti-goals
- Pattern recognition and lessons learned
- Navigation between weeks

### Monthly Notes  
- Monthly goals with anti-goals
- Assumption challenging and decision tracking
- Navigation between months

### Quarterly Notes
- Strategic objectives with anti-goals
- Strategy evaluation and stop/start/continue framework
- Navigation between quarters

### Yearly Notes
- Themes, goals, and anti-goals
- Annual review with major accomplishments and learnings
- Navigation between years

## 🚀 Setup

### Prerequisites

Install these Obsidian community plugins:
- **[Templater](https://github.com/SilentVoid13/Templater)** - Required for template functionality
- **[Periodic Notes](https://github.com/liamcain/obsidian-periodic-notes)** - Required for periodic note management

### Installation

1. Clone or download this repository
2. Copy the template files to your vault's `Templates` folder
3. Create the journal folder structure in your vault:
   ```
   Journal/
     ├── 01-Daily/
     ├── 02-Weekly/
     ├── 03-Monthly/
     ├── 04-Quarterly/
     └── 05-Yearly/
   Templates/
   ```

### Plugin Configuration

#### Periodic Notes Settings

Configure the Periodic Notes plugin with these settings:

```json
{
  "daily": {
    "format": "YYYY/MM-MMMM/YYYY-MM-DD-dddd",
    "folder": "Journal/01-Daily",
    "template": "Templates/Daily Note.md",
    "enabled": true
  },
  "weekly": {
    "format": "YYYY/MM-MMMM/YYYY-[W]ww",
    "template": "Templates/Weekly Note.md",
    "folder": "Journal/02-Weekly",
    "enabled": true
  },
  "monthly": {
    "format": "YYYY/YYYY-MM",
    "template": "Templates/Monthly Note.md",
    "folder": "Journal/03-Monthly",
    "enabled": true
  },
  "quarterly": {
    "format": "YYYY-[Q]Q",
    "template": "Templates/Quarterly Note.md",
    "folder": "Journal/04-Quarterly",
    "enabled": true
  },
  "yearly": {
    "format": "YYYY",
    "template": "Templates/Yearly Note.md",
    "folder": "Journal/05-Yearly",
    "enabled": true
  }
}
```

#### Templater Settings

1. Enable Templater plugin
2. Set template folder to `Templates`
3. Enable automatic jump to cursor (recommended)

## 📁 Folder Structure

```
your-vault/
├── Journal/                     # All periodic notes
│   ├── 01-Daily/               # Daily notes organized by year/month
│   │   └── 2025/
│   │       └── 08-August/
│   │           ├── 2025-08-22-Thursday.md
│   │           └── 2025-08-23-Friday.md
│   ├── 02-Weekly/              # Weekly notes organized by year/month
│   │   └── 2025/
│   │       └── 08-August/
│   │           └── 2025-W34.md
│   ├── 03-Monthly/             # Monthly notes organized by year
│   │   └── 2025/
│   │       └── 2025-08.md
│   ├── 04-Quarterly/           # Quarterly notes
│   │   └── 2025-Q3.md
│   └── 05-Yearly/              # Yearly notes
│       └── 2025.md
└── Templates/                   # Template files
    ├── Daily Note.md
    ├── Weekly Note.md
    ├── Monthly Note.md
    ├── Quarterly Note.md
    └── Yearly Note.md
```

## 🎨 Customization

Feel free to modify the templates to match your workflow:

- **Adjust sections**: Add, remove, or modify template sections
- **Change emojis**: Update emojis to match your preference
- **Modify prompts**: Customize reflection questions and prompts
- **Update navigation**: Adjust period links and navigation structure

## 🏷️ Tags

All notes are automatically tagged with hierarchical tags:
- `journal/daily`
- `journal/weekly`
- `journal/monthly`
- `journal/quarterly`
- `journal/yearly`

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues, suggestions, or pull requests to improve these templates.

## 📄 License

This project is released under the MIT License. Feel free to use, modify, and distribute these templates.