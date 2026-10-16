# do-rag-sitemaps

Uncompressed `.xml` mirrors of DigitalOcean public sitemaps for Gradient Knowledge Base ingestion.

Official www sitemaps are served as `.xml.gz`, which the KB API rejects (`Base URL must be a sitemap URL (.xml)`).
These files are gunzipped copies for use with `crawling_option: SITEMAP`.

Refresh periodically from `https://www.digitalocean.com/sitemap.xml` child shards.
