# Documentation for the Project Kleutghen Site # 
## Where We Left Off ##
Although GitHub Pages are always 'live' or 'served' on the internet, the project site is not ready to be published/presented. 
* 001 tab has the map, text comparison & analysis, additional reference links, and a space for the article on 
the 'Fragrant Concubine' by Teng. 
* other tabs are set up for text/image collections, a tab for the 010 & 011 texts, a search tab
* working contact page
## What it Needs ## 
* peer-reviewed pinyin and translation uploaded to the 001 tab
* peer-reviewed name for 001 to use throughout the website
* expanding the website to hold more data (more texts, images, FC map)

## How to Work on This Repo ##
* index.md (home page)
* navigation.yml (sets header links for tabs)
* footer.yml (sets footer links
* to create new pages (create new .html or .md files, set default to archive, css is set in the 

## Site Setup ##
from jekyll-theme-skinny-bones-master
* _site                               # compiled site ready to deploy
* images                             # unoptimized images
* includes                           # reusable blocks for _layouts
* _layouts
    * archive.html                   # archive listing of a group of posts or collection
    * article.html                   # articles, blog posts, text heavy material layout
    * default.html                   # base
    * home.html                      # home page
      * media.html                     # portfolio, work, media layout
* _posts                              # posts grouped by category for sanity
* _sass
   * vendor                          
      * bourbon                     # Bourbon mixin library   
        * neat                        # Neat grid library
* _animations.scss                # CSS3 animations
    * _badges.scss                    # small badges
    * _bullets.scss                   # visual bullets
    * _buttons.scss                   # buttons
    * _grid-settings.scss             # Neat settings         
    * _helpers.scss                   # site wide helper classes
    * _layout.scss                    # structure and placement, the bulk of the design
    * _mixins.scss                    # custom mixins
    * _notices.scss                   # notice blocks
    * _syntax.scss                    # Pygments.rb syntax highlighting
    * _reset.scss                     # normalize and reset elements
    * _sliding-menu.scss              # sliding menu overlay
    * _variables.scss                 # global colors and fonts
        * css
          * main.scss                       # loads all Sass partials
    * fonts                               # webfonts
    * images                              # images
      * js
        *plugins                         # jQuery plugins
        * vendor                          # vendor scripts that don't get combined with the rest
        * _main.js                        # site scripts and plugin settings go here
          * main.min.js                     # concatenated and minified site scripts
 * index.md                            # homepage content
    * _config.yml                         # Jekyll settings
