## Icy Mars 
The hands-on will be based on a pre-produced QGIS project. Data layers are described in the Icy Mars data info.
Relevant references are included below.
## Hands-on short guide
Objectives: 

Geological and morphological mapping of the Moreux Crater area on Mars, focusing on crater-related, glacial-like and aeolian landforms.

Data required: 

CTX image
Steps involved (quick description / screenshots, etc.):
Delineate linear features and geological units, focusing on impact-related, glacial-like, and aeolian morphologies.

Expected result:

Obtain a geological map of Moreux Crater and study the characteristics of a glacier-like form near the central peak.
Task short guide

Objective:

Create a geological map of Moreux Crater.

Data required:

CTX image

## Steps involved (quick description / screenshots, etc.):

1.	Mapping of crater units: rims, scarps, floor, central peak, and rough apron textures;
2.	Mapping of glacial landforms: valley glacier-like features on crater rims and central peak;
3.	Mapping of aeolian landforms: dunes;
4.	Identification of small impact craters;
5.	Focusing on the central peak glacier, highlighted by a polygon and mapping its different linear features.

Expected results:

A geomorphological map of the crater, with particular emphasis on the glacial features in the area. 
Mapping in detail the central peak glacier using linear features.

## References

Rishitosh K. Sinha, S.V.S. Murty, Amazonian modification of Moreux crater: Record of recent and episodic glaciation in the Protonilus Mensae region of Mars, Icarus, Volume 245, 2015, Pages 122-144, https://doi.org/10.1016/j.icarus.2014.09.028.

## Data package availability

https://zenodo.org/doi/10.5281/zenodo.1051574

## Coordinate Reference System (CRS)

Mars (2015) / Ocentric / Equirectangular, clon = 0
Proj4 CRS 
+proj=eqc +lat_ts=0 +lat_0=0 +lon_0=0 +x_0=0 +y_0=0 +a=3396190 +b=3376200 +units=m +no_defs

WKT CRS
PROJCRS["Mars (2015) / Ocentric / Equirectangular, clon = 0",
    BASEGEODCRS["Mars (2015) / Ocentric",
        DATUM["Mars (2015)",
            ELLIPSOID["Mars (2015)",3396190,169.894447223612,
                LENGTHUNIT["metre",1]],
            ANCHOR["Viking 1 lander: 47.95137 W"]],
        PRIMEM["Reference Meridian",0,
            ANGLEUNIT["degree",0.0174532925199433]],
        ID["IAU",49902,2015]],
    CONVERSION["Equirectangular, clon = 0",
        METHOD["Equidistant Cylindrical",
            ID["EPSG",1028]],
        PARAMETER["Latitude of 1st standard parallel",0,
            ANGLEUNIT["degree",0.0174532925199433],
            ID["EPSG",8823]],
        PARAMETER["Longitude of natural origin",0,
            ANGLEUNIT["degree",0.0174532925199433],
            ID["EPSG",8802]],
        PARAMETER["False easting",0,
            LENGTHUNIT["metre",1],
            ID["EPSG",8806]],
        PARAMETER["False northing",0,
            LENGTHUNIT["metre",1],
            ID["EPSG",8807]]],
    CS[Cartesian,2],
        AXIS["(E)",east,
            ORDER[1],
            LENGTHUNIT["metre",1]],
        AXIS["(N)",north,
            ORDER[2],
            LENGTHUNIT["metre",1]],
    ID["IAU",49912,2015]]

