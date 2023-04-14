---
layout: default
title: Home
nav_order: 1
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
permalink: /
---

### 별 헤는 밤 입숨

내일 어머님, 어머니, 말 까닭이요, 별 하나에 이런 버리었습니다. 내린 그리고 하나에 까닭이요, 있습니다. 강아지, 차 잔디가 별을 것은 이국 노루, 토끼, 나의 봅니다. 내 지나가는 어머님, 무성할 겨울이 벌써 가난한 청춘이 잠, 거외다. 이제 추억과 멀리 어머님, 새워 하나에 봅니다. 시와 별을 아스라히 것은 마리아 밤이 이름을 동경과 거외다. 토끼, 때 슬퍼하는 어머니, 이국 강아지, 덮어 까닭입니다. 멀듯이, 나는 가슴속에 당신은 하나에 봄이 봅니다. 어머님, 파란 어머니, 하나에 하나의 이 언덕 듯합니다. 새워 당신은 내일 이름과, 내 별을 피어나듯이 걱정도 무덤 있습니다.

다 위에 비둘기, 계십니다. 하나 했던 밤을 아직 어머니 쉬이 이름을 너무나 나는 까닭입니다. 부끄러운 계집애들의 나는 아이들의 노루, 별 이름과, 쉬이 하나에 듯합니다. 남은 봄이 걱정도 봅니다. 별빛이 내 책상을 이름을 아이들의 한 새워 까닭입니다. 하나에 별에도 딴은 너무나 소학교 까닭이요, 벌써 있습니다. 동경과 벌레는 멀리 별에도 쓸쓸함과 이름을 강아지, 멀리 있습니다. 차 내일 별 무덤 별 하나에 겨울이 때 노루, 거외다. 어머니 별이 토끼, 어머님, 다하지 이웃 까닭입니다. 이름자 하나에 남은 하나에 아직 이국 있습니다.

# Focus on writing good documentation
{: .fs-9 }

Just the Docs gives your documentation a jumpstart with a responsive Jekyll theme that is easily customizable and hosted on GitHub Pages.
{: .fs-6 .fw-300 }

[Get started now](#getting-started){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }
[View it on GitHub][Just the Docs repo]{: .btn .fs-5 .mb-4 .mb-md-0 }

---

{: .warning }
> This website documents the features of the current `main` branch of the Just the Docs theme. See [the CHANGELOG]({% link CHANGELOG.md %}) for a list of releases, new features, and bug fixes.

Just the Docs is a theme for generating static websites with [Jekyll]. You can write source files for your web pages using [Markdown], the [Liquid] templating language, and HTML.[^1] Jekyll builds your site by converting all files that have [front matter] to HTML. Your [Jekyll configuration] file determines which theme to use, and sets general parameters for your site, such as the URL of its home page.

Jekyll builds this Just the Docs theme docs website using the theme itself. These web pages show how your web pages will look *by default* when you use this theme. But you can easily *[customize]* the theme to make them look completely different!

Browse the docs to learn more about how to use this theme.

## Getting started

The [Just the Docs Template] provides the simplest, quickest, and easiest way to create a new website that uses the Just the Docs theme. To get started with creating a site, just click "[use the template]"!

{: .note }
To use the theme, you do ***not*** need to clone or fork the [Just the Docs repo]! You should do that only if you intend to browse the theme docs locally, contribute to the development of the theme, or develop a new theme based on Just the Docs.

You can easily set the site created by the template to be published on [GitHub Pages] – the [template README] file explains how to do that, along with other details.

If [Jekyll] is installed on your computer, you can also build and preview the created site *locally*. This lets you test changes before committing them, and avoids waiting for GitHub Pages.[^2] And you will be able to deploy your local build to a different platform than GitHub Pages.

More specifically, the created site:

- uses a gem-based approach, i.e. uses a `Gemfile` and loads the `just-the-docs` gem
- uses the [GitHub Pages / Actions workflow] to build and publish the site on GitHub Pages

Other than that, you're free to customize sites that you create with the template, however you like. You can easily change the versions of `just-the-docs` and Jekyll it uses, as well as adding further plugins.

{: .note }
See the theme [README][Just the Docs README] for how to use the theme as a gem without creating a new site.

## About the project

Just the Docs is &copy; 2017-{{ "now" | date: "%Y" }} by [Patrick Marsceill](http://patrickmarsceill.com).

### License

Just the Docs is distributed by an [MIT license](https://github.com/just-the-docs/just-the-docs/tree/main/LICENSE.txt).

### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. Read more about becoming a contributor in [our GitHub repo](https://github.com/just-the-docs/just-the-docs#contributing).

#### Thank you to the contributors of Just the Docs!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"></a>
  </li>
{% endfor %}
</ul>

### Code of Conduct

Just the Docs is committed to fostering a welcoming community.

[View our Code of Conduct](https://github.com/just-the-docs/just-the-docs/tree/main/CODE_OF_CONDUCT.md) on our GitHub repository.

----

[^1]: The [source file for this page] uses all three markup languages.

[^2]: [It can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#creating-your-site).

[Jekyll]: https://jekyllrb.com
[Markdown]: https://daringfireball.net/projects/markdown/
[Liquid]: https://github.com/Shopify/liquid/wiki
[Front matter]: https://jekyllrb.com/docs/front-matter/
[Jekyll configuration]: https://jekyllrb.com/docs/configuration/
[source file for this page]: https://github.com/just-the-docs/just-the-docs/blob/main/index.md
[Just the Docs Template]: https://just-the-docs.github.io/just-the-docs-template/
[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[Just the Docs repo]: https://github.com/just-the-docs/just-the-docs
[Just the Docs README]: https://github.com/just-the-docs/just-the-docs/blob/main/README.md
[GitHub Pages]: https://pages.github.com/
[Template README]: https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[customize]: {% link docs/customization.md %}
[use the template]: https://github.com/just-the-docs/just-the-docs-template/generate
