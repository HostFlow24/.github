# HostFlow24 organization profile

This public repository contains the GitHub organization profile, localized project overviews and brand assets for [HostFlow24](https://github.com/HostFlow24).

## Repository layout

| Path | Purpose |
| --- | --- |
| [profile/README.md](profile/README.md) | English introduction and language selector displayed on the public organization page. |
| [profile/README.en.md](profile/README.en.md) | English project overview, one text link and a clickable logo leading to the English website. |
| [profile/README.it.md](profile/README.it.md) | Italian project overview, one text link and a clickable logo leading to the Italian website. |
| [assets](assets) | Logos, organization avatar and repository social preview. |

GitHub displays `profile/README.md` on the [HostFlow24 organization page](https://github.com/HostFlow24). This repository must remain public for that profile to be visible. See [GitHub's organization profile documentation](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile#adding-a-public-organization-profile-readme).

## Updating the profile

1. Keep the introduction in `profile/README.md` short and in English.
2. Maintain each project overview in `profile/README.<language-code>.md`, using the language named by its code. To add another language, create its overview and add it to the language selector and this repository's layout table.
3. Include one text link to the website in each localized overview, pointing to the homepage in that language, and link its logo to the same homepage. In `profile/README.md`, link the logo to `https://www.hostflow24.com`, where visitors can choose a language, and keep the language selector focused on the localized overviews. Use canonical URLs without a trailing slash, such as `https://www.hostflow24.com/en` and `https://www.hostflow24.com/it`.
4. Describe what the product does and who it is for, without development status. Keep the meaning consistent across translations. Use absolute GitHub URLs for profile navigation and images so they also work from the organization page, and reuse the brand assets in `assets`.

Commit and push updates to `main` to publish them on GitHub.
