<h1 align="center">ProfileUI<h1>

---

## Short Reflection:
### 1. What design choices did you make (colors, fonts, layout)?
> * Layout: Used ConstraintLayout to create a responsive design that adapts to different screen sizes and orientations
> * Fonts: Used Material Design's built-in styles (Headline5, Body1) to establish a clear visual hierarchy
> * Colors: Relied on the default Theme.MaterialComponents.DayNight theme for good color contrast and automatic support for both light and dark modes

### 2. How did you ensure the screen is user-friendly and accessible?
> * Used sp (scalable pixels) for all text, so users can resize fonts in their device settings
> * Used dp (density-independent pixels) for all sizes and margins, ensuring the layout looks consistent on different screens
> * Added a contentDescription to the profile picture for screen readers
> * Used center alignment and clear spacing to make the layout easy to scan

### 3. What would you improve if this were a real app?
> * Make the "Edit Profile" button functional, navigating to an edit screen
> * Load the user's name, bio, and image dynamically from a database or API
