# Russet Dark Theme

Detailed specification of the dark version of the autumn-inspired Russet color theme for web interfaces.

## Color Palette

### Background Colors

**Primary Background**: `#1c1914`  
Deep dark brown with warm undertones. Used as the main application background, provides maximum eye comfort during extended work sessions.

**Secondary Background**: `#25211c`  
Slightly lighter than primary, applied to cards, panels, and other second-level surfaces. Creates subtle visual hierarchy.

**Tertiary Background**: `#2f2a24`  
Used for elevated elements: modal windows, dropdown menus, tooltips. Ensures clear layer separation in the interface.

**Hover Background**: `#3a342c`  
Applied to interactive elements in hover state. Subtle but noticeable highlighting effect.

### Text Colors

**Primary Text**: `#f0ebe6`  
Warm shade of white with a light beige undertone. Perfect for headings and main content, ensures excellent readability on dark backgrounds.

**Secondary Text**: `#c4beb5`  
Muted beige color for captions, metadata, and less important information. Creates visual hierarchy without losing readability.

**Tertiary Text**: `#9a9186`  
Soft gray-brown for auxiliary text, timestamps, hints. Maintains the overall theme aesthetics.

**Disabled Text**: `#6b635a`  
Used for disabled controls and inactive content.

### Accent Colors

**Primary Accent**: `#e6a85c`  
Warm amber shade for buttons, links, and other active elements. Stands out well on dark backgrounds while maintaining autumn theming.

**Secondary Accent**: `#b8794a`  
Darker reddish-brown for secondary actions and additional controls.

**Tertiary Accent**: `#d4a373`  
Golden-brown for highlighting important elements and states.

**Copper Accent**: `#cd7f5f`  
Copper shade for special highlights and unique interface elements.

### Semantic Colors

**Success**: `#8fbc8f`  
Muted green for successful operations and positive states.

**Warning**: `#daa520`  
Golden-yellow for warnings and important notifications.

**Error**: `#cd5c5c`  
Soft red for errors and critical states.

**Info**: `#87ceeb`  
Sky blue for informational messages.

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
- Hover: copper accent
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
- Shadow: subtle, muted

**Elevated Card**
- Background: tertiary background
- Border: 1px, hover background
- Border radius: 12px
- Padding: 2rem
- Shadow: more pronounced

### Navigation

**Main Menu**
- Background: secondary background
- Height: 60px
- Padding: 0 1.5rem
- Bottom border: 1px, tertiary background

**Menu Items**
- Font size: 1rem
- Weight: 500 (Medium)
- Color: secondary text
- Active color: primary accent
- Padding: 0.75rem 1rem

### Forms

**Input Fields**
- Background: primary background
- Border: 1px, tertiary background
- Border radius: 6px
- Padding: 0.75rem 1rem
- Min height: 44px

**Field Labels**
- Size: 0.875rem
- Weight: 500 (Medium)
- Color: secondary text
- Bottom margin: 0.5rem

**Form Buttons**
- Height: 44px
- Padding: 0.75rem 1.5rem
- Border radius: 6px
- Font size: 1rem

### Responsive Design

**Mobile Devices (up to 768px)**
- Container padding: 1rem
- Heading sizes: reduced by 20%
- Buttons: increased height (48px)
- Cards: 1rem padding

**Tablets (768px - 1024px)**
- Container padding: 1.25rem
- Standard font sizes
- Two-column grid for cards

**Desktop (from 1024px)**
- Full padding and sizes
- Multi-column grid
- Enhanced hover effects
