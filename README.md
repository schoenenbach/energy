# Can We Produce Enough Electricity for an All-Electric Car Fleet?

Abandoning our current fossil fuel-based car fleet seems to be one major step toward a sustainable society. However, one can raise the question if we are able to substitute the current car fleet with an all-electric one. Especially, if we can produce enough electricity to power it.

To answer this question we need to know how much energy actually is consumed by our car fleet and how much energy we can produce currently - and potentially in the future.

There is a [recent contribution by German physicist Harald Lesch on this topic][1]. He investigated scenarios of switching the power supply for cars from mainly fuel today to either Li-Ion or hydrogen technologies. He focussed mainly on the peak power consumption of an all-electric car fleet and the implications on the power infrastructure from Germany. His argument goes like this: Assume that we replace all currently existing cars (54 million in Germany) with battery-powered vehicles. Then assume that 2 \% of these cars need to be charged in parallel, namely 1 million. This could happen e.g. around rush hour times when people need to make sure their cars will carry them to their destination. And then assume that all cars will be charged using a fast charger with a power of 350 kW (current state of the art but as humans tend to be striving for convenience wherever possible this can be expected to be the standard in future.) This results in a demand of 350 GW electrical power from the grid. This compares to a current [power production between 40 and 80 GW in Germany][2]. In addition, Lesch mentions the complications that we are already facing in providing a stable power grid. So this seems to be a major challenge when we think about an all-electric car fleet.

Besides the peak *power* need illustrated in the example by Lesch, I wondered if we are capable of producing enough *energy* to support the car fleet. [According to the Umweltbundesamt (German Federal Environment Agency)][3] the overall consumption of fuel, diesel and petrol in  millions of liters per year, is depicted here

![Fuel consumption of traffic in Germany][fuel_usage]

The [fuel values of diesel and petrol (see the table under "Flüssige Brennstoffe")][6] are:

1. Diesel: 9,7 kWh/L
2. Petrol: 8,8 kWh/L

For simplicity, we can assume them to be roughly 10 kWh/L. This allows us now to use the numbers above to estimate the total *energy* needed to run our current car fleet
![Energy consumption of traffic in Germany][total_traffic]

Interestingly this seems to stay more or less constant over the past 20 years.

Last we can have a look at the overall energy consumption and the potential production of renewable energy in Germany.  
The BMWI (German Federal Ministry for Economic Affairs and Energy) states the [primary energy usage of Germany][4] to roughly 13,000 PJ - or 3,600 TWh - per year in 2018.
[Friedrich Wagner states the overall potential for power generation based on photovoltaic and wind energy to 900 TWh per year][5] with the climate conditions from 2018.

![Energy consumption and production capabilities in Germany][consumption_production]

Obviously, we could cover the amount of energy needed for an all-electric car fleet by relying on renewable energy sources. However, for the overall energy need we would require different solutions as well.

Sources (in German):

- [Video by Harald Lesch][1]
- [Power production capabilities in Germany][2]
- [Fuel consumption according to the Umweltbundesamt][3]
- [Primary energy usage of Germany according to the BMWI (German Federal Ministry for Economic Affairs and Energy)][4]
- [Potential for power generation based on photovoltaic and wind energy in Germany][5]
- [Fuel values of different fuels (in German)][6]

[1]: https://www.youtube.com/watch?v=TswNLBnAPjU
[2]: https://www.energy-charts.de/power_de.htm
[3]: https://www.umweltbundesamt.de/daten/verkehr/kraftstoffe
[4]: https://www.bmwi.de/Redaktion/DE/Downloads/Energiedaten/energiedaten-gesamt-pdf-grafiken.pdf?__blob=publicationFile&v=38
[5]: https://www.pro-physik.de/physik-journal/oktober-2019
[6]: https://de.wikipedia.org/wiki/Heizwert

[total_traffic]: ./Energy_consumption_traffic_lines.png
[fuel_usage]: ./3_tab_kraftstoffverbrauch-strv-sektor_2019-05-31.png
[consumption_production]: ./consumption_production_capability.png
