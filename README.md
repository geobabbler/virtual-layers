GitHub GeoJSON Virtual Layers
=============================

Exploring the concept of storing GeoJSON features in individual files in a single repository and using virtual layers to visualize them.

This concept should enable:
- Applications to better circumvent GitHub file size limitations
- The ability to fetch only those features required by the application
- The ability to track edits/metadata for individual features (record level metadata)

Approach:
- A dataset is a repo,
- A record in the dataset is a file,
- The assemblage of the dataset is described by a vlayer file (json),
- Views of datasets can be described by other vlayer files (json),
- A (data.json)[http://project-open-data.github.io/schema/] file describes the dataset
- The vlayer and data.json files should be at the repo route



This approach is based upon a concept put forth by Mike Byrne.
