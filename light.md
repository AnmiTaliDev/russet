# Russet Light Theme

Detailed specification of the light version of the autumn-inspired Russet color theme for web interfaces.

## Color Palette

### Background Colors

**Primary Background**: `#fefefe`  
Pure white with a barely noticeable warm tint. Creates a sense of cleanliness and spaciousness, perfect for the main application background.

**Secondary Background**: `#f8f6f4`  
Very light creamy shade for cards, panels, and other second-level surfaces. Provides gentle separation without harsh contrasts.

**Tertiary Background**: `#f2efec`  
More saturated cream-beige for elevated elements: modal windows, dropdown menus, focus areas.

**Hover Background**: `#ede8e4`  
Applied to interactive elements in hover state. Creates a subtle highlighting effect.

### Text Colors

**Primary Text**: `#2a2522`  
Deep dark brown, almost black with warm undertones. Ensures excellent readability and matches the autumn theme.

**Secondary Text**: `#5a544e`  
Medium brown for captions, metadata, and less important information. Creates visual hierarchy without losing readability.

**Tertiary Text**: `#8a8078`  
Light gray-brown for auxiliary text, timestamps, hints.

**Disabled Text**: `#afa59d`  
Used for disabled controls and inactive content.

### Accent Colors

**Primary Accent**: `#cd853f`  
Rich golden-orange for buttons, links, and other active elements. Bright but not aggressive, perfectly complements the light background.

**Secondary Accent**: `#a0522d`  
Dark reddish-brown for secondary actions and additional controls.

**Tertiary Accent**: `#daa520`  
Golden for highlighting important elements and special states.

**Copper Accent**: `#b87333`  
Copper-brown for unique interface elements and special highlights.

### Semantic Colors

**Success**: `#6b8e23`  
Natural green for successful operations and positive states.

**Warning**: `#ff8c00`  
Bright orange for warnings and important notifications.

**Error**: `#d2691e`  
Terracotta for errors and critical states.

**Info**: `#4682b4`  
Steel blue for informational messages.

## Typography

### Heading Hierarchy

**H1 - Main Heading**
- Size: 2.5rem (40px)
- Weight: 700 (Bold)
- Line height: 1.2
- Color: primary text
- Usage: page titles, section names

**H2 - Section Heading**
- Size: 2rem (32px)
- Weight: 600 (Semi-bold)
- Line height: 1.3
- Color: primary text
- Usage: large content block headings

**H3 - Subheading**
- Size: 1.5rem (24px)
- Weight: 600 (Semi-bold)
- Line height: 1.4
- Color: primary text
- Usage: card headings, subsections

**H4 - Small Heading**
- Size: 1.25rem (20px)
- Weight: 500 (Medium)
- Line height: 1.4
- Color: secondary text
- Usage: form headings, element groups

### Body Text

**Base Text**
- Size: 1rem (16px)
- Weight: 400 (Regular)
- Line height: 1.6
- Color: primary text
- Usage: main content, descriptions

**Large Text**
- Size: 1.125rem (18px)
- Weight: 400 (Regular)
- Line height: 1.6
- Color: primary text
- Usage: important descriptions, article leads

**Small Text**
- Size: 0.875rem (14px)
- Weight: 400 (Regular)
- Line height: 1.5
- Color: secondary text
- Usage: captions, metadata

**Fine Text**
- Size: 0.75rem (12px)
- Weight: 400 (Regular)
- Line height: 1.4
- Color: tertiary text
- Usage: footnotes, auxiliary information

### Interactive Elements

**Links**
- Color: primary accent
- Underline: none
- Hover: secondary accent
- Transition: 0.2s ease

**Buttons (Primary)**
- Text color: primary background
- Background: primary accent
- Font size: 1rem
- Weight: 500 (Medium)

**Buttons (Secondary)**
- Text color: primary accent
- Background: transparent
- Border: 1px, primary accent
- Font size: 1rem
- Weight: 500 (Medium)

## Layout and Grid

### Main Grid

**Container**
- Max width: 1200px
- Side padding: 1.5rem
- Centering: margin 0 auto

**Columns**
- System: 12-column grid
- Gaps: 1.5rem between columns
- Responsive: 1 to 4 columns depending on screen

### Spacing and Intervals

**Base Unit**: 0.5rem (8px)

**Small Spacing**: 0.5rem - 1rem  
For controls, icons, small components

**Medium Spacing**: 1.5rem - 2rem  
For cards, sections, main blocks

**Large Spacing**: 3rem - 4rem  
For separating major page sections

**Vertical Rhythm**: 1.5rem  
Base vertical interval between blocks

### Cards and Panels

**Base Card**
- Background: secondary background
- Border: 1px, tertiary background
- Border radius: 8px
- Padding: 1.5rem
- Shadow: rgba(42, 37, 34, 0.08) 0 2px 8px

**Elevated Card**
- Background: primary background
- Border: 1px, #e0d8d2
- Border radius: 12px
- Padding: 2rem
- Shadow: rgba(42, 37, 34, 0.12) 0 4px 16px

### Navigation

**Main Menu**
- Background: primary background
- Height: 60px
- Padding: 0 1.5rem
- Bottom border: 1px, tertiary background
- Shadow: rgba(42, 37, 34, 0.06) 0 1px 4px

**Menu Items**
- Font size: 1rem
- Weight: 500 (Medium)
- Color: secondary text
- Active color: primary accent
- Padding: 0.75rem 1rem

### Forms

**Input Fields**
- Background: primary background
- Border: 1px, #d0c4b8
- Border radius: 6px
- Padding: 0.75rem 1rem
- Min height: 44px
- Focus: border primary accent

**Field Labels**
- Size: 0.875rem
- Weight: 500 (Medium)
- Color: primary text
- Bottom margin: 0.5rem

**Form Buttons**
- Height: 44px
- Padding: 0.75rem 1.5rem
- Border radius: 6px
- Font size: 1rem
- Hover shadow: rgba(205, 133, 63, 0.25) 0 4px 12px

### Element States

**Normal State**
- Standard colors and sizes

**Hover State**
- Background: hover background
- Shadow: increased
- Transform: translateY(-1px)

**Active State**
- Background: slightly darker
- Shadow: reduced
- Transform: translateY(0)

**Focus State**
- Border: primary accent
- Focus shadow: rgba(205, 133, 63, 0.3) 0 0 0 3px

### Responsive Design

**Mobile Devices (up to 768px)**
- Container padding: 1rem
- Heading sizes: reduced by 20%
- Buttons: increased height (48px)
- Cards: 1rem padding
- Navigation: hide secondary elements

**Tablets (768px - 1024px)**
- Container padding: 1.25rem
- Standard font sizes
- Two-column grid for cards
- Horizontal navigation

**Desktop (from 1024px)**
- Full padding and sizes
- Multi-column grid
- Enhanced hover effects
- Sidebar navigation (optional)

### Additional Elements

**Dividers**
- Color: tertiary background
- Thickness: 1px
- Vertical margin: 1rem

**Loading Indicators**
- Color: primary accent
- Background: secondary background
- Animation: smooth

**Tooltips**
- Background: primary text
- Text color: primary background
- Border radius: 4px
- Font size: 0.875rem
