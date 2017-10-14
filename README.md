zotero-csl
==========================

Zotero allows you to customize existing styles or roll your own. I don't need anything so different as would move me to roll my own, but I do want to hack the Chicago style. Whenever I remember to, which is most of the time, I store a URI for any books I'm considering in Zotero so that I can get back to the catalog listing when I want. (Zotero doesn't store the whole thing, natch.)

However, the Zotero devs assumed that any book entry with a value in the URI is likely to be an electronic edition, a perfectly sensible assumption given the purposes behind the Zotero metadata fields; seems like the assumption is that if a person doesn't want something in the citation, they'll put that in a Note. Well, not me, I'm just contrary that way.

So I did a small hack to the template for the Chicago full note and note styles so that it wouldn't by default include the URI. When I need to, I can change the style, or in the final submission I can convert the fields in my Word document and sever the link with Zotero, allowing me to edit the citations ad hoc and append URIs where desired.


Installation
-------------

The documentation team is in the process of updating doco for the Zotero 5.0 release, but [their v4.x documentation](https://www.zotero.org/support/dev/citation_styles/style_editing_step-by-step) worked substantially the same for me.