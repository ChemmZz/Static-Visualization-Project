China's Solar Exports 

Chema Galvez

## What is your current goal? Has it changed since the proposal?
Yes, I originally tried to match China's solar exports to Europe's RD&D budget across time but there is a big outlier in Europe's data that it's most likely a data entry problem but this practically makes the dataset useless.

So I'm pivoting on tracking the (3) different exports of solar technology, where are they going. One of these technologies are solar wafer which is the raw (also we could say foundational) material for solar panels, with my visualizations I discovered that Asia is the contienent that is exporting more of these, which signals that there is another country/es manufacturing solar panels, so it would be interesting to track it down.

## Are there data challenges you are facing? Are you currently depending on mock data?
Previously I mentioned that there was not data for the US RD&D budget from 2016 onward, now that I explored the data further I also discovered that Europe's data has inconsistencies so I will ditch these dataframe completely.

## Describe each of the provided images with 2-3 sentences to give the context and how it relates to your goal.

* [RD&D Budget Europe](images_plots/rdd_bdgt_oecd.png) In this graph is where I realized my RD&D Budget data had a proble, the scale of Hungary 2021 makes no sense, it was probably a data entry error, I tried searching if there was actually an abnormal investment in Hungary during that year but found nothing.

* [China Solar Exports Over Time](images_plots/plot_world_exports_red.png) Here the idea is to track how China's exports have evolved across time. The measure is in total capacity of the products exported. We can clearly see the upward trend and a big jump in 2022.

[China Solar Exports over time](images_plots/plot_world_exports_pinkish.png) Same chart as the previous but I was trying different colors

* [Solar Exports Over Time by Technology](images_plots/monthly_exports_by_technology.png) This graph is close to the China Solar Exports Over Time but I added the the dimmension of the three type of Solar Enrgy technologies. We can observe the same as in the previous graph but it introduces the different technologies which can be useful to adress in the written part.

[Solar Exports Over Time by Technology (colorful)](images_plots/monthly_exports_by_technology_colorful.png) Here I'm just trying a different color palet for the same graph as above.

* [Solar Exports Over Time by Technology (Area)]("images_plots/exports_by_tech.png") I wanted to experiment with another type of chart to explain the same variables, instead of bars here I did it as a area graph, which I personally liked more. I'm waiting to hear feedback from my teammates

* [Exports by regions]("images_plots/exports_by_regions.png") With this graph we can see which regions (and alliances) are the ones importing more Chine's Solar technology, this was supposed to be used as a support for the RD&D data but even though I'm not going to use that one, this graph still makes for interesting points.

* [Exports by regions + World]("images_plots/exports_by_region_plus_world.png") This is a better version of the previous chart, cleaned, with better colors but also adding the World data (agregation of all regions). I really like this one but it's somewhat repetitive with the firsts charts (China Solar Exports Over Time & Solar Exports Over Time by Technology) so I'll probaly just end up doing one of these 

* [Exports by region and tech]("images_plots/exports_by_tech_region.png") This graph packs a lot of information, we can see per region how much solar tech (by capacity) they're importing while at the same time see what technology their exporting more. We can do quick comparissons and conclusions like that most countries import the finalized panels, not the raw or intermediate tech

* [Exports by region and tech (canvas)]("images_plots/monthly_exports_by_tech_region_canvas.png") Same information as above but instead of bar one bar graph per tech, here we can see them aggregated as percentage. I don't like which one I like the most, I'm waiting for the feedback. We can draw the same conclusions and comparissons

## What form do you envision your final narrative taking? (e.g. An article incorporating the images? A poster? An infographic?)
I would like to make an article, idk if it's to ambicious for the time we have but instead I can't make it then infographic