# USAID_Jal_Jangal_RFP (04.03.2024)
USAID Biodiversity Jal Jangal Request for proposal.

# Maps of 4 major landscapes of Nepal 

- Chitwan Annapurna Conservation Landscape
- Karnali Conservation Landscape
- Kailash Sacred Convervation Landscape
- Terai Arc Convervation Landscape

# Chitwan Annapurna Conservation Landscape

"GaPa_NaPa" in ( 'Rupa' , 'Annapurna' , 'Modi' , 'Aandhikhola' , 'Phedikhola' , 'Rainas' , 'Bhanu' , 'Byas' , 'Chum Nubri' , 'Thori' , 'Nashong' , 'Narphu' )

"DISTRICT" in ('ARGHAKHANCHI', 'BAGLUNG', 'CHITAWAN', 'DHADING', 'GORKHA', 'GULMI', 'KASKI', 'LAMJUNG', 'MAKWANPUR', 'MANANG', 'MUSTANG', 'MYAGDI', 'NAWALPARASI_E', 'NAWALPARASI_W', 'NUWAKOT', 'PALPA', 'PARBAT', 'RASUWA', 'SYANGJA', 'TANAHU')

# Karnali Conservation Landscape

"GaPa_NaPa" in ( 'Chhayanath Rara' , 'Soru' , 'Mugum Karmarong' , 'Kanakasundari' , 'Patrasi' , 'Aathabis' , 'Thantikandh' , 'Chamunda Bindrasaini' , 'Barahtal' , 'Panchpuri' , 'Chaukune')

"DISTRICT" in ('ACHHAM' , 'BAJURA', 'DADELDHURA', 'DAILEKH', 'DOLPA', 'DOTI', 'JAJARKOT', 'JUMLA', 'KALIKOT', 'MUGU', 'RUKUM', 'SAIYAN', 'SURKHET')

# Terai Arc Convervation Landscape

"GaPa_NaPa" in ( 'Rapti' , 'Gadhawa' , 'Madhuwan' , 'Dhangadhi' , 'Laljhadi' , 'Krishnapur' , 'Alital' )

"DISTRICT" in ('ARGHAKHANCHI', 'BANKE', 'BARA', 'BARDIYA', 'CHITAWAN', 'DANG', 'KAILALI', 'KANCHANPUR', 'KAPILBASTU', 'MAKWANPUR', 'NAWALPARASI_E', 'NAWALPARASI_W', 'PALPA', 'PARSA', 'RAUTAHAT', 'RUPANDEHI')

# Kailash Sacred Convervation Landscape

"GaPa_NaPa" in ( 'Lekam' , 'Marma' , 'Apihimal' , 'Mahakali' , 'Dasharathchanda' , 'Thalara' )

"DISTRICT" in ('BAITADI', 'BAJHANG', 'DARCHULA', 'HUMLA')

Reference of districts : https://wwfasia.awsassets.panda.org/downloads/conservation_landscapes_of_nepal.pdf


###

One of the critical challenges for VRA is finding the climate data at the scale of local municipalities. Nepal has limited climate stations that are sparsely located. Most of the stations have climate data that spans less than 30 years. Therefore, we will use ERA5 climate reanalysis product by ECMWF (https://climate.copernicus.eu/climate-reanalysis). This hourly data from 1950 to now has a 9 km spatial resolution and is produced by combining data collected from weather stations, satellites, ground-based radar-gauge composite, and interpolations incorporating topographic features. This is a promising climate dataset at a fine spatial scale for a data-poor country like Nepal. We will analyze trends of extreme climate indices and changes in average annual and seasonal temperature and precipitation at the level of municipalities.
For future climate change, we will use the bias-corrected General Circulation Models (GCMs) for South Asia developed by Mishra et al. (2020) from Coupled Model Intercomparison Project-6 (CMIP-6). This dataset provides daily bias-corrected data of precipitation and, maximum and minimum temperatures at 0.25° spatial resolution for South Asia including Nepal. We will use an ensemble of 13 GCMs for two different future scenarios (SSP2-4.5, SPP5-8.5). Although the RFP document used the terms RCP 4.5 and RCP 8.5, SSPs are the most recent scenarios used by the IPCC hence will be followed here. We have codes for R, Phyton, and Google Earth Engine that were used in our previous VRA to analyze the climate data.  

