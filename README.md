# What affects the Sea Surface Temperature? 

Global warming has been one of the biggest problems the world is facing today. In particular,
the increasing ocean temperature affect marine species and ecosystems. This increase can cause coral
bleaching and in turn, loss of breeding grounds for marine animals. In this exercise, we discover knowledge
using data from the Tropical Atmosphere Ocean (TAO) array which was developed by the international
Tropical Ocean Global Atmosphere (TOGA) program. In particular, we would like to know what are the
indicators of a sea surface temperature increase. Here, we found that air temperature and sea surface
temperature are highly correlated with each other and as such, we remove air temperature in our predictor
variables. The final linear model is as follows: sea_surface_temp = 5.955latitude + 0.3791 longitude +
0.3295zonal_winds -0.8165 meridional_winds -1.126*humidity, with an error of 16.86%. From here, we can
see that increasing the latitude, longitude and zonal winds also increase the sea surface temperature. On
the other hand, the lower the meridional winds and the humidity, the higher the sea surface temperature
will be. We can use these insights in detecting possible triggers for sea surface temperature increase.
