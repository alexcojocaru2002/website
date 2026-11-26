# Alex Cojocaru

A minimal personal website. Plain HTML and CSS; no build step or JavaScript.

## Local preview

From this directory, run:

```sh
python3 -m http.server 8000
```

Open <http://localhost:8000>. Edit `index.html` for content and `styles.css`
for appearance. The site uses Space Grotesk via Google Fonts, with system
sans-serif fallbacks if the font cannot load.

The original bachelor's date range was `2021 - 2014`. The page shows only
the start year until the correct end year is confirmed.

## Remove `/website` from the GitHub Pages URL

The current repository, `alexcojocaru2002/website`, is a project site. GitHub
Pages gives project sites a URL containing the repository name:

<https://alexcojocaru2002.github.io/website/>

To serve the personal website at <https://alexcojocaru2002.github.io/>:

1. Check that the account does not already have a repository named
   `alexcojocaru2002.github.io`. GitHub allows one user site per account.
2. In this repository's **Settings → General → Repository name**, rename
   `website` to `alexcojocaru2002.github.io`.
3. Under **Settings → Pages**, confirm the publishing source. For this static
   site, choose **Deploy from a branch**, select the branch containing these
   files, and select **/ (root)** as the folder.
4. Update the local remote after renaming:

   ```sh
   git remote set-url origin git@github.com:alexcojocaru2002/alexcojocaru2002.github.io.git
   ```

5. Push the updated files to the selected publishing branch and wait for the
   Pages deployment to finish.

Stylesheet URLs are relative and section links use fragments, so this source
works at `/`, `/website/`, or a custom domain without changing its asset paths.
The ML Blog keeps its separate `/ml-blog/` URL.

Renaming the repository does not redirect the old GitHub Pages URL. If keeping
the old `/website/` links working matters, create the user-site repository
separately and keep the existing `website` repository as a redirect page.

## Use a custom domain instead

GitHub Pages also supports a domain you own, without renaming this repository:

1. Register or use an existing domain.
2. Set it under **Settings → Pages → Custom domain** for this repository.
3. Follow GitHub's instructions to configure the domain's DNS records, verify
   the domain, and enable **Enforce HTTPS** once the certificate is available.

With branch publishing, GitHub saves the configured domain in a `CNAME` file.
Keep that file in the publishing branch. No `CNAME` is included here because
no custom domain has been selected.

References:

- [GitHub Pages site types](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages)
- [Creating a GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
- [Renaming a repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/renaming-a-repository)
- [Managing a custom domain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site)
