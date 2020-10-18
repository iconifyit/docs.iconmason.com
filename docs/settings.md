# Custom Search Settings

Icon Mason allows you to customize some of the default settings. Settings are stored in a JSON file in the `com.atomic` extensions data folder. You can find this folder in the following locations:

- Mac OS : `Users/$username$/Library/Application Support/com.atomic`
- Windows : `$username$\Documents\com.atomic`

The settings content looks like this: 

```JSON
{
    "searchConfig" : {
	  "shouldSort": true,
	  "tokenize": true,
	  "findAllMatches": true,
	  "threshold": 0.6,
	  "location": 0,
	  "distance": 100,
	  "maxPatternLength": 32,
	  "minMatchCharLength": 3,
	  "keys": [
		"file",
		"tags",
		"name"
	  ]
	},
	"tagsConfig" : {
		"minlength"    : 3,
		"maxlength"    : 128,
		"delimiters"   : [" ", "@", "--", "-", "$", "!", ".", ","],
		"separator"    : "-",
		"concatenator" : "~"
	}
}
```

## searchConfig 

Icon Mason uses the Fuse JS search library and supports all of the search config settings of the Fuse JS library. You can learn more about the configuration details at [FuseJS.io](https://fusejs.io/api/options.html)

## tagsConfig

You can customize how Icon Mason converts artboard names to icon tags. 

- minlength  : The minimum length word to convert to an icon tag
- maxlength  : The maximum length of a tag
- delimiters : The delimters to split into individual words
- separator  : The character on which to split the tags. Note that this is different from delimiting words. A tag can contain multiple words.
- concatenator : If you want to concatenate more than one word as a single tag, use the concatenator character.

