# About
This is the repo for the https://neovim.com.br landing page. It's for help new neovim users to understand how it works. I'm using hugo to bundle it.
I also forked and translated in Portuguese the neovim kickstart https://github.com/OuthBack/kickstart-pt-br.nvim

![image](https://github.com/OuthBack/neovim.com.br/assets/65133825/cadb70b8-6e5e-4ff9-84c6-d4ac66450807)

# Hugo
## Using

1. [Install Hugo](https://gohugo.io/installation/)
2. Clone this repository

```bash
git clone https://github.com/gohugoio/hugoBasicExample.git
cd hugoBasicExample
```

3. Clone the repository you want to test. If you want to test all Hugo Themes then follow the instructions provided [here](https://github.com/gohugoio/hugoThemes#installing-all-themes)

4. Run Hugo and select the theme of your choosing

```bash
hugo server -t YOURTHEME
```

5. Under `/content/` this repository contains the following:

- A section called `/post/` with sample markdown content
- A headless bundle called `homepage` that you may want to use for single page applications. You can find instructions about headless bundles over [here](https://gohugo.io/content-management/page-bundles/#headless-bundle)
- An `about.md` that is intended to provide the `/about/` page for a theme demo

6. If you intend to build a theme that does not fit in the content structure provided in this repository, then you are still more than welcome to submit it for review at the [Hugo Themes](https://github.com/gohugoio/hugoThemes/issues) repository
