+++
title = "DocDock Theme for Hugo"
description = ""
+++

# Hugo docDock theme
[Hugo-theme-docdock {{%icon fa-github%}}](https://github.com/vjeantet/hugo-theme-docdock) is a theme for Hugo, a fast and modern static website engine written in Go. Hugo is often used for blogs, **this theme is fully designed for documentation.**

This theme is a partial porting of the [Learn theme of matcornic {{%icon fa-github%}}](https://github.com/matcornic/hugo-theme-learn). and its default style "flex" comes from [facette.io](https://github.com/facette)'s documentation.

{{%panel%}}docDock works with a "page tree structure" to organize content : All contents are pages, which belong to other pages. [read more about this]({{%relref "content-organisation/_index.md"%}}) {{%/panel%}}

## Main features

* [Automatic Search]({{%relref "search/_index.md" %}})
* **Unlimited menu levels**
* [Generate RevealJS presentation]({{%relref "page-slide.md"%}}) from markdown (embededed or fullscreen page)
* Automatic next/prev buttons to navigate through menu entries
* [Image resizing, shadow...]({{%relref "create-page/page-images.md" %}})
* [Attachments files]({{%relref "meta/shortcodes/attachments.md" %}})
* [List child pages]({{%relref "meta/shortcodes/children/_index.md" %}})
* [Excerpt]({{%relref "meta/shortcodes/excerpt.md"%}}) ! Include segment of content from one page in another
* [Mermaid diagram]({{%relref "meta/shortcodes/mermaid.md" %}}) (flowchart, sequence, gantt)
* [Icons]({{%relref "meta/shortcodes/icon.md" %}}), [Buttons]({{%relref "meta/shortcodes/button.md" %}}), [Alerts]({{%relref "meta/shortcodes/alert.md" %}}), [Panels]({{%relref "meta/shortcodes/panel.md" %}}), [Tip/Note/Info/Warning boxes]({{%relref "meta/shortcodes/notice.md" %}}), [Expand]({{%relref "meta/shortcodes/expand.md" %}})
* [customizable look and feel]({{%relref "content-organisation/customize-style/_index.md"%}}), [theme style]({{%relref "content-organisation/customize-style/themestyle.md"%}}), [theme variants]({{%relref "content-organisation/customize-style/theme-variants.md"%}})

### Layout styles

This theme comes with two distinctive layout styles: Flex and Original. The main documentation is built with **Flex**, though available also in **[Original style](/original)**

#### Style "Flex" (default)

![](docdock-style-flex.png?classes=shadow)

#### Style "Original"

![](docdock-style-original.png?classes=shadow)

## Contribute to this documentation
Feel free to update this content, just click the **Edit this page** link displayed on top right of each page, and pullrequest it
{{%alert%}}Your modification will be deployed automatically when merged !{{%/alert%}}


## Documentation website
This current documentation has been statically generated with Hugo with a simple command : `hugo -t docdock` -- source code is [available here at GitHub {{%icon fa-github%}}](https://github.com/vjeantet/hugo-theme-docDock)

{{% panel theme="success" header="Automated deployments" footer="Netlify builds, deploys, and hosts  frontends." %}}
Automatically published and hosted thanks to [Netlify](https://www.netlify.com/).

Read more about [Automated HUGO deployments with Netlify](https://www.netlify.com/blog/2015/07/30/hosting-hugo-on-netlifyinsanely-fast-deploys/)
{{% /panel %}}

