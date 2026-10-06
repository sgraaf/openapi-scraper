# openapi-scraper

Track changes to RESTful APIs by scraping their OpenAPI descriptions

Inspired by Simon Willison's [graphql-scraper](https://github.com/simonw/graphql-scraper) for GraphQL schemas

In this repo:

- [github/github.json](github/github.json) ([history](https://github.com/sgraaf/openapi-scraper/commits/main/github/github.json)) for `https://api.github.com/`
- [openai/openai.yaml](openai/openai.yaml) ([history](https://github.com/sgraaf/openapi-scraper/commits/main/openai/openai.yaml)) for `https://api.openai.com/v1`
- [openlibrary/openlibrary.json](openlibrary/openlibrary.json) ([history](https://github.com/sgraaf/openapi-scraper/commits/main/openlibrary/openlibrary.json)) for `https://openlibrary.org/`
- Rocket.Chat: [rocketchat/](rocketchat) ([history](https://github.com/sgraaf/openapi-scraper/commits/main/rocketchat)) for the [Rocket.Chat REST API](https://github.com/RocketChat/Rocket.Chat-Open-API), split into one OpenAPI file per domain
- [openwebui/openwebui.json](openwebui/openwebui.json) ([history](https://github.com/sgraaf/openapi-scraper/commits/main/openwebui/openwebui.json)) for [Open WebUI](https://github.com/open-webui/open-webui), generated from the latest [`open-webui`](https://pypi.org/project/open-webui/) release on PyPI
- [jellyfin/jellyfin.json](jellyfin/jellyfin.json) ([history](https://github.com/sgraaf/openapi-scraper/commits/main/jellyfin/jellyfin.json)) for the [Jellyfin API](https://github.com/jellyfin/jellyfin-sdk-kotlin), as published in the Jellyfin Kotlin SDK
