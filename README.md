# Time Series Forecasting Fish Sale Forecasting


## SARIMA Project Summary

This project investigates how statistical modeling can be applied to real-world time series data to better understand patterns and improve forecasting. Using the Catfish Sales dataset, it explores the potential of the SARIMA model, which is widely used in both academia and industry for handling seasonal data.

The study begins with exploratory data analysis to identify trends, seasonality, and stationarity in the dataset. It then introduces and applies the autocorrelation (ACF) and partial autocorrelation (PACF) functions, which are critical tools for understanding lag relationships and guiding the selection of SARIMA parameters.

Building on this foundation, the notebook fits a SARIMA model with manually tuned parameters and evaluates its performance using MSE, AIC, and BIC. The results highlight how careful tuning can improve model fit while balancing complexity.

Finally, the project extends the analysis by implementing a retraining approach in which the model is updated as new observations arrive. This demonstrates how structural changes in the data can challenge static forecasting models and underscores the importance of adaptive strategies in time series analysis.

In summary, the notebook shows both the promise and limitations of SARIMA for forecasting seasonal data while emphasizing the challenges posed by real-world datasets that evolve over time.

## Why the Fishing Industry Matters

The fishing industry and the way supply and demand move within it are central to both environmental well being and economic stability, which makes it important to pay close attention to how this sector is shaped. From an environmental standpoint, fishing practices influence the delicate balance of marine ecosystems in ways that can either sustain or destroy them. When demand pushes fisheries to take more than ecosystems can replenish, species decline, food webs collapse, and habitats such as coral reefs are left damaged. The Food and Agriculture Organization reports that over **35 percent of global fish stocks are already overexploited**, a figure that has been rising for decades. In contrast, when supply is managed responsibly, fish populations remain healthy and ecosystems continue to thrive.  

Demand matters because when consumers pursue certain species with intensity, the pressure on those fish stocks multiplies. But shifts in demand toward sustainable seafood options and aquaculture innovations can generate new opportunities for more responsible practices, which in turn create positive outcomes for the environment.  

The fishing industry is also a cornerstone of the global economy and provides livelihoods for millions of people. Nearly **60 million people** are directly employed in fisheries and aquaculture worldwide, and over **3 billion people** rely on fish as their primary source of protein. Stable supply ensures not only employment but also food security, fairer pricing, and resilience against shocks caused by scarcity. When fish stocks collapse, the damage ripples outward through communities that depend on them, threatening both cultural traditions and economic survival.  

To care about the fishing industry and its supply and demand dynamics is to recognize that choices at every level, from consumer behavior to government policy, determine whether oceans remain abundant and economies remain strong. Sustainable fishing is about much more than protecting fish. It is about protecting the intertwined future of the environment and human society.
