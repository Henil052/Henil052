# Install your new GitHub profile

Your main download contains **README.md** and the **assets** folder. Upload both to the top level of your existing profile repository, **Henil052/Henil052**.

## Fastest method: use the GitHub website

1. Extract **Henil-GitHub-Profile.zip** on your computer.
2. Open [your profile repository](https://github.com/Henil052/Henil052).
3. Choose **Add file → Upload files**.
4. Drag in **README.md** and the entire **assets** folder from inside the extracted folder. Keep the folder structure. Do not upload the ZIP itself or nest everything inside another folder.
5. Commit the changes, then open [your profile](https://github.com/Henil052).

The animated header, terminal typing, circuit lines, and footer are contained in SVG files. They start when the images load; there is no npm install, hosting account, or API key to set up. Technology icons are bundled locally too.

If GitHub's upload page will not replace your existing README, upload the assets folder first, then edit the existing README and replace its contents with the downloaded README.md.

## Included

- Custom animated header, with a separate mobile layout
- Typing effect, blinking terminal cursor, and moving circuit accents
- Matching LinkedIn, email, and project buttons
- Four project cards with concise, accurate descriptions
- Bundled technology icons with light and dark variants
- Live email and LinkedIn links, plus a verified link to your Shopping System CLI
- An optional contribution snake workflow in `extras/`
- A local preview page and an editable source generator for the original artwork

## Preview before uploading

Open **preview.html** in a browser from the extracted folder. It uses the README HTML returned by GitHub's Markdown API, with local styling that approximates GitHub. The actual profile page may differ slightly in spacing and font rendering. Use the preview's theme buttons to check both modes.

Animation follows the system's reduced-motion preference. If your computer requests reduced motion, the SVG artwork remains readable and static.

## Add the contribution snake

Follow **extras/CONTRIBUTIONS.md**. It is an optional extra because it needs one successful GitHub Actions run before the contribution images can be displayed. Its workflow is not enabled just by uploading the main files.

## Personalize later

- Edit normal profile wording, project descriptions, and links in **README.md**.
- Update the contact buttons' destination URLs in the README; their SVGs control appearance only.
- Edit **extras/build-assets.py** and run `python3 extras/build-assets.py` to regenerate the original SVG artwork. This does not overwrite your README or the bundled technology icons.
- Add the Android, MongoDB, and cryptography repository links once you choose the public repositories you want to feature. Their links have deliberately not been guessed.

The core profile is ready to upload. Your GitHub account has not been modified.

## References and credits

[GitHub's profile README requirements](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme): the repository must be public, its name must match your username, and README.md must be in the repository root.

Technology icons: [Skill Icons](https://github.com/tandpfun/skill-icons), distributed under the MIT license included in **assets/skill-icons-LICENSE.txt**. Names and logos identify their respective technologies. The banner, buttons, project illustrations, and footer are original SVG artwork created for this profile.
