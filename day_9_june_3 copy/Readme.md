Yesterday, individuals & small groups worked at making their specific components work with the API. Some of the results can be seen in the Day 7 notes, as links (we skipped a day 8 document).

Today, we consolidated into 3 teams, with different goals

## Visualization

### Team members

* Jiran
* Zhihao
* Gaoyuan
* Jason

### Goals

* Split different graphs they built yesterday into separate views
	* XY Scatter/Line
	* Bar
	* Pie
* Breaking out vars into static file
* Applying dropdown menu variable select to each of the above pages
* Introducing routing to allow navigation btw / selection of different pages
* Setting heroku deployment env vars (no more hard-coding keys!)
* Readme
	* Deployment instructions
	* Description of how the viz app works

## Search/Filter

### Team members

* Jiacheng
* Alison
* Zewen
* Minghao

### Goals

* Make the different search components' settings dynamic
	* Rangeslider's min/max given via query to aggregations endpoint based on dropdown-selected variable
	* Autocomplete field's queries directed based on dropdown-selected variable
	* Radio
* Get human-readable labels from an options call piped into variable-selection dropdowns
* This single-page app should create and hold a search/filter object
	* For now, you could just display that as a pretty-printed text rendering of the json, on the page
	* Down the line, we have to figure out how to hand that search object off to the other teams' components
* Deploy to heroku

## Tables/Cards

### Team members

* Haoyu
* Lize

### Goals

* Deployment to Heroku
* Cards
	* Split field handling
		* And think about how we can attach different fields together when needed (e.g., source_ref to full_ref_text for specific references -- or captain_id to captain_name for interactivity)
	* Labels for vars
	* Tiled layout of cards
* Tables
	* Default columns
	* Select columns through integration of tree view (which Gaoyuan has already built)
	* Split field handling and labels for columns
