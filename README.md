# Immo_MachineLearning

Collected data from Immoweb website was analyzed to determine which variables influence the price of a property in the Belgian market.

I graded features that were in string such as kitchen type, PEB, and renovation status as they may influence the final price of a property.
Also, I collected the price per square meter from each district, because location is reported to be an important factor (probably a main one) modifying the price of a property.

I deleted all features that had minor impact in the price (showing weak correlation value).

I calculated the linear regression for all properties, but the MAE value was high. Then, I calculated the GXBoost regression and I obtained better results.

Finally, I splited the dataframe in houses and apartments as the price of the houses has been reported to be related to the number of free-facades (detached houses have higher prices than semidetached house, according to official information).

I calculated linear regression, XGBoost, and KNeighbors regression. I obtained the best values with KNeighbors.
