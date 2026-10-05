# Border Realm privacy policy site

This directory is designed to be the root of a **dedicated public GitHub
repository**, so publishing the privacy page does not publish the game's source
or assets. The workflow publishes only `index.html` through GitHub Pages.

The policy wording now matches the mixed-audience age screen and 18+-only ad
behavior in the game source. Recheck it against the final packaged build before
publishing. The live site will
be available at `https://<github-account>.github.io/<repository-name>/` after
GitHub Pages is enabled and the workflow completes. Add that final URL to the
Play Console and the Android game's Settings screen.

## Publish

1. Create a public GitHub repository named `border-realm-privacy-policy`.
2. Copy the contents of this directory into its root and push them to `main`.
3. In the repository settings, enable GitHub Pages with **GitHub Actions** as
   the source.
4. Wait for **Publish privacy policy** to finish, then open the URL reported
   by that workflow and confirm it loads without signing in.
5. Use the published page URL in Play Console and add it in-game.

Publishing this separate site does not require making the game repository
public.
