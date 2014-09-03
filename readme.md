<b>Tags ordering</b>

<p>Git-tag now supports tag.sort configuration, "to be used as the default sort order when no ‐‐sort= option is given." A good example of the usefulness of this new feature is provided by Tim Pettersen on Atlassian Blog, who suggest the following default sort to take into account version numbers in tags:

$ git config --global tag.sort version:refname
By setting the above default option, git tag will correctly order version numbers without requiring any specific sort option to override its default lexicographically ordering.

The new Git version also contains several changes aimed at improving performance and a bunch of bug fixes. More details can be found in the full release notes. The above mentioned article by Tim Pettersen is also worth reading since it collects his thoughts on "some aspects of the release that got us excited at Atlassian" and more extensive examples.
</p>
<p><b>ref: quora.com - [http://www.infoq.com/news/2014/08/git21-release-whats-new]</b></p>
