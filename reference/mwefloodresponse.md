# mwefloodresponse: Malawi Emergency Flood Response Water Point Survey (2019–2020)

This dataset contains water point assessment data collected during an
emergency flood response in Malawi between 2019 and 2020. The survey was
conducted under the BASEflow program to evaluate the status,
functionality, and safety of water points affected by flooding events.

## Usage

``` r
mwefloodresponse
```

## Format

A tibble with 319 rows and 40 variables

- submitted_on:

  Date and time the survey record was submitted

- district:

  Administrative district where the water point is located

- community:

  Name of the local community or village

- people_using:

  Number of people currently using the water point

- photo_water_point:

  link of photo showing the water point

- latitude:

  GPS latitude of the water point

- longitude:

  GPS longitude of the water point

- depth:

  Measured depth of the water source

- currently_submerged:

  Indicator of whether the water point is submerged at the time of
  survey

- likely_submerged:

  Assessment of whether the water point was submerged during the recent
  flooding

- functional_status:

  Operational status of the water point

- water_pump_possible:

  Ability to pump water at the time of the visit

- problems_reported:

  Observed or reported problems at the water point

- water_quality_problems:

  Issues affecting water quality

- civil_works_problems:

  Problems affecting the water point infrastructure

- photo_civil_works:

  link of photo showing civil works problems

- pump_problems:

  Problems observed with the water pump

- photo_pump_problems:

  link of photo showing pump problems

- pump_operational_feel:

  Subjective assessment of the pump operation

- time_to_pump_20l:

  Time taken to pump 20 liters of water

- strokes_to_yield:

  Number of strokes required to yield water

- sediment_presence:

  Presence or absence of sediment in the water

- water_quality_tests:

  Field tests performed on water quality

- electrical_conductivity:

  Measured electrical conductivity of the water

- conductivity_units:

  Units used for electrical conductivity measurement

- total_dissolved_solids:

  Measured total dissolved solids in water

- ph:

  Measured pH of the water

- temperature_c:

  Water temperature in Celsius

- turbidity_tube:

  Turbidity measured using a tube method

- turbidity_tube_units:

  Units used for turbidity tube measurement

- turbidity_electronic_ntu:

  Turbidity measured using an electronic turbidimeter

- comments:

  Additional observations recorded by the surveyor

- microbiological_test:

  Type of microbiological test performed

- test_method:

  Method used to perform the microbiological test

- sample_type:

  Type of water sample collected

- sample_date:

  Date the water sample was collected

- color_change_mpn:

  MPN count from color-change test indicating bacterial contamination

- color_change_upper95:

  Upper 95 percent confidence interval for MPN count

- color_change_health:

  Health risk classification based on color-change results

- color_change_image:

  link of photo showing compartments that changed color
