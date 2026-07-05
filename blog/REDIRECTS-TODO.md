# Redirect setup (do this in Wix, not in this repo)

GitHub Pages has no server-side redirect layer, so a `_redirects` file (that's
Netlify-only) does nothing here. The redirects need to happen on the OLD
domain, since that's what's currently indexed by Google and bookmarked by
readers.

**Where:** palani.ch → Wix Dashboard → Settings → SEO Tools → URL Redirect Manager

Add a 301 redirect for each row below (old path on palani.ch → full new URL on kannan.ch):

| Old path (palani.ch) | New URL (kannan.ch) |
|---|---|
| /post/moralityinvipassana | https://kannan.ch/blog/moralityinvipassana/ |
| /post/institutionalmemory | https://kannan.ch/blog/institutionalmemory/ |
| /post/__mse | https://kannan.ch/blog/mse/ |
| /post/saasobituary | https://kannan.ch/blog/saasobituary/ |
| /post/capitalandclock | https://kannan.ch/blog/capitalandclock/ |
| /post/purposefulpivot | https://kannan.ch/blog/purposefulpivot/ |
| /post/kovai | https://kannan.ch/blog/kovai/ |
| /post/heroes | https://kannan.ch/blog/heroes/ |
| /post/whybeforewhat | https://kannan.ch/blog/whybeforewhat/ |
| /post/vidai | https://kannan.ch/blog/vidai/ |
| /post/partnership | https://kannan.ch/blog/partnership/ |
| /post/clock | https://kannan.ch/blog/clock/ |
| /post/unconsciousbias | https://kannan.ch/blog/unconsciousbias/ |
| /post/mulai-1 | https://kannan.ch/blog/mulai/ |
| /post/insead | https://kannan.ch/blog/insead/ |

Note most of these old paths and new paths are now identical apart from the
domain — that's intentional, since slugs were kept as single words rather
than rewritten for extra SEO keyword weight.

Once these are live on Wix and you're ready to fully retire palani.ch, you can
also set a site-wide redirect from palani.ch itself → https://kannan.ch,
as a fallback catch-all for anything not covered above.

Note: palani.ch is expected to eventually become the German-language site
(see plan discussion) rather than disappearing entirely — treat that as a
separate future project once kannan.ch is fully live.
