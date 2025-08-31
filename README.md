# SkyLens# SkyLens 🌌✨

## Overview

SkyLens is a web application offering immersive astronomical exploration tools designed for both casual stargazers and astronomy enthusiasts. It features:

- Embedded **Aladin Lite** for real-time interactive star maps based on user location 🌟
- A **Star Wiki** page enabling detailed star searches powered by the API Ninjas Stars API 🔭
- A retro-inspired user interface with pixel art fonts and frosted glass effects 🪐
- Plans to integrate immersive live sky views via **Stellarium Web** or self-hosted Stellarium Web Engine.

SkyLens makes it easy to explore stars, constellations, and the night sky from any modern web browser.

---

## Features

- **Live Star Map:** Interactive sky mapped with Aladin Lite based on user geolocation.
- **Star Wiki:** Searchable star database with detailed astronomical information.
- **Retro UI:** Visually pleasing pixel-art design with smooth animations and frosted glass style.
- **API-Driven:** Integrates with public astronomy APIs for up-to-date star data.
- **Responsive Design:** Works well on desktops, tablets, and mobile devices.

---

## Installation

1. Clone this repository:

    ```
    git clone https://github.com/your-username/sky-lens.git
    cd sky-lens
    ```

2. No backend server required; it is a static web app.

3. Open `index.html` in a modern browser to use the landing page.

4. Update API keys:

    - Insert your **API Ninjas Stars API** key in `starwiki.html` at the designated location.

---

## Usage

- From the landing page, access:
  - **Live Night Sky:** Opens the embedded Aladin Lite star map.
  - **Star Wiki:** Enter star names to fetch detailed data.
  - **360° Sky Viewer:** Explore panoramic sky images (feature under development).
  
- Use navigation buttons to switch between features easily.

---

## Planned Improvements 🚀

- Embed **Stellarium Web** for immersive location-aware 3D sky visualization.
- Self-host Stellarium Web Engine for enhanced customization.
- Add real-time sky panorama updating by location/compass.
- Expand the Star Wiki with more detailed astrophysical data.
- Improve mobile interactions and accessibility.

---

## API Keys and Configuration

- Get your free API key for the Stars API at [API Ninjas](https://api-ninjas.com/api/stars).
- Insert your API key in the `starwiki.html` file:

    ```
    headers: { 'X-Api-Key': 'YOUR_API_KEY_HERE' }
    ```

- No key needed for Aladin Lite integration.

---

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/your-username/sky-lens/issues) first.

To contribute:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

Created and maintained by Diya Kishore.  
Email: diyakishore15@example.com  


---

## Acknowledgements

- [Aladin Lite](https://aladin.u-strasbg.fr/AladinLite/)
- [API Ninjas Stars API](https://api-ninjas.com/api/stars)
- [Stellarium Web](https://stellarium-web.org)
- [Google Fonts - Press Start 2P](https://fonts.google.com/specimen/Press+Start+2P)
- Inspired by classic pixel art and retro interfaces

---

## Screenshots

_Add screenshots of your app here to showcase features._

