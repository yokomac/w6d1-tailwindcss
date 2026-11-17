# w6d1-tailwindcss
This is w6d1 tailwindcss assignment.

# Assignment 2: Responsive Course Website

**Level:** Intermediate  
**Course:** Introduction to Tailwind CSS  
**Estimated completion time:** 60–90 minutes  
**Technologies:** HTML and Tailwind CSS only

## Objective

Build a responsive **Code Academy** website that displays web development courses. Use Tailwind CSS utility classes to style the page and make the layout adapt to mobile and desktop screen widths.

**Restrictions:** Use only HTML and Tailwind CSS. Do not use custom CSS/SCSS or JavaScript. Use the Tailwind concepts covered in class: spacing, colors, typography, hover/focus states, responsive breakpoints, Flexbox, Grid, borders, rounded corners, and shadows.

## Requirements

### 1. Header and navigation

Create a header that contains:

- Website title: **Code Academy**
- Three navigation links: **Home**, **Courses**, **About**

Use Tailwind **Flexbox** classes. On mobile, the title and navigation should stack vertically. On medium screens and above, arrange them horizontally. Add appropriate spacing and contrasting colors.

### 2. Welcome section

Add a welcome section containing:

- Heading: **Learn Web Development**
- A short introductory paragraph about the courses
- A button or link labeled **Explore Courses**

Style this section with Tailwind typography, background/text colors, padding and margins. Add hover and keyboard-focus effects to the button or link. Ideally, make **Explore Courses** jump to the course section.

### 3. Course cards

Create **at least four course cards**, each with a title, description, and **Learn More** button or link.

| Course | Description |
|---|---|
| HTML | Learn the structure of web pages. |
| CSS | Learn how to style websites. |
| JavaScript | Make websites interactive. |
| Tailwind CSS | Build modern responsive designs. |

Each card must use Tailwind utilities for padding, borders, rounded corners, shadows, and text styling.

### 4. Responsive Grid

Use **CSS Grid through Tailwind** for the course cards:

- **Mobile (below 768px):** one column
- **Medium screens and above (768px+):** three columns

Recommended classes: `grid`, `grid-cols-1`, `md:grid-cols-3`, `gap-6`.

> With four cards and three columns, the fourth card will wrap onto the next row. This is expected.

### 5. Flexbox

Use Tailwind Flexbox for the header/navigation layout. Suggested classes: `flex`, `flex-col`, `md:flex-row`, `justify-between`, `items-center`, and `gap-4`.

### 6. Interactive states

Add a visible hover effect and a keyboard-focus effect to at least **two** buttons or links.

Suggested classes: `hover:bg-blue-700`, `focus:ring-2`, `focus:ring-blue-500`.

## Responsive testing

Use your browser's Developer Tools to test at narrow and wide viewport sizes. Verify that:

- Course cards stack in one column on mobile.
- Three course columns appear on medium/desktop screens.
- Header and navigation rearrange correctly.
- Text remains legible and the page does not have unnecessary horizontal scrolling.

## Submission

Submit:

1. `index.html` — your completed website
2. **One desktop screenshot** showing the three-column layout
3. **One mobile screenshot** showing the single-column layout

## Grading rubric (100 points)

| Criteria | Points |
|---|---:|
| Required HTML structure and sections | 15 |
| Tailwind typography, colors, and spacing | 20 |
| Flexbox navigation | 20 |
| Responsive Grid layout | 25 |
| Buttons and interactive states | 10 |
| Code readability and organization | 10 |
| **Total** | **100** |

## Optional bonus (+10 points)

Add a **Student Testimonials** section using a responsive Tailwind Grid layout.

## Helpful reference

Tailwind CSS documentation: https://tailwindcss.com/docs

For a quick classroom-only demo, you may include the Tailwind CSS v4 Play CDN in your HTML `<head>`:

```html
<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
```

The Play CDN requires an internet connection and is intended for learning and development, not production.

