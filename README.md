# Euvsdisinfo-dataset

EUvsDisinfo is the flagship project of the European External Action Service’s East StratCom Task Force. It was established in 2015 to better forecast, address, and respond to the Russian Federation’s ongoing disinformation campaigns affecting the European Union, its Member States, and countries in the shared neighbourhood.
Using data analysis and media monitoring services in 15 languages, EUvsDisinfo identifies, compiles, and exposes disinformation cases originating in pro-Kremlin media that are propagated across the EU and Eastern Partnership countries. 

EUvsDisinfo is the only searchable, open-source repository of its kind, and has two core objectives:

1. To increase public awareness and understanding of the Kremlin’s disinformation operations;
2. To help citizens to develop resistance to digital information and media manipulation.

As the data is not directly accessible for analysis, we scraped it using the Selenium and Beautiful soup Python’s packages. We retrieved 14 497 cases of Disinformation and their disproofs (information) from the 6th of January 2015 to the 22nd of November 2022.

Each row has seven attributes:

1. Date: Date of publication;
2. Links: Link to the article in the EUvsDisinfo database;
3. Title: Title of the disinformation article;
4. Outlets: Outlets of propagation;
5. Country: Target countries;
6. Disinformation: Text of Disinformation;
7. Information: Factual Information.
