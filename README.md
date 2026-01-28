# Car Market Analysis - Engine Performance, Pricing & Fuel Efficiency

## Introduction 

The car dataset contains detailed information on a wide range of vehicles, including technical specifications, pricing, and fuel efficiency metrics. Key attributes include manufacturer suggested retail price (MSRP), engine horsepower (HP), drivetrain configuration, transmission type, vehicle size, and city and highway fuel economy. The dataset spans multiple manufacturers and vehicle segments, offering a broad view of the automotive market.

## Dataset
...

## Objectives

The primary objective is to understand how vehicle characteristics influence manufacturer suggested retail price (MSRP) and fuel efficiency, and to identify trade-offs inherent in vehicle design and configuration. 


## Methodology

The dataset was filtered to include vehicles from model year 1995 onward, and records with missing values were removed to ensure data quality. This prepared dataset supports meaningful comparisons across vehicle categories and enables analysis of relationships between performance, pricing, and fuel economy.


## Visualizations


## Key Insights

The analysis shows clear relationships between vehicle characteristics, pricing, and efficiency. MSRP increases with both vehicle size and engine performance: large vehicles have the highest average MSRP (approximately $56,000), followed by midsize (about $41,000) and compact vehicles (about $38,000). Engine horsepower (HP) is strongly correlated with MSRP (r ≈ 0.65), with vehicles under 200 HP typically priced below $50,000, while vehicles exceeding 600 HP often surpass $300,000. Drivetrain choice further affects pricing, as rear-wheel drive and all-wheel drive vehicles have higher median MSRPs (around $44,000 and $43,000) than front-wheel drive vehicles (approximately $27,000).

Fuel efficiency trends highlight important design trade-offs. City MPG values are mostly concentrated between 15 and 25 MPG, with a right-skewed distribution driven by a small number of highly efficient vehicles. Transmission type influences efficiency, with manual transmissions averaging approximately 20 MPG city and 28 MPG highway, slightly outperforming automatic transmissions (19 MPG city, 26 MPG highway). Direct-drive transmissions exhibit exceptionally high MPG values, reflecting electric powertrains rather than conventional combustion engines.


## Recommendations

Based on the findings, consumers seeking lower purchase costs and better fuel efficiency may benefit from choosing smaller, front-wheel drive vehicles with manual or efficient automatic transmissions. Manufacturers aiming to balance performance and affordability should consider optimizing horsepower gains against fuel economy losses, particularly in midsize vehicle segments. From a policy and sustainability perspective, the strong efficiency performance of direct-drive (electric) vehicles suggests continued investment and development in electric powertrain technologies could significantly improve overall fleet fuel efficiency.




