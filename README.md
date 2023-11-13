# Data-driven story editor

Hey there. This is a demo for a very simple data-driven story editor.

This is my new content



<FlatUiTable url="https://storage.openspending.org/alberta-budget/__os_imported__alberta_total.csv" />

## Formatting

I can do  ***<u>formatting</u> here, as you can see.***

## Storage

I can also save this .md file. (check out the url for this page)

## Maps

Simple map example:

<Map layers={[
  {
    "data": "https://opendata.arcgis.com/datasets/9c58741995174fbcb017cf46c8a42f4b_25.geojson",
    "name": "Points",
    "tooltip": {
      "propNames": [
        "Location"
      ]
    }
  }
]} title="Roads in York"  />

## Data visualization

Lastly, we can create custom "components" on this editor. Check out this table:

<FlatUiTable url="https://storage.openspending.org/alberta-budget/__os_imported__alberta_total.csv" />

And this chart

<LineChart data="https://raw.githubusercontent.com/datasets/oil-prices/main/data/wti-year.csv" xAxis="Date" yAxis="Price" />

...
