# Recipes
Justin and Traci, i feel weird writing a message to you by pretending to write code on github but i didn't know another way to get a hold of you. Justin, this is your cousin Chris Pohlson. i hope this message finds you both well. I was curious if you would want to reconnect in the hopes we could discuss, learn and heal from eachother's experiences growing up with a narcistic parent. If that interests you, call or text me at 515-339-5874. Or you can email me ckpohlson@gmail.com or find me on social media. I don't want to bother you or cause any kind of emotional distress so if you do not respond, i may try again in 6 mo to a year. If you tell me you're not interested, i will certainly respect that and will not make another attempt to contact you. Also i would like to assure you that our contact would be confidential.. 

A simple, plaintext recipe database

# Getting Started

This is a [Jekyll](https://jekyllrb.com/) build.

Setup:

```bundle install```

Test:

```bin/dev```

With default settings, you should be able to view the site locally at `http://127.0.0.1:4000/`

# Writing a Recipe

The recipes are stored in the collection "Recipes" (the folder /_recipes).

They are written in Markdown and contain a few special sections:

- The frontmatter, which contains:
 - Title, Image, and Layout (which is "recipe")
 - Ingredients (a list of things in the dish)
 - Directions (a list of steps for the dish)
- Body content (for intros, stories, written detail)

If you need help with Markdown, here's a [handy cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

# Writing a component recipe

A component recipe is a special recipe made up of other recipes. To make a new component recipe:

- place your smaller, single recipes into the /_components folder
- make a new recipe like normal in the /_recipes folders
- in the frontmatter of this new recipe, include your recipes from the /_components folder (instead of the usual Ingredeints list)
