# hacolp-cds
Canadian Historical GIS Partnership repository for Historical Atlas of Canada Census Division population maps.

The Canadian Historical GIS Partnership Development project is developing web-mapping pilot projects for several collaborating organizations, using a variety of data sets. For more information see project website at www.geohist.ca. <br>
This repository holds code for the Open Source versions of the pilot projects for the Historical Atlas of Canada Online Learning Project. For more information see the website at www.historicalatlas.ca <br>

The web-mapping pilot project chosen from the Historical Atlas content are the 3 map series showing Population Growth, Density, and Distribution for Canada by Census Division over the time period 1851-1961. These maps were originally published online as part of the Historical Atlas Online as the chapter Summary of Population Growth, 1851-1961. <br> http://www.historicalatlas.ca/website/hacolp/national_perspectives/population/UNIT_25/index.htm. <br>

The re-designed maps in this site use a time-line slider to display changes in population more smoothly and easily than the original layer-checkbox design. This web-map was developed using Mapbox-GL and data-driven layers (https://www.mapbox.com/help/gl-dds-map-tutorial/). The Time slider was adapted from a generic  jQuery slider (https://api.jqueryui.com/slider/) tied to Mapbox GL layer to filter based on Census Division information and the YEAR attribute.
