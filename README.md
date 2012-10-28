# City Lots San Francisco in .json

I needed a really big `.json` file for testing various code.

The CityLots spatial data layer is a representation of the City and County of San Francisco's Subdivision parcels. The initial file is in the `.shp` (shapefile) format and as the conversion process is quite cumbersome I uploaded the data as a `.json` file. 

Warning: size is 189,9 MB.

## Default data

The initial file can be downloaded from [San Francisco Data](https://data.sfgov.org/Geography/City-Lots-Zipped-Shapefile-Format-/3vyz-qy9p).

## Converting .shp to .json

- download the `.zip` file from [San Francisco Data](https://data.sfgov.org/Geography/City-Lots-Zipped-Shapefile-Format-/3vyz-qy9p)
- install [gdal](http://gdal.org/)
- help for installing on a mac can be found [here](http://spatialanalysis.co.uk/2010/11/installing-rgdal-on-mac-os-x/) and [here](http://trac.osgeo.org/gdal/wiki/BuildingOnMac)
- install [shp2json](https://github.com/substack/shp2json) via `npm install shp2json -g`
- run `$ shp2json citylots.zip citylots.json` from the command line

## Acknowledgements

- substack's [shp2json](https://github.com/substack/shp2json)

## License

Copyright (C) 2012 [Mirco Zeiss](mailto: mirco.zeiss@gmail.com)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.