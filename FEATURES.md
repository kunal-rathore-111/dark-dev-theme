# Kunal Dark Dev Theme - Features & Details

## 🎨 Complete Color Palette

### Background Colors
- **Primary Background**: `#000000` - Pure black for deep contrast
- **Secondary Background**: `#040616` - Dark blue tint for UI elements
- **Editor Background**: `#000000` - Pure black editor surface
- **Sidebar Background**: `#000000` - Unified with editor
- **Status Bar Background**: `#040616` - Subtle differentiation

### Foreground Colors
- **Primary Foreground**: `#FFFFFF` - Crisp white text
- **Secondary Foreground**: `#c7d3f6` - Slightly muted for UI text
- **Inactive Foreground**: `#ffffff9a` - Dimmed for inactive elements

### Accent Colors
| Color | Hex | Usage |
|-------|-----|-------|
| **Pink** | `#f90086` | Keywords, control flow, important syntax |
| **Cyan** | `#54d4ff` | Functions, methods, parameters |
| **Bright Cyan** | `#00e5ff` | Variables, properties, brackets |
| **Yellow** | `#FFF900` | Strings, numbers, constants |
| **Purple** | `#7a6deef4` | Classes, types, interfaces |
| **Blue** | `#5a73be` | Links, peek views, focus states |
| **Green** | `#44B6FC` | Success states, terminal green |
| **Neon Green** | `#00FF41` | Active panel borders, highlights |

## 🖥️ UI Elements

### Editor
- Line highlighting: Transparent for minimal distraction
- Selection: `#043249` - Dark blue selection
- Cursor: `#ffffff` - White for maximum visibility
- Line numbers: `#ADD8E650` - Subtle gray
- Active line number: `#00d4ff` - Cyan highlight
- Bracket matching: `#5a73be30` - Blue tint with border

### Activity Bar
- Background: `#000000` - Pure black
- Foreground: `#e406c6e5` - Vibrant pink/magenta
- Badge background: `#85245edc` - Dark purple
- Border: `#03040e` - Almost invisible

### Sidebar
- Background: `#000000` - Unified with editor
- Foreground: `#c7d3f6` - Light blue-white
- Section headers: `#c8c6cf` - Subtle gray
- Selection: Various blue tints for focus states

### Status Bar
- Background: `#040616` - Dark blue
- Foreground: `#777777` - Muted gray
- Debugging background: `#f90086` - Pink for visibility
- Border: `#0a0a0a60` - Subtle separator

### Tabs
- Active background: `#000000` - Pure black
- Active border: `#f90086` - Pink indicator
- Inactive background: `#000000` - Same as active
- Hover background: `#19018534` - Subtle purple tint

### Terminal
- Background: `#000000` - Pure black
- Selection: `#212c496e` - Blue tint
- Cursor: `#ffffff` - White
- Border: `#39FF14` - Neon green
- ANSI Colors: Matching theme palette

## 🔤 Syntax Highlighting

### Token Color Assignments

#### Keywords & Control Flow
- Color: **Pink** (`#f90086`)
- Scopes: `keyword`, `storage.type`, `keyword.control`
- Examples: `if`, `else`, `for`, `while`, `function`, `class`, `return`

#### Functions & Methods
- Color: **Cyan** (`#54d4ff`)
- Scopes: `entity.name.function`, `support.function`
- Examples: Function declarations, method calls

#### Variables & Properties
- Color: **Bright Cyan** (`#00e5ff`)
- Scopes: `variable`, `variable.other`, `meta.object-literal.key`
- Examples: Variable names, object properties

#### Strings
- Color: **Yellow** (`#FFF900`)
- Scopes: `string`, `string.quoted`
- Examples: `"text"`, `'text'`, template literals

#### Numbers & Constants
- Color: **Yellow** (`#FFF900`)
- Scopes: `constant.numeric`, `constant.language`
- Examples: `123`, `true`, `false`, `null`

#### Classes & Types
- Color: **Purple** (`#7a6deef4`)
- Scopes: `entity.name.class`, `entity.name.type`, `support.type`
- Examples: Class names, interface names, type annotations

#### Comments
- Color: Muted gray (check theme file for exact value)
- Scopes: `comment`, `punctuation.definition.comment`
- Style: Can be italicized via settings

