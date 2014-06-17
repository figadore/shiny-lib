Contains Array2XmlTrait, based on Lalil Patel's class

Install with composer
```
"require": {
    "shinymayhem/shiny-lib": "dev-master"
}
```
override protected properties
_convertSpaces: boolean, whether to run str_replace on node_names (default: true)
_convertSpacesString: what to replace spaces with (default: "-")
_allowNumericTags: boolean, whether to allow numeric tags (default: true)
_numericTagPrefix: what to prefix numeric tags with (default: "element-")
