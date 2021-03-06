# Creating Shop Items

Creating new titles for players to purchase from the shop is an easy process.

All shop items are stored in a folder called `Data Items` as data.  These are scripts that do nothing but have properties about the shop item.

## Data Items

Expand the `Perk - Title Shop` folder and take a look in the `Data Items` folder.

In here you will see the current title that have been setup for the example.

![](/images/title-shop/2.png)

## Create Perk

Create your perk for the shop item.

<iframe width="560" height="315" src="https://www.youtube.com/embed/Er6gkLnTl5s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Create Item

!!! tip
	Make sure to deinstance the template so you can modify it.

Add a new copy of the `Perk_Title_Shop_Item_Data` script to the `Data Items` folder.  This script has various properties we can set to setup the new shop item.

| Property Name | Description |
| ------------- | ----------- |
| `perk` | The perk for this item. |
| `id` | A unique ID for this title. |
| `title` | The title. |

<iframe width="560" height="315" src="https://www.youtube.com/embed/BERKKHTaYBM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Now enter player mode and test out to see if your new shop item shows up.

<iframe width="560" height="315" src="https://www.youtube.com/embed/YE0ixCt4Q38" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>