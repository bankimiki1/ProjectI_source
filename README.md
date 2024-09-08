// ENG 
The goal of my analysis was to examine long-term temperature trends in Budapest to determine whether the city is experiencing warming. I conducted the analysis in several steps, using different statistical models and visualization techniques.

**1. Data Cleaning and Preparation**
First, I calculated a moving average for the temperature data to smooth out short-term fluctuations and better identify long-term trends. I created pivot tables to analyze the yearly average temperatures, allowing for a clearer view of the annual data.

**2. Visualizations**
I plotted the average temperatures and moving averages on graphs to visually demonstrate how the temperatures have changed over time. Additionally, I broke the data down by season, analyzing the average temperatures for spring, summer, autumn, and winter separately. I also visualized the monthly temperature data using a heatmap, which effectively highlighted the differences between individual months.

**3. Linear Regression Analysis**
I applied a simple linear regression model to predict future temperature trends. The model provided forecasts for the years 2024, 2030, and 2035. While the model suggested some warming, I recognized that it wasn’t suitable for dealing with the temporal dependencies and seasonal patterns in the data, limiting its predictive accuracy.

**4. Using the SARIMA Model**
To better capture the temporal patterns and seasonal effects, I employed a SARIMA model. This model provided more accurate forecasts as it accounted for seasonal fluctuations. The predictions indicated that Budapest will continue to warm, which aligns with global warming trends.

**5. Conclusions**
From the analysis, I concluded that the linear regression model is inadequate for analyzing temperature data because it doesn’t account for the time-related and seasonal factors. The SARIMA model, on the other hand, offered more reliable results and indicated that Budapest’s temperatures are likely to keep rising in the future.

Overall, the analysis confirmed that Budapest is warming.


// HUN 

Az elemzésem célja Budapest hosszú távú hőmérsékleti trendjeinek vizsgálata volt, hogy megállapítsam, vajon tapasztalható-e felmelegedés a városban. Az elemzést több lépésben végeztem, különböző statisztikai modellek és vizualizációs technikák segítségével.

**1. Adattisztítás és előkészítés**
Először mozgóátlagot számoltam az átlaghőmérsékletekre, hogy kisimítsam a rövid távú ingadozásokat, és jobban lássam a hosszú távú trendeket. Pivot táblákat készítettem az éves átlaghőmérsékletek alakulásáról, így az éves adatok jól átláthatóvá váltak.

**2. Vizualizációk**
Grafikonokon ábrázoltam az átlagos hőmérsékleteket és a mozgóátlagot, hogy szemléltessem, hogyan változtak az idők során. Emellett szezonális bontásban is megvizsgáltam a hőmérsékleteket, külön elemeztem a tavasz, nyár, ősz és tél átlaghőmérsékleteit. A hónapokra bontott hőmérsékleti adatokat egy hőtérképen is megjelenítettem, amely jól bemutatja az egyes hónapok közötti hőmérséklet-különbségeket.

**3. Lineáris regresszió elemzés**
Egy egyszerű lineáris regresszió modellt használtam, hogy előrejelzést készítsek a hőmérsékleti trendekről. A modell előrejelzést adott a 2024-es, 2030-as és 2035-ös évekre. Bár a modell némi felmelegedést prognosztizált, rájöttem, hogy ez az egyszerű megközelítés nem alkalmas az időbeli függőségek és a szezonális mintázatok kezelésére, ezért az előrejelzések pontossága korlátozott.

**4. SARIMA modell használata**
Annak érdekében, hogy jobban figyelembe vegyem az időbeli mintázatokat és a szezonális hatásokat, SARIMA modellt alkalmaztam. Ez a modell sokkal pontosabb előrejelzést adott, mivel figyelembe vette a szezonális ingadozásokat is. Az előrejelzések szerint Budapest tovább fog melegedni, ami összhangban van a globális felmelegedés tendenciáival.

**5. Következtetések**
Az elemzésből kiderült, hogy a lineáris regresszió nem megfelelő a hőmérsékleti adatok elemzésére, mivel nem veszi figyelembe az időbeli és szezonális hatásokat. A SARIMA modell viszont pontosabb eredményeket adott, és arra utalt, hogy Budapest hőmérséklete a jövőben tovább emelkedhet.

Összességében az elemzés megerősítette, hogy Budapest hőmérséklete emelkedik.
