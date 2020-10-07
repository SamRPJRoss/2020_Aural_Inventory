# 2020_Aural_Inventory
R Code and Data from Ross et al. Ecological Indicators

Ross et al. Aural Inventory code.Rmd = R markdown file with all code (requires data from Ross et al. Aural Inventory data.Rda)
Ross et al. Aural Inventory code.nb.html = HTML R markdown file with all code and figures pre-run
Ross et al. Aural Inventory data.Rda = data from Ross _et al._ (Submitted) _Ecological Indicators_, with data structure as below: 

Standard = dataframe R object with 1386 obs. of 28 variables:
> *Standard$Filename* = name of Wildlife acoustics SM4 audio file used in analysis.
> *Standard$Site* = code of fieldsite (23 sites).
> *Standard$Biotic_Soundtype_Richness* = Number of unique biological sounds per 10-min sound file (_i.e._ 'sensed richness').
> *Standard$Wind_rain* = Presence (1) or absence (0) of audible geophony in each sound file.
> *Standard$Anthrophony* = Presence (1) or absence (0) of audible anthropophony in each sound file.
> *Standard$Cicadas.Stridulations* = Presence (1) or absence (0) of audible insect noise (_e.g._ broadband cicadas or orthoperan stridulations) in each sound file.
> *Standard$ACI* = Standardised (0-1) Acoustic Complexity Index value per sound file.
> *Standard$ADI* = Standardised (0-1) Acoustic Diversity Index value per sound file.
> *Standard$AEve* = Standardised (0-1) Acoustic Evenness Index value per sound file.
> *Standard$BioA* = Standardised (0-1) Bioacoustic Index value per sound file.
> *Standard$H* = Standardised (0-1) Acoustic Entropy Index value per sound file.
> *Standard$M* = Standardised (0-1) Median Amplitude Envelope value per sound file.
> *Standard$NDSI* = Standardised (0-1) Normalised Difference Soundscape Index value per sound file.
> *Standard$NDSI_Bio* = Standardised (0-1) Biophony value per sound file.
> *Standard$NDSI_Anth* = Standardised (0-1) Anthropophony value per sound file.
> *Standard$ARic* = Standardised (0-1) Acoustic Richness value per sound file.
> *Standard$Ht* = Standardised (0-1) Temporal Entropy Index value per sound file.
> *Standard$year* = Datetime information: year.
> *Standard$Season* = Datetime information: season (Spring, Summer, Autumn, Winter).
> *Standard$day* = Datetime information: day (number date per month).
> *Standard$hour* = Datetime information: hour (24 hour clock).
> *Standard$min* = Datetime information: minute.
> *Standard$sec* = Datetime information: second.
> *Standard$time* = Full Datetime information (in JST).
> *Standard$TOD* = Datetime information: time of day (Dawn, Day, Dusk, Night).
> *Standard$TOD_by_Season* = Datetime information: broken down by season and time of day.
> *Standard$mean.rich* = Mean Biotic_Soundtype_Richness value per site.
> *Standard$mean.rich_Szn* = Mean Biotic_Soundtype_Richness value per site x season combination.

See Ross _et al._ (Submitted) _Ecological Indicators_ for details on the standardisation, calculation of acoustic indices _etc._
NB: all times are in JST (Okinawa time).

