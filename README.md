hire-me
=======

A template to facilitate your hire in a start-up work environment.


# `content.json`

This is where all of YOU go. it has the following format:

```json
{
  "cover" : {
    "title" : "title_of_the_cover_card",
    "content" : "text_below_the_cover_card [supports html formating]",
    "picture_name" : "name_of_the_picture_to_put_as_cover [1100px by 680px]"
  },
  "categories" : [
    {
      "title" : "title_of_the_first_set_of_card", 
      "cards" : [
        {
          "title" : "title_of the first card",
          "description" : "text_below_the_cover_card [ < 250 characters]",
          "picture_name" : "name_of_the_picture_to_put_above_card [720px by 445px]"
        },
        ...
      ]
    },
    ...
  ]
}
```


# Notes


## Pictures

There is a tight constraint if you want the picture to fill entirely its emplacement.
I made every picture div respect the golden ratio.

| sizes (px) | width | height |
|:----------:|------:|-------:|
|    cover   | 1100  |  680   |
|    card    |  720  |  445   |


If you don't want it to take the full width, the picture will be scaled to be seen in its entirety.
In this case, please use `png` files, and make sure they have an alpha channel (transparency).


## Text

The long text fields, namely `cover.content` and `categories[i].cards[j].description`
support html tags so you can insert links and use custom formatting.

The page is made to show pinpointed skills, and therefore should contain few text.
Please try to limit the text fields to the following:
*Keep in mind that it changes relative to the numbers of `i` you use :clap:*

|     field name     | max #characters |
|:------------------:|----------------:|
|    `cover.title`   |            ~12  |
|   `cover.content`  |              ∞  |
|     `card.title`   |            ~14  |
| `card.description` |           ~256  |



# Contribute

To contribute do not hesitate to send me pull requests !

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally
* Consider starting the commit message with an applicable emoji:
	* :lipstick: when improving the format/structure of the code
	* :racehorse: when improving performance
	* :non-potable_water: when plugging memory leaks
	* :memo: when writing docs
	* :bulb: Check out the Emoji Cheat Sheet for more ideas.




