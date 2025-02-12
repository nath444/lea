# LEA 3.5 (Language Enhanced Anki Template)

A modern, feature-rich Anki template designed for language learning, with special support for Chinese and English.

## Features

### Universal Features [U]
- 🌙 Dark mode support
- 🔄 Interactive example toggles (show/hide translations)
- 🎯 Word type badges (Adjective, Verb, Noun, etc.)
- 🌍 Country and region flags support
- 🔊 Text-to-Speech for words and examples
- 📝 Grammar categories
- 💾 Local storage for user preferences

### Chinese-Specific Features [ZH]
- 🀄 Pinyin display for words and examples
- 📚 Chinese radicals support
- 🈺 Character decomposition
- 🗣️ Automatic pinyin generation

### Card Structure
1. **Front Side**
   - Main word/character
   - Word type badge
   - Grammar categories
   - Region/Country flags

2. **Back Side**
   - Translations with regional variants
   - Example sentences with:
     - Pinyin (for Chinese)
     - Translations
     - Toggle buttons for visibility
   - Synonyms list
   - Additional information in collapsible sections

## Usage

### Language Tags
Use these tags at the beginning of your cards:
- `[ZH]` - Chinese cards
- `[EN]` - English cards

### Region Codes
Add region codes before words to display regional flags:
- `001` - North America
- `002` - South America
- `003` - Europe
- `004` - Africa
- `005` - Asia

Example: `001 FR word` displays North America and French flags.

### Word Types
Available word type badges:
- ADJ. - Adjectives
- ADV. - Adverbs
- DIV. - Miscellaneous
- EXP. - Expressions
- NOM - Nouns
- VERBE - Verbs

## Dependencies
- Bootstrap 5.3.3
- Bootstrap Icons
- CNChar (for Chinese character handling)
- PapaParse
- Flag Icons CSS

## Installation
1. Copy the template files to your Anki collection
2. Create a new note type using these templates
3. Import the required CSS and JavaScript files

## Card Format
```
Front: [Language Tag] Word
Back: Translation [Details]
Examples: Original;Translation
Grammar: Category1;Category2
```

## Customization
- Edit `style.css` for visual customization
- Modify `front.php` and `back.php` for template changes
- Adjust JavaScript functions for behavior modifications

## Browser Compatibility
- Works with modern browsers supporting ES6
- Requires localStorage for saving preferences
- Needs internet connection for CDN resources

## Version
Current Version: 3.5 (Beta) - 2025
