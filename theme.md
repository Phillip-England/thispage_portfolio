# Theme Vision: Dark Developer Portfolio

## Design Philosophy

This portfolio embraces a **dark, professional, developer-focused aesthetic** that emphasizes content over decoration. The design prioritizes readability, clean hierarchy, and subtle visual interest through strategic use of color and gradients.

## Color Palette

### Core Colors
- **Background (Primary)**: `neutral-950` (#0a0a0a) - Deep black for main backgrounds
- **Background (Secondary)**: `neutral-900` (#171717) - Slightly lighter for cards, sidebars
- **Background (Tertiary)**: `neutral-800` (#262626) - For code blocks, inputs, hover states
- **Border**: `neutral-800` (#262626) - Subtle borders that don't distract

### Text Colors
- **Primary Text**: `white` (#ffffff) - Headings, important content
- **Secondary Text**: `neutral-300` (#d4d4d4) - Body text
- **Muted Text**: `neutral-400` (#a3a3a3) - Less important text, descriptions
- **Subtle Text**: `neutral-500` (#737373) - Timestamps, metadata

### Accent Colors (Project-Specific)
- **Blue** (`blue-500`/`blue-600`): CLI tools, utilities - represents reliability
- **Purple** (`purple-500`/`purple-600`): Web frameworks - represents creativity
- **Green** (`green-500`/`green-600`): SSG/build tools - represents growth and output

### Gradient
- **Primary Gradient**: `from-blue-600 to-purple-600` - Used for profile image glow, buttons, and key CTAs

## Typography

### Font Stack
- **Primary**: System font stack with Inter preference
  - `'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif`
- **Monospace**: JetBrains Mono for code
  - `'JetBrains Mono', 'SF Mono', Monaco, Consolas, monospace`

### Scale
- **Hero Title**: `text-4xl` (36px) - Bold, white
- **Section Header**: `text-2xl` (24px) - Bold, white
- **Subsection**: `text-xl` (20px) - Bold or semibold
- **Body**: `text-base` (16px) - neutral-300
- **Small/Meta**: `text-sm` (14px) - neutral-400/500

## Layout Principles

### Container
- Max width: `max-w-4xl` (896px) for content pages
- Padding: `px-6` horizontal, `py-20` vertical
- Centered with `mx-auto`

### Spacing
- Section spacing: `mb-12` to `mb-16`
- Element spacing: `mb-4` to `mb-6`
- Card gaps: `gap-6`

### Responsive Design
- Single column on mobile
- Two-column grid for project cards on `md:` breakpoint
- Full-width sidebar navigation becomes hidden on mobile for doc pages

## Component Patterns

### Cards
- Background: `bg-neutral-900`
- Border: `border border-neutral-800`
- Hover: `hover:border-neutral-600`
- Rounded: `rounded-xl`
- Shadow: None (relies on border contrast)

### Buttons
- Primary: Gradient background with hover lightening
- Focus: Ring with `ring-blue-600 ring-offset-neutral-950`

### Navigation
- Horizontal nav with border-bottom separator
- Links: `text-neutral-400 hover:text-white`
- Active/Logo: `text-white font-bold`

### Code Blocks
- Background: `bg-neutral-800` or `bg-neutral-900`
- Border: `border border-neutral-700`
- Rounded: `rounded-lg`
- Padding: `p-4`
- Overflow: `overflow-x-auto`

### Tables
- Header: `bg-neutral-800`
- Rows: Alternating or plain with bottom borders
- Cell padding: `p-3` to `p-4`

## Animation & Transitions

- All color transitions: `transition-colors duration-200`
- Transform transitions: `transition-transform duration-300`
- Hover effects should be subtle and purposeful
- No heavy animations - this is a professional portfolio

## Documentation Pages

Documentation pages follow the same dark theme but with:
- Fixed left sidebar navigation (desktop only)
- Main content area with comfortable reading width
- Section anchors with scroll margin
- Syntax-highlighted code blocks using accent colors

## Key Visual Elements

1. **Profile Image Glow**: Gradient blur effect around profile photo creates a focal point
2. **Project Color Coding**: Each project has an associated accent color for quick identification
3. **Subtle Dividers**: `h-px bg-neutral-800` used to separate sections without heavy visual weight
4. **Icon Containers**: Rounded containers with muted backgrounds showcase icons with purpose

## Accessibility

- Minimum contrast ratios maintained between text and backgrounds
- Focus states visible with ring utilities
- Interactive elements have clear hover/focus states
- Screen reader text provided where icons are used alone
