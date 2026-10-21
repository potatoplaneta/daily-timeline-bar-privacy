# Daily Timeline Bar privacy and support

Public privacy policy and support pages for the Daily Timeline Bar macOS app by PotatoPlanetStudios.

- Privacy policy: https://potatoplaneta.github.io/daily-timeline-bar-privacy/
- Support: https://potatoplaneta.github.io/daily-timeline-bar-privacy/support.html
- Private support and privacy requests: potatoplanet.studios@gmail.com
- Public bug reports: https://github.com/potatoplaneta/daily-timeline-bar-privacy/issues

## Publishing

GitHub Pages serves the root of `main`. No build step, dependencies, JavaScript, external fonts, cookies added by this site, or analytics are required. `.nojekyll` enables static hosting. Push changes to `main` to publish.

The layout follows [Wheel Launcher](https://github.com/potatoplaneta/wheel-launcher-privacy) and [Audio Router](https://github.com/potatoplaneta/audio-router-privacy). The colors use Daily Timeline Bar’s teal accent. PNGs are copied from its Daylight app icon assets.

For a local preview, run `python3 -m http.server 8789 --bind 127.0.0.1` and open http://127.0.0.1:8789/.

## App integration

The app’s `DailyTimelineBarPrivacyURL` and `DailyTimelineBarSupportURL` Info.plist keys point to these pages. The links are available in Settings and the Help menu. Use the same addresses in App Store Connect’s Privacy Policy URL and Support URL fields. Copyright: `2026 PotatoPlanetStudios`.

Content was checked against the app implementation on October 21, 2026. Recheck calendar fields, local retention, permissions, notifications, StoreKit and Keychain behavior, and support practices when the app changes. Keep private application source and user data out of this public repository. Update the effective date when the policy changes.

GitHub Issues are public and require an account. Direct private support and privacy requests to the email address above.

## References

- [Apple App Review Guidelines: privacy](https://developer.apple.com/app-store/review/guidelines/#privacy)
- [Apple app privacy details](https://developer.apple.com/app-store/app-privacy-details/)
- [Apple privacy policy](https://www.apple.com/legal/privacy/)
- [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)
- [Google Privacy Policy](https://policies.google.com/privacy)
