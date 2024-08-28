# HG_simulation
we conducted a simulation using GEOS-Chem with a 2° × 2.5° resolution, firstly.
The simulation's regional coverage ,level number and meteorological data are as follows:
 longitude:
    range: [72.0, 136.0]
    center_at_180: true 
  latitude:
    range: [17.5, 54.0]
    half_size_polar_boxes: false
  met_field: MERRA2(2020)
  number_of_levels: 47

Subsequently, we obtained the boundary conditions, which were used for the finer resolution simulations：GEOSChem.BoundaryConditions.********_0000z.nc4
Then we conducted a simulation using GEOS-Chem with a 0.5° × 0.625° resolution，the data processing and plotting codes are also included.