#### Operators & Punctuation
- Color: **Bright Cyan** (`#00e5ff`)
- Scopes: `keyword.operator`, `punctuation`
- Examples: `+`, `-`, `*`, `/`, `=`, `()`, `[]`, `{}`

## 🎯 Special Features

### Semantic Highlighting
- Enabled by default
- Provides enhanced token coloring for supported languages
- Particularly effective for TypeScript, Python with Pylance

### Git Integration
- Added files: `#1de4b2f8` - Teal/cyan
- Modified files: `#1d94e4` - Blue
- Deleted files: `#ee247855` - Red/pink tint
- Untracked files: `#5cfad8` - Bright cyan
- Ignored files: `#3a3a3a` - Dark gray
- Conflicting files: `#ff00d4` - Magenta

### Diff Editor
- Inserted text: `#00e1ff3a` - Cyan tint
- Removed text: `#ff196542` - Red/pink tint

### Peek Views
- Background: `#0d0f4b2d` - Dark blue tint
- Border: `#5a73be41` - Blue
- Title background: `#00aeff1a` - Cyan tint
- Match highlight: `#001068` - Dark blue

### Search & Find
- Find match: `#001068` - Dark blue
- Find match highlight: `#001068` - Same as match
- Range highlight: Transparent for minimal distraction

### Widgets & Suggestions
- Background: `#070316e5` - Very dark purple
- Border: `#0f0f0fce` - Almost black
- Selected item: `#0a47704d` - Blue tint
- Highlight: `#ff0080` - Bright pink

## 🌐 Language-Specific Optimizations

### JavaScript/TypeScript
- Clear distinction between keywords, functions, and variables
- Template literal support
- JSX/TSX element coloring

### Python
- Works beautifully with Pylance semantic highlighting
- Decorator support
- Type hint coloring

### HTML/CSS
- Tag names, attributes, and values clearly distinguished
- CSS property and value highlighting
- Class and ID selectors stand out

### Markdown
- Headers, lists, and code blocks clearly defined
- Link highlighting
- Emphasis and strong text

### JSON/YAML
- Keys and values distinctly colored
- String values in yellow
- Numbers and booleans highlighted

## 🔧 Customization Tips

### Enable Italic Comments
```json
{
  "editor.tokenColorCustomizations": {
    "[Kunal Dark Dev]": {
      "textMateRules": [
        {
          "scope": ["comment"],
          "settings": {
            "fontStyle": "italic"
          }
        }
      ]
    }
  }
}
```

### Adjust Background Darkness
```json
{
  "workbench.colorCustomizations": {
    "[Kunal Dark Dev]": {
      "editor.background": "#0a0a0a"
    }
  }
}
```

### Enhance Bracket Colorization
```json
{
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": "active"
}
```

## 📊 Comparison with Other Themes

### vs One Dark Pro
- Kunal Dark Dev uses pure black backgrounds instead of dark gray
- More vibrant accent colors (pink, cyan, yellow)
- Higher contrast for reduced eye strain

### vs Dracula
- Darker background (pure black vs purple-tinted)
- Different accent palette (cyan-focused vs purple-focused)
- More distinct function and variable colors

### vs Material Theme
- True black theme vs material's softer backgrounds
- Neon-inspired accents vs material's muted tones
- Stronger contrast ratios

## 🎨 Design Philosophy

1. **Maximum Readability**: Every color choice serves to enhance code comprehension
2. **Eye Strain Reduction**: Pure black backgrounds with high-contrast text
3. **Logical Color Association**: Similar syntax elements across languages share colors
4. **Visual Hierarchy**: Important code stands out naturally
5. **Minimal Distraction**: UI elements fade into background, code is the star
6. **Vibrant but Professional**: Colorful enough to be engaging, not distracting

## 🔍 Technical Details

- **Theme Type**: Dark
- **Semantic Highlighting**: Enabled
- **Token Colors**: 100+ custom scopes defined
- **UI Colors**: 70+ workbench colors customized
- **Supported Platforms**: All VS Code supported platforms
- **Minimum VS Code Version**: 1.87.0

## 📈 Future Roadmap

- [ ] Lighter variant for daytime coding
- [ ] Darker variant for ultra-dark preference
- [ ] Blue accent variant
- [ ] Green accent variant
- [ ] High contrast accessibility variant
- [ ] Language-specific refinements based on community feedback
- [ ] Custom icon theme to match color palette
