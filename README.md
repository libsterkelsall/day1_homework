# day1_homework
HTML CSS Git: Code Refractor
<<<<<<< HEAD
TASK
to refactor an existing webpage to make it accessible
optimize website for search engine bots  
ensure access for people with disabilities 
ensure access for people with socio-economic restrictions (out-dated browsers and data restricitions)
try to leave code better than found it

Corrections to index.html

    altered description in <head> <title> to reflect company name on browser tab

    changed class 'header' section to semantic element selector of <header> so no class required

    changed selector for 'seo' in <header> from class to ID as unique

    changed <div> to <nav> to describe container for navigation  links

    corrected 'search engine optimization' href attribute to correct the link's destination

    changed container for main image from <div> to <section> with an ID selector for 'hero'rather than class as unique

    Inserted aria-label attribute to provide description of large image for image restricted web browsers, visually challenged visitors and search engine bots.

    changed container for main content from <div> to <article> with an ID selector for 'content' rather than class as unique

    removed ID selectors across all three <div> in content as superfluous

    consolidated each <div> in <article> to be part of the same class "optimization" in name and nature
   


    changed container for side bar from <div> to <aside> with an ID selector for 'benefits' rather than class as unique

    consolidated each <div> in <aside> to be part of the same class "benefit-insert" in name and nature


    changed container for footer from <div> to <footer> 





Corrections to CSS

    ?consider putting in more powerful reset of css to address other attributes than padding and margins

    ?consider putting in alternate colors for older or limited browsers

    reflect change of identifier for 'seo' from class to ID as unique

    reflect change of div container to nav element for navigation links

    ?consider removing 'calibri' as text in navigation secion as only microsoft

    removed code for 'list-style-type: none' as not adding anything

    ?consider changing margin for list items in navigation container from 25px to make more accessible across browsers

    WANTED to move coding for text paragraphs in selector 'p' in <article> (previously class "content") to after coding for 'hero' image in <section> so that it matches order of index.html doc

    WANTED to move coding for headings in selector 'h2' in <article>  so that it matches order of index.html doc

    reflect change of identifier for 'content' from class to ID as unique

    moved code for 'content' in <article> to follow order of index.html doc

    consolidated instructions for each of the three <div>s in the <article> container to respond to instructions for common class now named 'optimization'

    consolidated instructions for each of the three images in the <article> container to respond to instructions for common class 'optimization'


    changed <div> to <aside> to describe container for side bar listing benefits

    reflect change of identifier for 'benefits' from class to ID as unique

    Increased padding in ID 'benefits' to 42px to even with height of <article> beside it

    consolidated instructions for each of the three <div>s in the <aside> container to respond to instructions for common class now named 'benefit-insert'

    consolidated instructions for each of the three images in the <article> container to respond to instructions for common class 'optimization'


    changed <div> to <footer> to describe container for footer


=======

Corrections to index.html
    altered description in head
    fixed 'search engine optimization' button

Corrections to Css
    too scared
>>>>>>> 6480f76b5ec7c160f3542b10ca143a2cee291b32
