# Refactoring-Horiseon
There were several components of the html and css that needed to be refactored or changed.

The following items were completed in the html:
There were comments added above each section describing what was contained in the following section.
All <div>s were removed and replaced with semantic html tags. The tags used were header, nav, figure, content, figcaption, aside, and footer.
The "Search Engine Optimization" link was not working. After examining the code, I discovered, the link did not have a class defined to it. Inserting a class solved the broken link.
Following sequential headers, the H2 header in the footer was replaced with an H4 header.

The following items were completed in the CSS:
The headers (H1, H2, H3, & H4) were attached to a class, but since the headers were all used with the same section, they did not need a defined class. Additionally, since all the H2 and H3 headers contained the same properties, there was no need to seperate them by classes amd could just have their properties defined within H3. Lastly, since H1 was 48px and H2 was 36px, it made sense to have H3 be 24px and H4 be 12px.
I also reorganized the CSS to follow the organization of the html, moving all the content information above the aside information and having each class followed by their class img styles (if they have an image).