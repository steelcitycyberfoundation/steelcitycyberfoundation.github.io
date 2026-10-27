# Steel City Cyber Foundation Website

This is the website for Steel City Cyber Foundation, a student-led project in Pittsburgh working to make cybersecurity education accessible to youth and underserved communities. It is in the planning phase. It is not yet a registered nonprofit and does not currently have a fiscal sponsor.

## About the Website

This is a static website built with HTML, CSS, and JavaScript, designed to be hosted on GitHub Pages. The website includes:

- Responsive design that works on all devices
- Modern, clean UI with cybersecurity-themed elements
- Sections for the organization's mission, focus areas, and ways to get involved
- Free beginner resources (7 guides in `resources/`)
- Contact form that opens the visitor's email app (no backend)
- Social media integration

## Local Development

To work on this website locally:

1. Clone the repository:
   ```
   git clone https://github.com/steelcitycyberfoundation/steelcitycyberfoundation.github.io.git
   ```

2. Navigate to the project directory:
   ```
   cd steelcitycyberfoundation.github.io
   ```

3. Serve the folder and open http://localhost:8000/ (the 404 page uses root-relative paths, so a server works better than opening files directly):
   ```
   python3 -m http.server 8000
   ```

4. Make changes to the HTML, CSS, or JavaScript files as needed.

5. Commit and push your changes to deploy them to the live site.

## Deployment

This website is automatically deployed to GitHub Pages when changes are pushed to the main branch. The live site can be accessed at [https://steelcitycyberfoundation.github.io](https://steelcitycyberfoundation.github.io).

## File Structure

- `index.html` - Main HTML file
- `404.html` - Not-found page served by GitHub Pages
- `css/styles.css` - Main stylesheet
- `js/main.js` - JavaScript functionality
- `resources/` - Beginner guide pages
- `images/` - Directory containing all website images
- `favicon-32.png`, `apple-touch-icon.png`, `logo.png` - Icons and the share image
- `CNAME` - Placeholder only (comments, no domain). The site is served at the github.io address.

## Contributing

If you'd like to contribute to the website, please:

1. Fork the repository
2. Create a new branch for your feature
3. Make your changes
4. Submit a pull request

## Contact

For questions about the website or the organization, please contact:

- Email: steelcitycyberfoundation@gmail.com
- Instagram: @SteelCityCyberFoundation

## License

This project is licensed under the MIT License - see the LICENSE file for details.
