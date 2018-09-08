---
title: "even more things"
description: ""
date: "2017-04-24T18:36:24+02:00"
weight: 3010
tags: ["dogs","cats"]

---

### codefence examples

Hokey religions and ancient weapons are no match for a good blaster at your side, kid. I’m surprised you had the courage to take the responsibility yourself. 
<!--more-->


Don’t act so surprised, Your Highness. You weren’t on any mercy mission this time. Several transmissions were beamed to this ship by Rebel spies. I want to know what happened to the plans they sent you.


### api call example

```
https://integration.store.aventurine.com/v1/orders/BATCH_ID  \
--digest  \
-u USERNAME:PASSWORD  \
-H "Content-Type: text/json" -H "Accept: application/json"  \
-X POST --data-binary @batch_file.json

```

#### html example

```
<h2>thing</h2>

<p>There’s too much interference! Red Five, can you see them from where you are? No sign of any…wait! Coming in point three five.</p>

<ul>
<li>Without precise calculations we could fly right through a star or bounce too close to a supernova and that’d end your trip real quick, wouldn’t it?</li>
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


