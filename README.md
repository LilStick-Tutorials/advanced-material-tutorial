# Lil Stick's Custom Advanced Material Tutorial

# GC ON TOP

![Example](https://i.imgur.com/tHb4qW1.png)

## Step 1
Open your in game console by pressing the ` key.

If you're unsure what the console key is then check the example below.

![Example](https://i.imgur.com/TLgOzZx.png "Logo Title Text 1")

## Step 2

Type the following into your console `mat_texture_list 1`

![Example](https://i.imgur.com/UpuvPM5.png "Logo Title Text 1")

## Step 3

Make sure you tick the following highlighted boxes

![Example](https://i.imgur.com/gmKNX9g.png)

## Step 4

Scroll through the list and find a texture you want.

In this example I'll be selecting a random face texture.

Click a texture you want and then a window will expand like this.

![Example](https://i.imgur.com/0YkWkqd.png)

Copy the directory with the file structure of `models/kleiner/walter_face`

Always make sure you're copying a file path and not the other text around it.

## Step 5

Paste the file path into your `Advanced Material` tool.

![Example](https://i.imgur.com/pD8Z81I.png)

## Step 6

Shoot your tool gun onto a prop, personally I like to use `2x2 or 3x3` plates in the prop menu

![Example](https://i.imgur.com/kW7vb4r.png)

Then you can just resize the materials by adjusting `Width Magnification` or `Height Magnification`

I also apply a shadow remover to the prop so you can see it more clearly.

## Step 7

This is the hard part, the more you look for textures you'll see different file names that need different file extentions.

For example `.cache` `.png` `.jpg`

Heres a few file types as an example

`cache/workshop/19803979021049036` This file type needs a `.cache` extention

`data/bricks_server/images/3918767357` This file type needs a `.png` extention.

`models/player/the303/doritos_coolranch2` This file type doesnt need an extention.

So as an example the `workshop` file structure needs a `.cache` at the end like this. `cache/workshop/19803979021049036.cache`

![Example](https://i.imgur.com/mEX6Vfz.png)

# For now the tutorial is finished!

Anything new I find I will post above and make a `Step 8`

If you have any isses with this tutorial or something I didnt explain very well please contact me on discord `ayystick` and I will adjust this. You can also make commits to github if you know how to use it!

# FAQ

Q. How do I find my gang image?

A. Gang images are stored in a file path called `bricks`. Search for `brick` in the filter menu at the top of the texture list screen. **REMEMBER** Gang images dont always load in for everyone, if you want this file to be visable to everyone then make sure you capture flags to force the clients PC to download the image from the server.
