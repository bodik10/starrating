# starrating.js
jQuery plug-in that adds to a web-page the customised rating widget
Requires: jQuery (tested with v 1.11)

# Usage
`$("#dest").addStarRating(options);` // add rating widget to div container wich ID is 'dest'

# Options
JS object

Option | Type | Description
------ | ------ | ------ 
`width` | number | container max width
`img_filled` | string | path to filled star
`img_empty` | string | path to empty star
`input_id` | string | input's ID where rating value will be stored
`max`| number | amount of 'stars'
