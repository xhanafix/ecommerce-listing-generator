# E-commerce Listing Generator

A powerful web application that generates optimized product listings for multiple e-commerce platforms using AI. The application helps sellers create engaging and effective product descriptions in Bahasa Malaysia for Shopee, TikTok Shop, and Facebook Marketplace.

## Features

### Multi-Platform Support
- **Shopee**: Generate optimized listings with titles, descriptions, and marketing content
- **TikTok Shop**: Create engaging video scripts and product descriptions
- **Facebook Marketplace**: Generate marketplace-optimized listings with location-based content

### AI-Powered Content Generation
- Uses OpenRouter API to access multiple AI models:
  - Claude 3 Opus
  - Claude 3 Sonnet
  - GPT-4 Turbo
  - Gemini Pro
  - Custom model support
- Generates content in casual Bahasa Malaysia
- Optimizes content for each platform's specific requirements

### User-Friendly Interface
- Clean, modern design using Tailwind CSS
- Intuitive form with helpful tooltips
- Real-time connection testing
- Easy tab switching between platforms
- Responsive design for all devices

### Content Management
- Copy to clipboard functionality
- Export to CSV option
- Regenerate content with one click
- Preview generated content before use

### Security & Privacy
- API keys stored securely in browser's local storage
- No server-side storage of sensitive data
- Direct API calls to OpenRouter
- No third-party data sharing

## Setup

1. Clone the repository:
```bash
git clone https://github.com/xhanafix/ecommerce-listing-generator.git
cd ecommerce-listing-generator
```

2. Start a local server:
```bash
python -m http.server 8000
```

3. Open your browser and navigate to:
```
http://localhost:8000
```

## Usage

### API Setup
1. Get an API key from [OpenRouter](https://openrouter.ai/)
2. Enter your API key in the API Settings section
3. Select your preferred AI model
4. Test the connection using the "Test Connection" button

### Product Details
Fill in the following information:
- Product Name: The exact name of your product
- Product Details: Features, materials, and benefits (one per line)
- Target Market: Who would be interested in your product
- Use Case: Where and how the product will be used
- Price: Product price in Malaysian Ringgit (RM)
- Product Variants: Different versions of your product (optional)
- Delivery Option: How customers can receive the product
- Product Location: Where the product is located

### Generating Listings
1. Select your target platform (Shopee, TikTok Shop, or Facebook Marketplace)
2. Click "Generate Listing"
3. Wait for the AI to generate optimized content
4. Review the generated content
5. Use the copy or export buttons to save the content

### Generated Content Structure

#### Shopee
- Optimized Product Title
- Suggested Thumbnail Text
- Bullet Features
- AIDA Description
- Suggested Category & Attributes
- Variant Names
- Local Call-to-Action
- Promo Strategy

#### TikTok Shop
- SEO Product Title
- Short Video Script
- Feature Bullet Points
- AIDA-style Description
- TikTok Hashtags
- Thumbnail Text
- Promo Strategy
- Sample Pinned Comment

#### Facebook Marketplace
- Optimized Title
- Product Description
- Feature Bullet Points
- Overlay Text
- Offer Strategy
- Location Phrases
- Keyword Tags
- Sample Reply Message

## Technologies Used
- HTML5
- Tailwind CSS
- JavaScript (ES6+)
- OpenRouter API
- Various AI Models (Claude, GPT-4, Gemini)

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Icons provided by [Flaticon](https://www.flaticon.com/)
- AI models powered by OpenRouter
- Built with [Tailwind CSS](https://tailwindcss.com/) 