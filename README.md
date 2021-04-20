# Frontiers3Dmorphology
Repository of data created and analyzed for the study: Colony-level 3D photogrammetry reveals that total linear extension and initial growth do not scale with complex morphological growth in the branching coral, Acropora cervicornis.

Acer3DMorphologyData.csv -> csv file containing phenotype data for 156 coral colonies used in the experiment

Key:
  Each row represents a single coral colony and all of the phenotype data associated with it
  Site: Reef site that coral was outplanted to;
  Tag: ID tag give to a coral at outplanting site (1-30 tags at each site);
  Genotype and Nursey group: indicate clonal lineage of each coral, nursery group numbers were assigned to genotypes;
  Frag ID: position of coral ramet in an array of 30 ramets of the same genet at the coral nursery;
  T0_Method: method of phenotyping coral at nursery time point
  
  *Point measures for the each trait are indicated by time point first (T0,T6, or T12) then the trait. 
  *Growth measures for each trait are indicated by the trait first then start and end time point (e.g. TLE_0.6 = growth in TLE from T0 to T6)*
  
  TLE: total linear extension;
  SA: surface area of coral tissue;
  V: volume of coral colony;
  Vcx: volume of convex hull;
  SAcx: surface area of convex hull (includes added surface area created on bottom of coral colony where no living tissue exists;
  Vinter: volume of interstitial space (volume of convx hull - volume of coral colony);
  FieldTLE: by-hand measures by divers taken in the field;
  SAtoV: surface area to volume ratio of coral colony;
  T12_Dead, T12_TOD, T12_Status: all pertain to whether or no a colony was alive after 12 months, this study only used coral that survived to T12;
  CumulativeBreaks: breakage events observed from photographic taken every 3 month during first year of outplanting;
  Status: whether a coral was observed to experience 1 or more breakage events over the first year of outplanting
  
  
ImageCaptureSpecs.csv  -> csv file containing the number of photographs used to build individual coral models from 6 and 12 months in addition to the colony measurements, n= 427 and includes all models built in the experiment including colonies that were excluded due to incomplete data across the 3 time points

ModelOutputSpecs.xlsx  -> excel file containing Metashape output details for 200 coral models built for this study

ModelPrecisionSpecs.csv -> csv file containing measurements for technical replicates of a single coral model used for assessing the precision of the 3D photogrammetry method
