---
title: >-
  Segment interpretation and validation data - Land Cover Mapping, North Slope
  of the Arctic National Wildlife Refuge, Alaska, 2019
created: '2021-02-25T22:43:33.591963'
modified: '2021-02-25T22:43:33.591970'
state: active
type: dataset
tags:
  - Anwr
  - Arctic Coastal Plain
  - Classification
  - Ecological Land Survey
  - Habitat
  - Land Cover
  - Mapping
  - North Slope
  - Remote Sensing
  - Soil Analysis
  - Vegetation
groups: []
csv_url: 'https://ecos.fws.gov/ServCat/DownloadFile/195492?Reference=130649'
json_url: ''
layout: post

---
The field data and WorldView imagery were leveraged to generate an extensive set of segments labeled with land cover class. These segment interpretations provided the training and validation data for the mapping. Analysts reviewed each aerial and ground plot from the 2019 field survey, examining the plot center and training polygon over the WorldView mosaic, and reviewing field photos, cover estimates, and notes. For each plot, one image segment was identified as the primary example of the vegetation type of the plot (unless there was no suitable example segment, as in cases when a ground plot was targeting a small but distinct vegetation patch that was not captured in the image segmentation). Usually, the primary segment included or was close to the nominal plot center, but this was not always the case, since the target area for the aerial plots could encompass several segments.

After identifying a primary segment, the analyst also identified a set of 0–15 secondary segments that were good examples of the same vegetation type. This assessment was informed by field experience, review of field photos of the landscape setting, and photo-interpretation of the WorldView mosaic.

An additional set of auxiliary segments were identified and assigned to a land cover class. The first set of auxiliary segments was assigned to non-vegetated classes such as lakes, ponds, ocean, barrens, and snowfields or aufeis. While a limited effort was expended to sample such classes during field work, we knew that these would be readily identifiable with high confidence from the WorldView imagery and so focused the field sampling on vegetated classes. 

Later, after reviewing preliminary models and receiving feedback from Janet Jorgenson (retired plant ecologist for the Arctic Refuge), we added additional auxiliary segments for vegetated classes based on expert photo interpretation. These were designed to provide the model with additional training data to define the breakpoints between similar classes.

Land cover classes were assigned to all of the primary, secondary, and auxiliary segments. 20% of the segments were randomly selected to be withheld from model training. The final model was validated using the reserved validation segment interpretation points (20% of the full set). These segments were not used to develop the model. The map class was extracted from the final land cover map for each validation point. A confusion matrix, overall accuracy metrics, and per-class performance metrics were calculated from the validation data.
