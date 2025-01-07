# Telebort-Assignment
# Outfit Color Matcher

A web application that helps users find matching shirt colors based on their selected pant color using the Colormind API.

## Features

- Interactive RGB color picker with sliders
- Real-time color preview
- Matching shirt color suggestions
- Hex code display
- Responsive design

## Technologies Used

- TypeScript
- Hono (Web Framework)
- Colormind API
- HTML/CSS
- Cloudflare Workers (for deployment)

## API Integration

This project uses the [Colormind API](http://colormind.io/api/) to generate harmonious color combinations. The API:
- Takes RGB values as input
- Returns color palettes
- Is free to use
- Doesn't require authentication

## How to Use

1. Adjust the RGB sliders or enter RGB values to select your pant color
2. View the real-time color preview
3. See matching shirt color suggestions automatically generated
4. Each suggestion includes:
   - Color preview
   - Color name
   - Hex code
  
## Try It Now
https://outfit.matchoutfit.workers.dev/
