# Font Pairing Options for Photography Portfolio

Here are several beautiful, modern font pairings that work well with photography portfolios. Each pairing includes a display font (for headings) and a body font (for text).

## 1. Playfair Display + Inter (Current)

**Best for**: Clean, modern, and elegant portfolios  
**Display font**: Playfair Display (serif) - beautiful, classic feel with high readability  
**Body font**: Inter (sans-serif) - clean, modern, with excellent legibility

```html
<!-- Google Fonts -->
<link
  href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&family=Inter:wght@300;400;500;600&display=swap"
  rel="stylesheet"
/>

<!-- Tailwind Config -->
<script>
  tailwind.config = {
    theme: {
      extend: {
        fontFamily: {
          display: ['"Playfair Display"', "serif"],
          body: ['"Inter"', "sans-serif"],
        },
      },
    },
  };
</script>

<style>
  body {
    font-family: "Inter", sans-serif;
  }
</style>
```

## 2. Cinzel + Montserrat

**Best for**: Classic, timeless portfolios with a touch of elegance  
**Display font**: Cinzel (serif) - decorative, with a classic architectural feel  
**Body font**: Montserrat (sans-serif) - clean, modern, with wide letterforms

```html
<link
  href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;500;600;700&family=Montserrat:wght@300;400;500;600&display=swap"
  rel="stylesheet"
/>

<script>
  tailwind.config = {
    theme: {
      extend: {
        fontFamily: {
          display: ['"Cinzel"', "serif"],
          body: ['"Montserrat"', "sans-serif"],
        },
      },
    },
  };
</script>

<style>
  body {
    font-family: "Montserrat", sans-serif;
  }
</style>
```

## 3. Lora + Source Sans Pro

**Best for**: Sophisticated, editorial-style portfolios  
**Display font**: Lora (serif) - elegant, with subtle curves and high readability  
**Body font**: Source Sans Pro (sans-serif) - versatile, neutral, and highly readable

```html
<link
  href="https://fonts.googleapis.com/css2?family=Lora:wght@400;500;600;700&family=Source+Sans+Pro:wght@300;400;500;600&display=swap"
  rel="stylesheet"
/>

<script>
  tailwind.config = {
    theme: {
      extend: {
        fontFamily: {
          display: ['"Lora"', "serif"],
          body: ['"Source Sans Pro"', "sans-serif"],
        },
      },
    },
  };
</script>

<style>
  body {
    font-family: "Source Sans Pro", sans-serif;
  }
</style>
```

## 4. Raleway + Merriweather

**Best for**: Modern, minimalist portfolios with a classic touch  
**Display font**: Raleway (sans-serif) - modern, with a geometric feel and wide letterforms  
**Body font**: Merriweather (serif) - classic, with a warm, traditional feel

```html
<link
  href="https://fonts.googleapis.com/css2?family=Raleway:wght@300;400;500;600;700&family=Merriweather:wght@300;400;500;600&display=swap"
  rel="stylesheet"
/>

<script>
  tailwind.config = {
    theme: {
      extend: {
        fontFamily: {
          display: ['"Raleway"', "sans-serif"],
          body: ['"Merriweather"', "serif"],
        },
      },
    },
  };
</script>

<style>
  body {
    font-family: "Merriweather", serif;
  }
</style>
```

## 5. Cormorant + Open Sans

**Best for**: Elegant, minimalist portfolios with a modern twist  
**Display font**: Cormorant (serif) - refined, with a classic feel and high contrast  
**Body font**: Open Sans (sans-serif) - friendly, clean, and highly readable

```html
<link
  href="https://fonts.googleapis.com/css2?family=Cormorant:wght@400;500;600;700&family=Open+Sans:wght@300;400;500;600&display=swap"
  rel="stylesheet"
/>

<script>
  tailwind.config = {
    theme: {
      extend: {
        fontFamily: {
          display: ['"Cormorant"', "serif"],
          body: ['"Open Sans"', "sans-serif"],
        },
      },
    },
  };
</script>

<style>
  body {
    font-family: "Open Sans", sans-serif;
  }
</style>
```

## How to Switch Fonts

1. Replace the Google Fonts link in the `<head>` section
2. Update the `fontFamily` object in the Tailwind config
3. Update the `font-family` property in the `<style>` tag

All these pairings are optimized for readability, visual hierarchy, and compatibility with photography portfolio designs. They work well in both light and dark themes.
