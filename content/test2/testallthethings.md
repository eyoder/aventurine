---
title: "test all the things"
description: ""
date: "2017-04-24T18:36:24+02:00"
weight: 3000
tags: ["dogs","cats"]
---


## test more things

No sign of any...wait! Coming in point three five. I see them. I'm in range. Target's coming up! Just hold them off for a few seconds.
<!--more-->

Keep your eyes open for those fighters! There's too much interference! Red Five, can you see them from where you are? No sign of any...wait! Coming in point three five. I see them. I'm in range. Target's coming up! Just hold them off for a few seconds.  
[Learn more about another thing - link with relref shortcode &gt;]({{< relref "testmorethings.md" >}})

[Learn more about this top level page - link with md syntax &gt;](/test)


## h2 heading

At the rate they're gaining... Traveling through hyperspace isn't like dusting crops, boy! 

{{%panel%}}this is a panel - Rendezvous at mark six point one. This is it!{{%/panel%}}

> this is a blockquote - We should be able to see it by now. Keep your eyes open for those fighters! There's too much interference! Red Five, can you see them from where you are? No sign of any...wait! Coming in point three five. I see them. I'm in range. Target's coming up! Just hold them off for a few seconds.

All wings report in. Red Ten standing by. Red Seven standing by. Red Three standing by. Red Six standing by. 
[Learn more about other things &gt;]({{ relref "testmorethings.uk.md" }}) 


* Red Nine standing by. 
  * Red Two standing by.
      * Red Three standing by.
          * Lock S-foils in attack position. 
          * We're passing through their magnetic field
      * Red Eleven standing by.
      * Another Red thing standing by.
* Red Five standing by. 
  * Lock S-foils in attack position. 
  * We're passing through their magnetic field. 

Hold tight! Switch your deflectors on. Double front!

1. Red Nine standing by. 
1.  Red Two standing by.
  * Red Three standing by.
        * Lock S-foils in attack position. 
        * We're passing through their magnetic field
  * Red Eleven standing by.
      * Another Red thing standing by.
1. Red Five standing by. 
  * Lock S-foils in attack position. 
  * We're passing through their magnetic field. 

Hold tight! Switch your deflectors on. Double front!

### anchor link test

We should be able to see it by now. Keep your eyes open for those fighters! There's too much interference! Red Five, can you [see them from where you are](#standard-headings-and-paragraphs)? No sign of any...wait! Coming in point three five. I see them. I'm in range. Target's coming up! Just hold them off for a few seconds.


#### images

50% width

