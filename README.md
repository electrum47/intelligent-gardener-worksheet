# Intelligent Gardener Worksheet

This is a spreadsheet based off the book _The Intelligent Gardener_ by Steve
Solomon. You'll want to read the book before attempting to use this spreadsheet.
However, dialing in which ingredients to use with paper can be tedious, so
having it in a spreadsheet form where you can quickly tweak the numbers to try
to balance everything out makes the process somewhat easier.

The spreadsheet is in OpenOffice/LibreOffice Calc format. OpenOffice and
LibreOffice are free downloads.

## Download the Spreadsheet

[Download the spreadsheet](https://github.com/electrum47/intelligent-gardener-worksheet/raw/master/intelligent-gardener-worksheet.ods)

## About the Spreadsheet

### Colors

Color | Description
------|-------------
Yellow | These are the cells you should edit for the specific soil sample you are working with.
Light Blue | Once you've figured out what ratio of ingredients you want in your mix, the blue column is how many pounds of materials you need to acquire to cover the acreage you set in `Acres` in the cell `B4`.
Light purple | This is how many ounces you need to mix of each ingredient to mix a batch to cover 100 square feet.
Green | As you play with the ratio of ingredients, the `Total Left to Apply` for each periodic element will turn Green if you get the deficit amount close to zero. That means you have roughly the right amount of that element.
Red | As you play with the ratio of ingredients, the `Total Left to Apply` for each periodic elemtn will turn Red if you have too much of an element. If your soil started out with a surplus those columns might start off Red and there's nothing you can do about that. Just know that you should be careful about not applying too much more of that element.

### How to use the spreadsheet

#### Entering your soil sample results from Logan Labs

![image](https://user-images.githubusercontent.com/59991595/128973474-c04a65f7-cf12-471a-bb49-237e4e2dcad1.png)

First set how many `Acres` you want to buy ingredients for in column `B4`. Next
use your Logan Labs report and fill in `B1` to `B3` and `G` through `Q` on rows
`7` and `8`.

#### About the element rows

![image](https://user-images.githubusercontent.com/59991595/128973664-e3939320-3177-4d4f-a8d1-15c28c7e3a83.png)

Row `9`: `Target`, is what Steve Solomon thinks you should be targeting for your
soil conditions.

Row `10`: `Deficit`, is how much you're missing from that target in your current
soil; negative means you have an excess of that element.

Row `11`: `Apply`, is basically the same as `Deficit`, but it factors in the
maximum amounts Steve Solomon suggests you add each year, so it might have you
adding less then your deficit so that you slowly fix your soil over several
seasons.

Row `12`: `Total Applied`, shows how much of each element you're adding with the
mix of ingredients you've selected (see next section).

Row `13`: `Total Left to Apply` is how much more of that element you need to mix
into your ingredients before you hit what Steve Solomon recommends. Each element
in row 13 will turn green when you get that element close to what Steve
suggests, and will turn Red if you get too much.

#### About the ingredients section of the spreadsheet

![image](https://user-images.githubusercontent.com/59991595/128973858-5910b552-9824-4efa-b412-b3423b2fc721.png)

Column `A` on the far left is the name of each ingredient.

Column `B` will be how many pounds of each ingredient you need to buy in total
for your acreage.

Column `C` is where you will adjust how much of each ingredient to add (more on
this in next section).

Column `D` is how many ounces of each ingredient you need to mix to mix up a
batch to cover 100 square feet.

Columns `E` through `Q` are the percentage of that element that ingredient
contains. The chemical composition of each ingredient can vary by brand, region,
and possibly other things, so you might want to check your source and adjust the
exact percentages based off what exactly you plan on using. As an example Row
`19` is `Blood Meal`, and in the current spreadsheet based off the brand of
bloodmeal I had available, it contained `13%` Nitrogen (N) [Cell `E19`] and 0.5%
Phosphorus (P) [Cell `H19`]

#### Creating a mix

I'd recommend zeroing out the yellow values in column `C` which are part of the
example that comes with the spreadsheet, but will almost certainly not be useful
for you. Be careful not to touch the white values, such as for `Borax` (`C39`)
as those only have one option so the spreadsheet can give you exactly what you
need for that ingredient. After clearing out the values you can look at what you
need up on row `13` (`Total Left To Apply`) and find an ingredient you want to
try to use to address that deficiency, and start plugging in numbers for that
ingredient. As an example, let's say you see you need Calcium in cell `I13` you
might decide to use some `Calphos` from Row `31` to address that. Try setting
cell `C31` to `100`. Was that enough? If not, maybe try `200`, if it was too
much maybe back off to `75`. `Calphos` also brings with it Phosphorus, so at
some point you might end up with too much Phosphorus, but not enough Calcium, so
you might decide to use less `Calphos` and add some `AgLime`.

This process is probably more of an art then a science. I don't have any
concrete recommendations except to just keep playing with the ingredients until
you think you've gotten good enough. It doesn't have to be perfect, but the
better job you do at getting each element close to the target will probably
produce better end results.

Row `50`: `Azomite` doesn't target any elements. Steve (as well as the company
producing Azomite) suggest that you target a specific amount each year
regardless of your soil type. If you're using `Azomite` just enter the number
you'd like to use.

## Printing the ingredient list

Once you've decided on your mix, it's helpful to print it out so you have a hard
copy where-ever you're mixing your ingredients at. The ingredient list should
fit on a single page. To do this with Open Office/Libre Office highlight the
ingredient rows:

![image](https://user-images.githubusercontent.com/59991595/128975844-04c2ed28-d508-471c-8a19-a0104eb7465e.png)

And then click on `File` -> `Print...`

Under `Range and Copies` and `Include` find a `> More` and click to expand it:

![image](https://user-images.githubusercontent.com/59991595/128976460-1c0f7098-18c4-4fd0-8db4-60c7baea98f4.png)

Now set the `From which:` drop down to the value `Print Selected Cells`.

![image](https://user-images.githubusercontent.com/59991595/128976735-34d5ae4d-3a94-4535-b45e-8fae208bad0f.png)

Now you can go ahead and print and you'll only get the ingredients to mix.
