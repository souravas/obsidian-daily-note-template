# Obsidian Journal System

A comprehensive journal system for Obsidian using the [Obsidian Journals plugin](https://github.com/srg-kostyrko/obsidian-journal) for advanced periodic note management with anti-goals, structured reflections, and seamless navigation.

## 🎯 Features

- **Advanced Journal Management**: Powered by the Obsidian Journals plugin for superior organization
- **Complete Periodic Note System**: Daily, weekly, monthly, quarterly, and yearly journals
- **Anti-Goals Planning**: Focus on what NOT to do across all time periods
- **Structured Reflections**: Thoughtful prompts for growth and learning
- **Advanced Navigation**: Enhanced navigation with journal shelves and custom periods
- **Flexible Organization**: Hierarchical folder structure with customizable templates

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
- **[Obsidian Journals](https://github.com/srg-kostyrko/obsidian-journal)** - Advanced journal management system
- **[Templater](https://github.com/SilentVoid13/Templater)** - Required for template functionality (optional but recommended)

### Installation

1. Install the Obsidian Journals plugin from the Community Plugins store
2. Copy the template files to your vault's `Templates` folder (if using templates)
3. The journal folder structure will be created automatically by the plugin

### Plugin Configuration

#### Obsidian Journals Settings

Configure the Obsidian Journals plugin with these journal types:

**Daily Journal:**
- Type: Day
- Name Template: `{{date}}`
- Date Format: `YYYY-MM-DD`
- Folder: `10 - Journal/01 - Daily/{{date:YYYY}}/{{date:MM}} - {{date:MMM}}`
- Template: `99 - Templates/Daily Note.md`
- Auto-create: Disabled
- Navigation Block: Custom block showing day, date, relative date, week link, month link, year link

**Weekly Journal:**
- Type: Week
- Name Template: `{{date}}`
- Date Format: `YYYY-[W]w`
- Folder: `10 - Journal/02 - Weekly/{{date:YYYY}}`
- Template: `99 - Templates/Weekly Note.md`
- Auto-create: Disabled
- Navigation Block: Shows week number, relative date, month link, year link

**Monthly Journal:**
- Type: Month
- Name Template: `{{date}}`
- Date Format: `YYYY-MM`
- Folder: `10 - Journal/03 - Monthly/{{date:YYYY}}`
- Template: `99 - Templates/Monthly Note.md`
- Auto-create: Disabled
- Navigation Block: Shows month name, relative date, year link

**Quarterly Journal:**
- Type: Quarter
- Name Template: `{{date}}`
- Date Format: `YYYY-[Q]Q`
- Folder: `10 - Journal/04 - Quarterly/{{date:YYYY}}`
- Template: `99 - Templates/Quarterly Note.md`
- Auto-create: Disabled
- Navigation Block: Shows quarter, relative date, year link

**Yearly Journal:**
- Type: Year
- Name Template: `{{date}}`
- Date Format: `YYYY`
- Folder: `10 - Journal/05 - Yearly`
- Template: `99 - Templates/Yearly Note.md`
- Auto-create: Disabled
- Navigation Block: Shows year and relative date

#### Templater Settings (Optional)

If using templates:
1. Enable Templater plugin
2. Set template folder to `Templates`
3. Enable automatic jump to cursor (recommended)

## 📁 Current Folder Structure

```
10 - Journal/                    # Main journal directory
├── 01 - Daily/                 # Daily notes
│   └── 2025/
│       ├── 08 - Aug/
│       │   ├── 2025-08-27.md
│       │   ├── 2025-08-28.md
│       │   ├── 2025-08-29.md
│       │   ├── 2025-08-30.md
│       │   └── 2025-08-31.md
│       └── 09 - Sep/
│           └── 2025-09-01.md
├── 02 - Weekly/                # Weekly notes
│   └── 2025/
│       ├── 2025-W35.md
│       ├── 2025-W36.md
│       ├── 2025-W37.md
│       └── 2025-W38.md
├── 03 - Monthly/               # Monthly notes
│   └── 2025/
│       ├── 2025-08.md
│       ├── 2025-09.md
│       ├── 2025-10.md
│       └── 2025-11.md
├── 04 - Quarterly/             # Quarterly notes
│   ├── 2025/
│   │   ├── 2025-Q3.md
│   │   └── 2025-Q4.md
│   └── 2026/
│       └── 2026-Q1.md
└── 05 - Yearly/                # Yearly notes
    ├── 2025.md
    ├── 2026.md
    └── 2027.md
```

This structure is automatically managed by the Obsidian Journals plugin and provides:
- **Hierarchical Organization**: Clear separation by time period
- **Automatic Dating**: Consistent date formats across all journals
- **Flexible Scaling**: Easily accommodates future periods
- **Cross-Navigation**: Seamless linking between different time scales

## 🎨 Customization

The Obsidian Journals plugin offers extensive customization options:

### Journal Configuration
- **Custom Periods**: Create journals for sprints, financial quarters, or any custom duration
- **Multiple Journals**: Set up different journals for work, personal, projects, etc.
- **Flexible Templates**: Use template variables like `{{date}}`, `{{index}}` for dynamic content
- **Navigation Blocks**: Custom navigation elements between periods

### Template Customization
- **Adjust sections**: Add, remove, or modify template sections
- **Change emojis**: Update emojis to match your preference
- **Modify prompts**: Customize reflection questions and prompts
- **Update navigation**: Adjust period links and navigation structure

### Advanced Features
- **Visual Decorations**: Circle indicators show when notes exist
- **Cross-Navigation**: Automatic linking between different time periods
- **Command System**: Built-in commands for opening current/next/previous notes
- **Calendar Integration**: Enhanced calendar view with custom styling
- **Template Variables**: Dynamic content using `{{date}}`, `{{relative_date}}`, etc.
- **Custom Navigation Blocks**: Rich navigation elements within each journal type

### Available Commands
The plugin provides these commands for quick navigation:
- Open today's/weekly/monthly/quarterly/yearly note
- Open tomorrow's/next week/next month/next quarter/next year note
- Open yesterday's/last week/last month/last quarter/last year note

## 🏷️ Tags

The journal system uses hierarchical tags for organization:
- `journal/daily` - Daily journal entries
- `journal/weekly` - Weekly planning and review
- `journal/monthly` - Monthly goal setting and reflection
- `journal/quarterly` - Quarterly strategic planning
- `journal/yearly` - Annual themes and major goals

Tags can be configured in templates or added manually to notes for better organization and searching.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues, suggestions, or pull requests to improve these templates.

## 📄 License

This project is released under the MIT License. Feel free to use, modify, and distribute these templates.