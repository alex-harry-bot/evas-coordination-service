# Operational notes

## Contact placeholders

Search/replace before launch:

- `+15555555555`
- `(555) 555-5555`
- `hello@example.com`
- `https://formspree.io/f/your-form-id`

## Form backend recommendation

For simplest launch:

- Netlify Forms if hosted on Netlify
- Formspree if hosted anywhere else
- Resend/custom backend only if custom automation is needed later

## Image handling

The current site hotlinks Unsplash images for design speed. Before production launch, download licensed images or use owned images and store optimized `.webp` versions under `assets/images/`.

Target sizes:

- Hero: 1600px wide WebP/JPEG, 75-85 quality
- Gallery: 900-1400px wide WebP/JPEG, 75-85 quality

## Suggested final domain ideas

- evascoordination.com
- eventsbyeva.com
- evajohnstonevents.com
- quadcitieseventcoordinator.com
