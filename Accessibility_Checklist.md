# Accessibility Checklist

## Text alternatives

- Every meaningful image has descriptive alt text
- Decorative images use empty alt (alt="") or CSS backgrounds
- Complex images (charts, diagrams) have a longer text description nearby
- Icon-only buttons and links have accessible names

## Adaptable structure

- Headings (h1–h6) are used in a logical order, not for visual styling
- Lists, tables, and landmarks (header, nav, main, footer) use proper semantic HTML
- Data tables have header cells (th) with correct scope
- Reading order in the source matches the visual order
- Instructions don’t rely only on shape, color, size, or position
- Content works in both portrait and landscape
- Form fields for personal info use autocomplete attributes

## Distinguishable

- Text contrast is at least 4.5:1 (3:1 for large text)
- UI components and graphics have at least 3:1 contrast
- Color is never the only way to convey information
- Page is usable when zoomed to 200%
- No horizontal scrolling at 320px width / 400% zoom
- Text spacing can be increased without losing content
- Images of text are avoided except for logos
- Content that appears on hover or focus can be dismissed, hovered over, and persists

## Keyboard

- All functionality works with keyboard alone
- No keyboard traps
- Single-character shortcuts can be turned off or remapped
- “Skip to main content” link is present

## Navigation

- Every page has a unique, descriptive <title>
- Focus order is logical
- Link text makes sense out of context (avoid “click here”)
- Multiple ways to find pages, such as menu, search, or sitemap
- Headings and labels describe their content
- Keyboard focus indicator is always visible
- Focused elements aren’t hidden behind sticky headers or banners

## Input modalities

- Multi-finger or path-based gestures have single-pointer alternatives
- Actions fire on pointer release, not press, or can be aborted
- Visible labels match accessible names
- Click and tap targets are at least 24×24 CSS pixels
- Drag-and-drop actions have a non-dragging alternative

### Readable

- Page language is set (<html lang="en">)
- Language changes within the page are marked up

### Predictable

- Focusing or entering input doesn’t trigger unexpected context changes
- Navigation and component order are consistent across pages
- Help options (contact, chat, FAQ) appear in a consistent place

### Clean Code

- Use valid, semantic HTML; prefer native elements over custom ones (button rather than div)
- ARIA is used only where native HTML can’t do the job, and is used correctly
