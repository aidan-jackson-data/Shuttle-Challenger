# Space Shuttle Safety and the *Challenger*

Authors: [Aidan Jackson](https://github.com/aidan-jackson-data) | [Sandip Panesar](https://github.com/spanesarmids) | [Devesh Khandelwal](https://github.com/devesh-k)

This notebook investigates the safety record of the Space Shuttle program in the lead up to the *Challenger* disaster of 1986. With data analyzed before launch, the probability of a catastrophic failure is found to be three times higher than when replicating original methodology due to mistakes in choice of statistical modeling.

This was originally part of the W271 Statistical Methods for Discrete Response, Time Series, and Panel Data course in the Master of Information and Data Science program at University of California, Berkeley. The exercise in turn was based on a previous 1989 paper on the same topic, published in the Journal of the American Statistical Association.<sup>[1]</sup>

| File      | Description |
| :----------- | :----------- |
| Report.pdf      | Report and statistical analysis       |
| Report.Rmd   | R Markdown file generating the PDF        |
| challenger.csv | Data on Space Shuttle flights prior to *Challenger*'s final mission* |

\*The primary dataset contains observations on O-Ring condition, the determined cause of the Challenger disaster, for [23/24](https://en.wikipedia.org/wiki/List_of_Space_Shuttle_missions#Launches_and_orbital_flights) orbital flights of the Space Shuttle program prior to launch. [STS-4](https://en.wikipedia.org/wiki/STS-4) resulted in loss at sea of the solid rocket boosters where the O-rings are located, and was omitted from the dataset.

Citation:

[1] Dalal, Siddhartha R., et al. “Risk Analysis of the Space Shuttle: Pre-Challenger Prediction of Failure.” Journal of the American Statistical Association, vol. 84, no. 408, [American Statistical Association, Taylor & Francis, Ltd.], 1989, pp. 945–57, https://doi.org/10.2307/2290069.
