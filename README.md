
Use Illustrator files
# 🍳 Perfect Fried Eggs

Welcome to the **Perfect Fried Eggs** project! This simple and delicious recipe will teach you how to make fried eggs with crispy edges and runny yolks, ready in minutes with just a few ingredients. This is also a project for the recipe assignment on the FreeCodeCamp Full-Stack Development Certificate.

## 📋 Table of Contents
- [Overview](#overview)
- [User Stories](#user-stories)
- [Getting Started](#getting-started)
- [Implementation](#implementation)
- [CSS Styling](#css-styling)
- [To-Do List for Image Optimization](#to-do-list-for-image-optimization)
- [License](#license)

## 🛸 Overview
This project is a solution for a lab project on FreeCodeCamp. It provides a straightforward guide to making perfect fried eggs, including an image of the ingredients and clear, step-by-step instructions. This project is done using only HTML, with the CSS added later for personal reference to enhance the appearance.

## 📝 User Stories
To complete this lab project, the following user stories were implemented and ensured to meet all specifications:
- **h1 Element:** An h1 element with the topic of the page is included at the top.
- **Introduction Paragraph:** A paragraph introducing the topic is placed below the h1 element.
- **Image:** An image of the ingredients is included with appropriate alt text.
- **Ingredients List:** An unordered list of ingredients is provided.
- **Instructions:** An ordered list of step-by-step instructions is included.

## 🚀 Getting Started
To get started with this project, simply copy the provided HTML code into an HTML file and open it in your preferred web browser.

### Prerequisites
No special tools or software are required. A modern web browser is all you need to view the page.

## 💻 Implementation
To fulfill the user stories and ensure all tests were met, the following steps were taken:
1. **HTML Structure:** The HTML document was structured to include the necessary elements.
2. **Heading and Introduction:** An h1 element was added to define the main topic, followed by a paragraph to introduce the recipe.
3. **Image:** An image element was included to visually represent the ingredients, with appropriate alt text for accessibility.
4. **Ingredients List:** An unordered list was provided to list all necessary ingredients for the recipe.
5. **Instructions:** An ordered list was created to give clear, step-by-step instructions on how to make perfect fried eggs.

By following these steps, all user stories were met, and the project passed all specified tests, ensuring a successful solution.

## 💅 CSS Styling

While the original FreeCodeCamp lab test doesn't require CSS, it has been added here as a personal reference to enhance the appearance and usability of the project. Key styling features include:

- **Responsive Design**: Ensures the layout adjusts smoothly across different devices and screen sizes.
- **Modern Typography**: Utilizes web-safe fonts to enhance readability.
- **Color Scheme**: Applies a consistent color palette for a cohesive look and feel.
- **Hover Effects**: Adds subtle hover effects to navigation links and buttons for better interactivity.
- **Flexbox**: Utilizes Flexbox for aligning and distributing space among items in the layout.

## 🚀 Implementing Preconnect

To improve loading performance, I added the `<link rel="preconnect">` tag in the `<head>` section:

```html
<head>
  <!-- Other head content -->
  <link rel="preconnect" href="https://cdn.freecodecamp.org">
  <link rel="preconnect" href="[Your-URL-Here]">
  <!-- Other head content -->
</head>
```

1. Preconnect to the CDN domain.
2. Preconnect to your website's domain.

This allows the browser to start the connection process ahead of time, reducing latency when resources are requested.

NOTE TO SELF: Replace `[Your-URL-Here]` with your actual website URL.

## 🔍 SEO Implementation

### JSON-LD Structured Data
The project includes structured data markup using JSON-LD to enhance search engine visibility and potentially display rich snippets in search results.

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Recipe",
  "name": "Perfect Fried Eggs",
  // ... [rest of the JSON structure]
}
</script>
```

### Important Notes About JSON-LD:
1. **Location**: Place directly in HTML `<head>` section
2. **No External Files**: Don't create separate .js files for this
3. **No Script Source**: Don't add src attribute to the script tag
4. **Type Attribute**: Must include `type="application/ld+json"`

### Validating JSON-LD:

#### Online Tools:
1. **Google's Tools**
   - [Rich Results Test](https://search.google.com/test/rich-results)
   - [Schema Markup Validator](https://validator.schema.org/)
2. **JSON Validators**
   - [JSON Editor Online](https://jsoneditoronline.org/)
   - [JSONLint](https://jsonlint.com/)

#### VS Code Validation:
1. Create temporary .json file
2. Paste JSON content (without script tags)
3. Check for red squiggly lines
4. Hover over errors for explanations

### Common JSON Validation Rules:
```javascript
// ✅ Valid Format Examples:
{
  "propertyName": "String value",    // String values in quotes
  "numberProperty": 42,              // Numbers without quotes
  "booleanProperty": true,           // Booleans without quotes
  "arrayProperty": [                 // Arrays use square brackets
    "item1",
    "item2"
  ],
  "objectProperty": {                // Objects use curly braces
    "nestedProperty": "value"
  }
}
```

### Optional Schema Enhancements:
```javascript
{
  "recipeCategory": "Breakfast",
  "recipeCuisine": "International",
  "aggregateRating": {
    "@type": "AggregateRating",
    "ratingValue": "4.8",
    "reviewCount": "249"
  },
  "video": {
    "@type": "VideoObject",
    "name": "How to Make Perfect Fried Eggs",
    "description": "Step-by-step video guide",
    "thumbnailUrl": "[Video-Thumbnail-URL]",
    "contentUrl": "[Video-URL]",
    "uploadDate": "2025-01-25"
  },
  "nutrition": {
    "@type": "NutritionInformation",
    "calories": "90 calories per egg",
    "fatContent": "7 g",
    "proteinContent": "6 g",
    "carbohydrateContent": "0.6 g",
    "servingSize": "1 egg"
  }
}
```

### Implementation Checklist:
- [ ] Replace all placeholder URLs
- [ ] Verify dates and times
- [ ] Check author information
- [ ] Validate JSON structure
- [ ] Test in Google's Rich Results Test
- [ ] Ensure all required fields are filled
- [ ] Update nutrition information if needed
- [ ] Add optional enhancements as needed


## 📋 To-Do List for Image Optimization
Implement before the 21st

1. Implement "preconnect"
2. Use DNS Prefetching
3. Use Modern Image Formats (e.g., WebP)
4. Enable Lazy Loading
5. Use a Content Delivery Network (CDN)
6. Optimize Images (Compress Without Losing Quality)
7. Use Responsive Images
8. Set Proper Cache Control Headers
9. Update CSS for more cooking themed appearance

## 📜 License
No license for this project.

---

Thank you for checking out this project! We hope you enjoy making and eating your perfect fried eggs. 🍳✨

**Newtype Out**
