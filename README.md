# GPA Calculator 

A modern, responsive GPA calculator.

##  GPA Calculation
The calculator uses the standard weighted average formula:
```
GPA = Σ(Credit × Points) / Σ(Credits)
```

## Customization

You can easily customize the calculator by modifying the CSS variables in the `:root` selector:

```css
:root {
    --primary: #6366f1;        /* Primary color */
    --bg-body: #f3f4f6;        /* Body background */
    --bg-card: #ffffff;        /* Card background */
    --text-main: #111827;      /* Main text color */
    --radius: 16px;            /* Border radius */
    /* ... and more */
}
```
**Note**: This calculator uses the 10-point GPA scale. If your institution uses a different scale (e.g., 4.0 scale), you may need to convert the grade points accordingly.
