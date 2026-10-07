# Foldspace support

English support website for Foldspace, hosted with GitHub Pages.

- Support: **swixer.support@icloud.com**
- Bug reports and ideas: <https://github.com/SwixerOfficial/foldspace-support/issues>
- Expected public URL after Pages is enabled: <https://swixerofficial.github.io/foldspace-support/>

## Publish

Commit and push the page files to `main`, then open the repository’s **Settings → Pages**:

1. Source: **Deploy from a branch**.
2. Branch: **main**, folder: **/ (root)**.
3. Save and wait for GitHub’s Pages deployment to succeed.
4. Open the deployed page and check both contact links before using its URL in App Store Connect.

Use the deployed page URL as **Support URL**. Publishing is separate from writing the local files; the expected URL above is not a deployment confirmation.

## Local preview

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Open <http://127.0.0.1:8765>. Stop with Ctrl-C.

The page uses plain HTML/CSS, a local copy of the Foldspace icon preview, native expandable answers, and system fonts. There is no build step, JavaScript, analytics, contact form, or external font dependency. The app itself and its source are maintained separately.
