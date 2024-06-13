### Stats
[![EarthKiii's GitHub stats](https://github-readme-stats.vercel.app/api?username=EarthKiii&show_icons=true&theme=radical)](https://github.com/anuraghazra/github-readme-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=EarthKiii&layout=compact&theme=radical)](https://github.com/anuraghazra/github-readme-stats)

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FEarthKiii%2F&count_bg=%234B4B4B&title_bg=%232F7BF3&icon=python.svg&icon_color=%23EDEA55&title=Visitors&edge_flat=false)](https://hits.seeyoufarm.com)

### Links
[![Fiverr](https://upload.wikimedia.org/wikipedia/commons/1/18/Fiverr_Logo_09.2020.svg)](https://www.fiverr.com/silensteam?up_rollout=true)

#### Hubble
https://github.com/HubbleTeam

```stl
solid """
endsolid
```

```topojson
{
  "type": "Topology",
  "transform": {
    "scale": [0.0005000500050005, 0.00010001000100010001],
    "translate": [100, 0]
  },
  "objects": {
    "example": {
      "type": "GeometryCollection",
      "geometries": [
        {
          "type": "Point",
          "properties": {"prop0": "value0"},
          "coordinates": [4000, 5000]
        },
        {
          "type": "LineString",
          "properties": {"prop0": "value0", "prop1": 0},
          "arcs": [0]
        },
        {
          "type": "Polygon",
          "properties": {"prop0": "value0",
            "prop1": {"this": "that"}
          },
          "arcs": [["1"]]
        }
      ]
    }
  },
  "arcs": [[[4000, 0], [1999, 9999], [2000, -9999], [2000, 9999]],[[0, 0], [0, 9999], [2000, 0], [0, -9999], [-2000, 0]]]
}
```

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
            // OPTIONAL: default ""
            // A title to show when this item is clicked or
            // hovered over
            "title": "A title",

            // OPTIONAL: default ""
            // A description to show when this item is clicked or
            // hovered over
            "description": "A description",

            // OPTIONAL: default "medium"
            // specify the size of the marker. sizes
            // can be different pixel sizes in different
            // implementations
            // Value must be one of
            // "small"
            // "medium"
            // "large"
            "marker-size": "medium",

            // OPTIONAL: default ""
            // a symbol to position in the center of this icon
            // if not provided or "", no symbol is overlaid
            // and only the marker is shown
            // Allowed values include
            // - Icon ID
            // - An integer 0 through 9
            // - A lowercase character "a" through "z"
            "marker-symbol": "bus",

            // OPTIONAL: default "7e7e7e"
            // the marker's color
            //
            // value must follow COLOR RULES
            "marker-color": "#fff",

            // OPTIONAL: default "555555"
            // the color of a line as part of a polygon, polyline, or
            // multigeometry
            //
            // value must follow COLOR RULES
            "stroke": "#555555",

            // OPTIONAL: default 1.0
            // the opacity of the line component of a polygon, polyline, or
            // multigeometry
            //
            // value must be a floating point number greater than or equal to
            // zero and less or equal to than one
            "stroke-opacity": 1.0,

            // OPTIONAL: default 2
            // the width of the line component of a polygon, polyline, or
            // multigeometry
            //
            // value must be a floating point number greater than or equal to 0
            "stroke-width": 2,

            // OPTIONAL: default "555555"
            // the color of the interior of a polygon
            //
            // value must follow COLOR RULES
            "fill": "#555555",

            // OPTIONAL: default 0.6
            // the opacity of the interior of a polygon. Implementations
            // may choose to set this to 0 for line features.
            //
            // value must be a floating point number greater than or equal to
            // zero and less or equal to than one
            "fill-opacity": 0.5
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
              [-90,35],
              [-90,30],
              [-85,30],
              [-85,35],
              [-90,35]
          ]
        ]
      }
    }
  ]
}
```