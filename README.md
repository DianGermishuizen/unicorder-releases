# Unicorder updates

The update feed and disk images for Unicorder's direct download (outside the Mac App Store). The app reads `appcast.xml` from https://updates.unicorder.app/appcast.xml, which a Cloudflare Worker serves from this repo (`wrangler.jsonc`, deployed on every push). The disk images are assets of the `updates` release.

Files are added by `scripts/release.sh --publish` in Unicorder's source repo, never by hand. The app's source is not here.
