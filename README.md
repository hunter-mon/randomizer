<script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script>$.fn.randomize = function(selector){
    var $elems = selector ? $(this).find(selector) : $(this).children(),
        $parents = $elems.parent();

    $parents.each(function(){
        $(this).children(selector).sort(function(){
            return Math.round(Math.random()) - 0.5;
        // }). remove().appendTo(this); // 2014-05-24: Removed `random` but leaving for reference. See notes under 'ANOTHER EDIT'
        }).detach().appendTo(this);
    });

    return this;
};
$('ul').randomize();
</script>
 
<div id="text"></div>

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/CyberRyder/randomizer/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Hello [here](https://pokemondb.net/news/260/new-sword-shield-trailer-reveals-galarian-forms-and-rivals#news-continue) is a link to Pokemon DB

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### ~~Markdown~~ 

<button id="target">RANDOMIZE</button>


I am planning to make a ~~randamizer~~ randomizer for pokemon.
- This
- Is
- So
- Cool


<script>$( "#target" ).click(function() {
  alert( "Handler for .click() called." );
});
</script>

Syntax highlighted code block

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

```

[Link](url)

![Image](https://img.pokemondb.net/artwork/vector/clawitzer.png)

Clawitzer: The Howitzer Pokemon

Type: Water

Ability: Mega Launcher

Moveset:

- Ice Beam

- Hidden Power Ground

- Water Pulse/Scald

- Aura Sphere/Dragon Pulse/Dark Pulse

For the last slot it is really just what your team needs most. Also, Water Pulse>Scald because thanks to Mega Launcher (Clawitzers Ability) Water Pulse has more power and a chance to confuse.

For more stuff on Clawitzer (I just picked it randomly \\\_( ' ' )\_/) See [this](https://pokemondb.net/pokedex/clawitzer).

I'll probably do alot of that kind af pokemon stuff and randomly post movesets and teams that I make. So you'll be seeing alot of that Clawitzer kind of stuff. :)

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/). (Not related to pokemon)

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/CyberRyder/randomizer/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
