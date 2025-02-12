# LEA 3.5 (Language Enhanced Anki Template)

A modern, feature-rich Anki template designed for language learning, with special support for Chinese and English.

## Configuration

Configuration du paquet :

Tous les paquets comportent des intitulés de champs suivant ce format :

<table>
   <thead>
      <tr>
         <th>Nom de champ</th>
         <th>Description</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td><b>mot_src</b></td>
         <td>Mots dans la langue d'origine</td>
      </tr>
      <tr>
         <td><b>mot_trad</b></td>
         <td>Mots dans la langue cible</td>
      </tr>
      <tr>
         <td><b>image</b></td>
         <td>URL de l'image associée au mot (facultatif)</td>
      </tr>
      <tr>
         <td><b>exemple_src</b></td>
         <td>Exemple d'utilisation du mot dans la langue d'origine (facultatif)</td>
      </tr>
      <tr>
         <td><b>exemple_trad</b></td>
         <td>Exemple d'utilisation du mot dans la langue cible (facultatif [selon les cas]*)</td>
      </tr>
      <tr>
         <td><b>grammaire</b></td>
         <td>Catégories grammaticales du mot dans la langue d'origine (facultatif [selon les cas]*)</td>
      </tr>
      <tr>
         <td><b>source</b></td>
         <td>Contexte dans lequel le mot a été vu pour la première fois (facultatif)</td>
      </tr>
   </tbody>
</table>








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
