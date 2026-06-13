# iHeartRadio

iHeartRadio is a digital radio platform operated by iHeartMedia that provides access to over 800 live broadcast and digital-only radio stations from more than 150 U.S. cities, podcasts, artist-based custom stations, and curated music content. The platform was originally built by Clear Channel Radio and has grown to become one of the largest digital radio services in the United States with availability across 200+ device platforms.

## APIs

The iHeartRadio platform exposes REST APIs accessible at `api.iheart.com` covering:

- **Catalog Search API** (`/api/v1/catalog/searchAll`) - Search across all content types including live stations, digital-only stations, podcasts, artists, tracks, and playlists
- **Live Stations API** (`/api/v2/content/liveStations/{station_id}`) - Retrieve station metadata and stream URLs in multiple formats (HLS, Shoutcast, RTMP, StreamTheWorld, PLS)
- **Podcasts API** (`/api/v3/podcast/categories/{podcast_id}/episodes`) - Search podcasts and retrieve episode listings with direct audio stream URLs

The public catalog endpoints are accessible without API key authentication. The formal developer program launched in 2012 is no longer actively maintained as a self-serve program; commercial integrations are handled through iHeartMedia partnership channels.

## Plans

- **Free** - $0/month, ad-supported, live radio, podcasts, artist stations, limited skips
- **iHeartRadio Plus** - $5.99/month, unlimited skips, instant replay, on-demand songs
- **iHeartRadio All Access** - $12.99/month, full on-demand library, offline downloads

## Links

- [Website](https://www.iheart.com)
- [Help Center](https://help.iheart.com)
- [Terms of Use](https://www.iheart.com/content/terms-of-use/)
- [GitHub](https://github.com/iheartradio)
- [Tech Blog](https://tech.iheart.com)
- [Pricing](https://help.iheart.com/hc/en-us/articles/20310091985549-iHeart-Plans)
- [Press Release - Developer Program Launch](https://www.iheartmedia.com/press/clear-channel-radio-launches-developer-program-iheartradio)
