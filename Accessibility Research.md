---
aliases: []
cssclasses: []
tags: []

---

```ad-info
collapse: open
**Created**: `=this.file.ctime`
**Modified**: `=this.file.mtime`
```

### Font
- Characters should be sans-serif, not italic, oblique, script, highly decorative, or unusually shaped ([Understanding Accessible Fonts and Typography for Section 508 Compliance | Section508.gov](https://www.section508.gov/develop/fonts-typography/))
- Characters should be at least 3/16 in (4.8 mm, generally corresponds to 16pt) high based on the uppercase “I” and have good contrast with background 
	- If the user is able to zoom, you don’t have to use 16 pt, and are even discouraged from using it. Use 11-12, or 15-16 pt. AVOID text smaller than 9 pt. 
- Serif Fonts are preferred for people with good vision, as it can even boost reading speed. But for people with low vision, serifs become to become troublesome. General Guidelines: 
	- For HEADINGS or EMPHASIS: Use Serif Fonts 
	- For BODY and FLUID READING: Use Sans Serif Fonts
- Text and images of text need a contrast ratio of at least 4.5:1. Large text like 16 pt bold and icons need 3:1 ratio between foreground and background. 
- Readers need to be able to resize to 200% zoom without losing quality or functionality. 
- Use text over images of text for more control.
[Typography for Glanceable Reading: Bigger Is Better](https://www.nngroup.com/articles/glanceable-fonts/)
- Use larger fonts for things that should only be glanced at 
- Avoid all lower-case for things that are glanceable
- Avoid all lower-case text for headings and titles (even if that’s the trend)
- Avoid condensed or thin typefaces if you want your user to be locked in
- Use large fonts in noncondensed variants for quick readability of notifications, toasts, feedbacks, etc.

[How type influences readability – Fonts Knowledge - Google Fonts](https://fonts.google.com/knowledge/readability_and_accessibility/how_type_influences_readability)
- “There are several free tools that provide the ability to see how your typography will look to people with varying color vision capabilities. Visit Material Design Accessibility Color Contrast Guidelines, Material Design Color and Accessibility, The Perception of Color, and Colour Blindness Awareness. To see what the three main types of color blindness look like, try out the Chromatic Vision Simulator application. To see if your choice of background and text colors meet color contrast guidelines, try the free WebAIM contrast checker tool.”