::: {#main}
::: {#main-header}
::: {#breadcrumb-section}
1.  [Information Technology](index.html)
2.  [2.0 Architectures](2.0-Architectures_451824369.html)
:::

Infrastructure Architecture \_Mobile - Android {#title-heading .pagetitle}
==============================================
:::

::: {#content .view}
::: {.page-metadata}
Created by Ryan Kajiura, last modified on Mar 07, 2020
:::

::: {#main-content .wiki-content .group}
Author: [Ryan
Kajiura](https://wiki.pinnacle.com/display/~ryank){.confluence-userlink
.user-mention .current-user-mention}

\

Future You should minimize time spent doing "detective work" looking for
intricate project dependencies, so they would prefer a project that's as
reusable, readable, and recognizable as possible. These goals span a
single object all the way up to the entire project and lead to patterns
that fall into the following categories:

-   *Creational patterns:* how you *create* objects.
-   *Structural patterns:* how you *compose* objects.
-   *Behavioral patterns:* how you *coordinate* object interactions.

You may already be using one or several of these patterns already
without having A Capitalized Fancy Name for it, but Future You will
appreciate you not leaving design decisions up to intuition alone.

In the sections that follow, you'll cover the following patterns from
each category and see how they apply to Android:

*Creational*

-   Builder
-   Dependency Injection
-   Singleton

*Structural*

-   Adapter
-   Facade

*Behavioral*

-   Command
-   Observer
-   Model View Controller
-   Model View ViewModel
-   Clean Architecture

*Note:* This article isn't like a traditional
[raywenderlich.com](http://raywenderlich.com){.external-link} tutorial
in that it doesn't have an accompanying sample project that you can
follow along with. Treat it instead like an article to get you up to
speed to the different patterns you'll see used in our other Android
tutorials, and to discover ways to improve your own code.

\

\

\

\

\

\

\

\

\

::: {#expander-843350265 .expand-container}
::: {#expander-control-843350265 .expand-control}
References
:::

::: {#expander-content-843350265 .expand-content}
-   <https://www.raywenderlich.com/470-common-design-patterns-for-android-with-kotlin>
-   <https://academy.realm.io/posts/eric-maxwell-mvc-mvp-and-mvvm-on-android/>
:::
:::
:::
:::
:::

::: {#footer role="contentinfo"}
::: {.section .footer-body}
Document generated by Confluence on May 21, 2020 14:12

::: {#footer-logo}
[Atlassian](http://www.atlassian.com/)
:::
:::
:::
