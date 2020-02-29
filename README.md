<h1 align="center">Jellyfin Anime Plugin</h1>
<h3 align="center">Part of the <a href="https://jellyfin.media">Jellyfin Project</a></h3>

<p align="center">

<img alt="Logo Banner" src="https://raw.githubusercontent.com/jellyfin/jellyfin-ux/master/branding/SVG/banner-logo-solid.svg?sanitize=true"/>
<br/>
<br/>
<a href="https://github.com/jellyfin/jellyfin-plugin-anime">
<img alt="GPL 2.0 License" src="https://img.shields.io/github/license/jellyfin/jellyfin-plugin-anime.svg"/>
</a>
<a href="https://github.com/jellyfin/jellyfin-plugin-anime/releases">
<img alt="Current Release" src="https://img.shields.io/github/release/jellyfin/jellyfin-plugin-anime.svg"/>
</a>
<br/>
<a href="https://opencollective.com/jellyfin">
<img alt="Donate" src="https://img.shields.io/opencollective/all/jellyfin.svg?label=backers"/>
</a>
<a href="https://features.jellyfin.org">
<img alt="Feature Requests" src="https://img.shields.io/badge/fider-vote%20on%20features-success.svg"/>
</a>
<a href="https://forum.jellyfin.org">
<img alt="Discuss on our Forum" src="https://img.shields.io/discourse/https/forum.jellyfin.org/users.svg"/>
</a>
<a href="https://matrix.to/#/+jellyfin:matrix.org">
<img alt="Chat on Matrix" src="https://img.shields.io/matrix/jellyfin:matrix.org.svg?logo=matrix"/>
</a>
<a href="https://www.reddit.com/r/jellyfin">
<img alt="Join our Subreddit" src="https://img.shields.io/badge/reddit-r%2Fjellyfin-%23FF5700.svg"/>
</a>
</p>

Jellyfin Anime Plugin is a plugin that adds providers specific to anime series and movies to the Jellyfin server. We welcome all contributions and pull requests!

If you have a larger feature in mind please open an issue so we can discuss the implementation before you start.

## Build Process

### Dependencies

- .NET Core 3.1

### Getting Started
1. Clone or download this repository

2. Ensure you have .NET Core SDK setup and installed

3. Build plugin with following command.
   ```sh
   dotnet publish --configuration Release --output bin
   ```
4. Place the resulting file in the `plugins` folder under the program data directory or inside the portable install directory