![image](http://4.bp.blogspot.com/-fNb_bQ73BtY/Ukxu3SJ5E_I/AAAAAAAAK3M/o5FX1b6FHXo/s1600/Menace+42.png?width=50%)


#### alerts

{{%alert%}}Something important to know{{%/alert%}}

#### notices

Types: note, info, tip, warning

Note

{{% notice note %}}
Things happen every day.
{{% /notice %}}

info

{{% notice info %}}
You can also ... do a thing.
{{% /notice %}}

tip

{{% notice tip %}}
If you ...do this thing...you'll get some benefit.
{{% /notice %}}

warning

{{% notice warning %}}
Don't do this.
{{% /notice %}}


#### panels

Types: success, info, warning, danger

success

{{% panel theme="success" header="You did good!" footer="Aventurine is awesome." %}}
I thought you said this thing was fast. Watch your mouth, kid, or you're going to find yourself floating home.{{%/panel%}}

info 

{{% panel theme="info" header="Something happened." footer="Aventurine is awesome." %}}
I thought you said this thing was fast. Watch your mouth, kid, or you're going to find yourself floating home.{{%/panel%}}

warning

{{% panel theme="warning" header="Something is broken." footer="Aventurine is awesome." %}}
I thought you said this thing was fast. Watch your mouth, kid, or you're going to find yourself floating home.{{%/panel%}}

danger

{{% panel theme="danger" header="Danger, Will Robinson!" footer="Aventurine is awesome." %}}
I thought you said this thing was fast. Watch your mouth, kid, or you're going to find yourself floating home.{{%/panel%}}


### excerpt

This is an excerpt from another file - with this shortcode, we can duplicate chunks of copy, images, or code anywhere!

{{%excerpt-include filename="test/testmorethings.md" panel="this is an excerpt, pulled from another file" /%}}


### expand

{{%expand "How awesome is this???" %}}<br />
SO. VERY. AWESOME.<br />
SO. VERY. AWESOME.<br />
SO. VERY. AWESOME.<br />
SO. VERY. AWESOME.<br />
SO. VERY. AWESOME.<br />
SO. VERY. AWESOME.<br />
SO. VERY. AWESOME.<br />
SO. VERY. AWESOME.<br />
SO. VERY. AWESOME.<br />
{{% /expand%}}



### test using backtick code fence {#back}

should use Chroma instead of Pygments

### api example

```curl
https://integration.store.nest.com/v1/bulk/PARTNERNAME/orders/BATCH_ID  \
--digest  \
-u USERNAME:PASSWORD  \
-H "Content-Type: text/json" -H "Accept: application/json"  \
-X POST --data-binary @batch_file.json

```

#### html example

```html
<h2>thing</h2>

<p>A Nest thermostat test kit, or at least one Nest thermostat that is added to the Nest Account you&rsquo;ll use for testing.</p>

<ul>
<li>Partial pallet orders are available (one layer, for example), for an additional charge. Contact your {{&lt; p-program-manager &gt;}} for more information.</li>
</ul>


```

### json example
```json
{
    "glossary": {
        "title": "example glossary",
		"GlossDiv": {
            "title": "S",
			"GlossList": {
                "GlossEntry": {
                    "ID": "SGML",
					"SortAs": "SGML",
					"GlossTerm": "Standard Generalized Markup Language",
					"Acronym": "SGML",
					"Abbrev": "ISO 8879:1986",
					"GlossDef": {
                        "para": "A meta-markup language, used to create markup languages such as DocBook.",
						"GlossSeeAlso": ["GML", "XML"]
                    },
					"GlossSee": "markup"
                }
            }
        }
    }
}
```

### test using highlight shortcode

{{< highlight  "linenos=inline" >}}

curl https://integration.store.nest.com/v1/bulk/PARTNERNAME/orders/BATCH_ID  \
--digest  \
-u USERNAME:PASSWORD  \
-H "Content-Type: text/json" -H "Accept: application/json"  \
-X POST --data-binary @batch_file.json

{{< / highlight >}}




{{< highlight json >}}
{
    "glossary": {
        "title": "example glossary",
		"GlossDiv": {
            "title": "S",
			"GlossList": {
                "GlossEntry": {
                    "ID": "SGML",
					"SortAs": "SGML",
					"GlossTerm": "Standard Generalized Markup Language",
					"Acronym": "SGML",
					"Abbrev": "ISO 8879:1986",
					"GlossDef": {
                        "para": "A meta-markup language, used to create markup languages such as DocBook.",
						"GlossSeeAlso": ["GML", "XML"]
                    },
					"GlossSee": "markup"
                }
            }
        }
    }
}
{{< /highlight >}}


## standard headings and paragraphs

### h3 heading

Without precise calculations we could fly right through a star or bounce too close to a supernova and that'd end your trip real quick, wouldn't it? 

#### h4 heading

What's that flashing? We're losing our deflector shield. Go strap yourself in, I'm going to make the jump to light speed.

##### h5 heading

It looks like an Imperial cruiser. Our passengers must be hotter than I thought. Try and hold them off. Angle the deflector shield while I make the calculations for the jump to light speed. 

###### h6 heading

Stay sharp! There are two more coming in, they're going to try to cut us off. Why don't you outrun them? I thought you said this thing was fast. Watch your mouth, kid, or you're going to find yourself floating home. We'll be safe enough once we make the jump to hyperspace. Besides, I know a few maneuvers. We'll lose them! Here's where the fun begins!

