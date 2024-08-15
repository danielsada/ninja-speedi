# ninja-speedi
A collection of recipies, times and formulas for ninja speedi. 

I love my ninja speedi, but I'm afraid the recipes, times and everything might get lost over time. I want to make sure I have the recipies and calculators here. 

This intends to have in the future:
- A calculator for custom meals
- Everything in the quick start guide in base proteins.

## TODO
- Get a good JSON for all the info I need. This is just to lay out some of the site.
- Reverse engineer the https://ninjatestkitchen.com/speedi-recipe-builder/

## To deploy:

To generate main.css
```
wget https://github.com/tailwindlabs/tailwindcss/releases/download/v3.4.10/tailwindcss-linux-x64
chmod +x tailwindcss-linux-x64 
mv tailwindcss-linux-x64 tailwindcss
./tailwindcss -w -o assets/main.css
```

To serve:
```
hugo serve
```