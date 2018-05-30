# Datasets



|           | Type                                   | Registration required | Access method              | Data URL                                                     | Access script(s)                                             | Analysis script(s)                            |
| --------- | -------------------------------------- | --------------------- | -------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | --------------------------------------------- |
| ECMWF ERA | Reanalysis                             | Yes                   | REST API                   |                                                              | https://github.com/grandey/ecmwf-data                        |                                               |
| TRMM      | Satelite (active) - precipitation      | No                    | FTP                        | ftp://trmmopen.gsfc.nasa.gov                                 | https://github.com/vightel/ojo-processing/blob/master/python/trmm_process.py  https://gist.github.com/cvitolo/9b5322be6fb940cc718a | https://github.com/sahg/pytrmm                |
| GPM       | Satelite (active) - precipitation      | Yes                   | FTP                        | https://pmm.nasa.gov/data-access/downloads/gpm  ftp://arthurhou.pps.eosdis.nasa.gov |                                                              |                                               |
| EUMETSAT  | Satellite (passive) - various products | Yes                   | web-form                   | http://archive.eumetsat.int/usc/                             |                                                              | https://github.com/guidocioni/eumetsat-python |
| GOES-16   | Satellite (passive) - various products | No                    | AWS S3                     | https://github.com/leifdenby/satdata/blob/master/aws_goes.py |                                                              |                                               |
| CMIP5     | Global climate simulations             | Yes                   | Python API (wget)          | https://rdrr.io/cran/wux/man/CMIP5fromESGF.html              |                                                              |                                               |
| obsio     | Surface observations                   | No                    | Python API (http requests) | https://github.com/jaredwo/obsio                             |                                                              |                                               |
| syphon    | Radiosonde observations                | No                    | Python API (http requests) | https://github.com/Unidata/siphon                            |                                                              |                                               |

