# gis-final-project
Team Oil Spill

This is a github repository for our GIS final group project (Lyric, Vittoria, Natalie) on predicting oil spill hotspots in the Mediterranean Sea using data from SkyTruth's Cerulean over the course of 2020-2025.

teamoilspilldatapull is a notebook that will pull data based on our filters from SkyTruth Cerulean's API on oil spills, and export that into two files (one with regular multipolygon geometry for eachs spill, and one with the coordinates for the centroids of each spill's polygon geometry). Because it is a notebook it will not run directly within github, so you will have to download the notebook and run it yourself. If you don't want to do that, we've also included the full teamoilspillcentroids data pull in this repository as well.

teamoilspillcentroids.csv is that full data pull.

To do: add hotspot predicting mechanism (ML??)
Upload notebook for DBSCAN clustering
