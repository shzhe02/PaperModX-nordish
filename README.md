## PaperModX - Nord-like fork

This is a nord-like fork (hence "nordish") of the Hugo theme [PaperModX](https://github.com/reorx/hugo-PaperModX).

The color scheme is essentially all of those from [Nord](https://www.nordtheme.com/) with the addition of #22272F, which is a darker shade of #2E3440 (nord0). This change only affects the dark theme. However, the light theme exclusively uses the colors from the original Nord color scheme.

Additionally, a fix was implemented for the header colors as there was a bug where the color of a selected header stays the same across both light and dark mode, causing it to be unreadable when dark mode is used.

### Extra features

I have since implemented a couple new features:
- Mermaid diagrams can now be enabled with the site/page parameter `mermaid: true`.
  - To use Mermaid diagrams in your post, simply make a regular mermaid codeblock.
- Katex can be activated with the site/page parameter `math: true`.
  - To use Katex expressions in your post, simply use the `$$ /* your math here */ $$` format.

### Disclaimer

I am not a graphics designer, and my knowledge of color theory essentially amounts to "Wow, color looks nice". I am not affiliated with the team behind the Nord theme in any way, I just think it looks really nice.

---

### Helpful links:

[PaperModX documentation](https://reorx.github.io/hugo-PaperModX/)

[Demonstrator site (my blog)](https://shzhe02.com/)
