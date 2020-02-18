# Encryption Works: How to Protect Your Privacy in the Age of NSA Surveillance

**Important:** The documentation provided here is out of date, and preserved in read-only format.
For up-to-date advice on using encryption to protect yourself, see our
[Digital Security Training guides](https://freedom.press/training/).

----------

> *Encryption works. Properly implemented strong crypto systems are one of the few things that you can rely on. Unfortunately, endpoint security is so terrifically weak that NSA can frequently find ways around it.*
>
> — Edward Snowden, answering questions live on the [Guardian's website](http://www.guardian.co.uk/world/2013/jun/17/edward-snowden-nsa-files-whistleblower)

On July 2, 2013, [Freedom of the Press Foundation](https://pressfreedomfoundation.org/) published this whitepaper entitled Encryption Works. You can find the original [online](https://pressfreedomfoundation.org/encryption-works) or in the PDF and ODT format in the "original" folder.

This version has been converted to markdown so it can be easily tracked in git and collaboratively edited. The guide itself is in [encryption_works.md](https://github.com/micahflee/encryption-works/blob/master/encryption_works.md).

## Contributing

We welcome any contributions, either as commits or as discussions in the [issues](https://github.com/freedomofpress/encryption-works/issues). Please look at the [contribute](CONTRIBUTING.md) file for more information.

## Hosting and Distributing with Pandoc

The source of the document is `encryption_works.md`, which is written in Markdown using the [Pandoc extensions]. Pandoc can render the document to HTML, PDF, or a number of other output formats.

To do so, first [install Pandoc](http://johnmacfarlane.net/pandoc/installing.html). Once it is installed, you can render the `.md` to `.html` with

    $ pandoc -s -t html5 encryption_works.md -o encryption_works.html

If you want to render pdf, make sure you follow the instructions on the Pandoc installation page to install LaTeX for your platform. Then:

    $ pandoc -s -t latex encryption_works.md -o encryption_works.pdf

For further information on conversion options, see the [Pandoc README] or man page.

[Pandoc extensions]: http://johnmacfarlane.net/pandoc/README.html#pandocs-markdown "Pandoc Markdown extensions"
[Pandoc README]: http://johnmacfarlane.net/pandoc/README.html "Pandoc README"

This work is licensed under [Creative Commons Attribution 3.0 Unported License](https://creativecommons.org/licenses/by/3.0/).

---

Freedom of the Press Foundation

[@freedomofpress](https://twitter.com/freedomofpress) | info@freedom.press

GPG: 0x734F6E707434ECA6C007E1AE82BD6C9616DABB79
