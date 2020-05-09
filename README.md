# Fuel-Economy-Data-Analysis

### Data on Cars used for Testing Fuel Economy

The test data used to determine fuel economy estimates is derived from vehicle testing done at EPA's National Vehicle and Fuel Emissions Laboratory in Ann Arbor, Michigan, and by vehicle manufacturers who submit their own test data to EPA.

Each year, EPA provides fuel economy data to the Department of Energy (DOE), the Department of Transportation (DOT) and the Internal Revenue Service (IRS) so that they can administer their fuel economy-related programs.

DOE publishes fuel economy label values in the annual Fuel Economy Guide (http://www.fueleconomy.gov).
DOT receives the manufacturers' fleet average fuel economy from EPA, and determines if manufacturers are complying with the federal corporate average fuel economy (CAFE) standards.
EPA provides IRS with the fuel economy data for vehicles which may be subject to the Gas Guzzler tax penalty. IRS is responsible for collecting those taxes from manufacturers. 

With this data, my goal was to analyze the fuel consumption by comparing the statistics of 2008 and 2018 and thus I utlized only that portion of data which can be downloaded from the below links,
2018 data: https://www.fueleconomy.gov/feg/EPAGreenGuide/Smartway/xls/SmartWay%20Vehicle%20List%20for%20MY%202018.xlsx
2008 data: https://www.fueleconomy.gov/feg/EPAGreenGuide/Smartway/xls/SmartWay%20Vehicle%20List%20MY%202008.xls

###### Below is a guide to understand the data:

Model – vehicle make and model<br>
Displ – engine displacement in liters
Cyl – number of engine cylinders
Trans – transmission type plus number of gears
 Auto - Automatic
 Man - Manual
 SemiAuto - Semi-Automatic
 SCV - Selectable Continuously Variable (e.g. CVT with paddles)
 AutoMan - Automated Manual
 AMS - Automated Manual-Selectable (e.g. Automated Manual with paddles)
 Other - Other
 CVT - Continuously Variable
 CM3 - Creeper/Manual 3-Speed
 CM4 - Creeper/Manual 4-Speed
 C4 - Creeper/Manual 4-Speed
 C5 - Creeper/Manual 5-Speed
 Auto-S2 - Semi-Automatic 2-Speed
 Auto-S3 - Semi-Automatic 3-Speed
 Auto-S4 - Semi-Automatic 4-Speed
 Auto-S5 - Semi-Automatic 5-Speed
 Auto-S6 - Semi-Automatic 6-Speed
 Auto-S7 - Semi-Automatic 7-Speed
Drive – 2-wheel Drive, 4-wheel drive/all-wheel drive
Fuel – fuel(s)
Cert Region –
 CA - California
 CE - Calif. + NLEV (Northeast trading area)
 CF - Clean Fuel Vehicle
 CL - Calif. + NLEV (All states)
 FA - Federal All Altitude
 FC - Tier 2 Federal and Calif.
 NF - CFV + NLEV(ASTR) + Calif.
 NL - NLEV (All states)
Stnd – vehicle emissions standard code. See Stnd Description.
Stnd Description – vehicle emissions standard description. See
https://www.epa.gov/greenvehicles/federal-and-california-light-duty-vehicle-emissions-standards-airpollutants
Underhood ID – engine family or test group ID. See
http://www.fueleconomy.gov/feg/findacarhelp.shtml#airPollutionScore
Veh Class – EPA vehicle class. See http://www.fueleconomy.gov/feg/findacarhelp.shtml#epaSizeClass
Air Pollution Score (Smog Rating) – see
http://www.fueleconomy.gov/feg/findacarhelp.shtml#airPollutionScore and
https://www.epa.gov/greenvehicles/smog-rating
City MPG – city fuel economy in miles per gallon
Hwy MPG – highway fuel economy in miles per gallon
Cmb MPG – combined city/highway fuel economy in miles per gallon
Greenhouse Gas Score (Greenhouse Gas Rating) – see
https://www.epa.gov/greenvehicles/greenhouse-gas-rating
SmartWay – Yes, No, or Elite. See https://www.epa.gov/greenvehicles/consider-smartwayvehicle
Comb CO2 – combined city/highway CO2 tailpipe emissions in grams per mile
