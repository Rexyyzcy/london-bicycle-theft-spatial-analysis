# London Bicycle Theft: Crime Mapping and Spatial Analysis

A 2024 UCL **SECU0022 Crime Mapping and Spatial Analysis** coursework project examining recorded bicycle theft in Greater London, with a closer look at Southwark. The report combines thematic maps, spatial clustering, kernel-density maps, and monthly and seasonal comparisons to show how conclusions change with geographic scale and the choice of denominator.

## Start with the report

[Read the 13-page illustrated report](report/london-bicycle-theft-spatial-analysis.pdf). It includes the final maps, interpretation, and limitations. The original Word submission was converted to PDF for this portfolio copy; the candidate number and document author metadata were removed from the copy.

## Methods and skills

- **GIS mapping:** compared bicycle-theft counts across London boroughs, inner-London output areas, and Southwark wards in ArcGIS Desktop / ArcMap.
- **Spatial analysis:** used nearest-neighbour analysis and kernel-density estimation to examine clustering and local hotspots; the report gives an overall nearest-neighbour index of 0.47 for the Southwark analysis.
- **Temporal analysis:** compared monthly counts and seasonal hotspot maps to show that concentrations change over time.
- **Risk adjustment:** contrasted raw ward counts with theft rates per 1,000 people at risk using a population denominator informed by residential and workday populations.
- **Interpretation:** discussed aggregation bias, administrative boundaries, older census data, and sensitivity to kernel-density settings before recommending how maps might inform resource allocation.

The work used ArcMap and CrimeStat as part of the original coursework. The PDF is the best way to view the finished maps without specialist software.

## ArcMap project files

The five archived `.mxd` files are in [map-projects](map-projects/):

| File | Focus |
| --- | --- |
| `Assignment1.mxd` | Core mapping work |
| `Assignment1_month.mxd` | Monthly hotspot maps |
| `Assignment1_season.mxd` | Seasonal hotspot maps |
| `Assignment1_q3.mxd` | Ward-level crime counts |
| `Assignment1_q4.mxd` | Population-adjusted crime-rate mapping |

These are **historical ArcMap documents, not standalone datasets**. They reference local GIS layers that are not included here, so opening them in ArcGIS Desktop may require relinking sources; I have not retested them in ArcMap for this portfolio publication. Old local Windows usernames embedded in the project paths were replaced in these public copies. The source `.mxd` files and Word document were not modified.

The large working GIS dataset, course-provided boundary files, and assessment feedback are not published here. The report contains the maps needed to review the analysis.
