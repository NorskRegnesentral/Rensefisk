This page contains stomach contents data from cleaner fish deployed in Norwegian salmonid farms. The description of the columns is as follows: 

id: integer variable, individual identifier. 


species: character, cleaner fish species. Takes values: Avl rognkjeks (farmed lumpfish), Berggylt (ballan wrasse), Rognkjeks (lumpfish), Bergnebb (goldsinny wrasse), Grønngylt (corkwing wrasse), Ogylt (farmed ballan wrasse)


length: float variable, cleaner fish length measured in cm. Standardised since 2020-04-01, with instructions to measure the length only to the caudal peduncle, not including the caudal fin (standard length).


weight: float variable, cleaner fish weight measured in g.


lice_quantity: number of salmon lice recovered in cleaner fish stomach. 


skottelus_quantity: number of caligus elongatus recovered in cleaner fish stomach.


datetime: date as yyyy-mm-dd, time of sampling. 


cloud_cover: character, cloud cover on sampling date. Takes values Overskyet (clouded), Delvis overskyet (partly clouded), Klarvær (Clear weather).


fish_type: character, farmed salmonid species. Takes values Laks (salmon) and Ørret (trout).


average_weight: integer, average weight of salmonid in g. 


old_average_weight: integer, average weight of salmonid in g.


population_goldsinny: float, stocking density of goldsinny wrasse.


population_corkwing: float, stocking density of corkwing wrasse.


population_ballan: float, stocking density of ballan wrasse.


population_lumpfish: float, stocking density of lumpfish.


population_ogylt: float, stocking density of farmed ballan wrasse. 


kelp_amount: integer, kelp amount in metres.


lice_moving: float, mean number of other motile lice per salmon in cage (from sample).


lice_mature: float, mean number of adult female lice per salmon in cage (from sample).


capture_method: character, capture method of cleaner fish. Takes values: Glip, hov, teine. 


capture_location: character, sample location of cleaner fish. Takes values: Annet, Dødfiskhov, Gjengfangst, Notvegg, Skjul. 


feeding_method: character. Takes values: Annet, Automat fôring pellet, Håndfôring pellet, Strømpe.


renhold_not: indicator for status of cleaning for cage, where 0 means clean, 1 less clean, and 2 least clean. 


renhold_skjul: indicator for status of cleaning for hides, where 0 means clean, 1 less clean, and 2 least clean. 


renhold_utstyr: indicator for status of cleaning for equipment, where 0 means clean, 1 less clean, and 2 least clean.


status_foring: indicator for status of feeding for cage, where 0 means good, 1 less good, and 2 bad.


kondis: float, condition factor for lumpfish calculated as in Engebretsen et. al 2024. 


PO: integer, production area. 


loc_anonymous: integer, anonymous locality indicator. 


engebretsen2023all: indicator for whether observation was used in the stomach content analysis of Engebretsen et al. 2023. 


engebretsen2023mainregression: indicator for whether observation was used in the main regression analysis of Engebretsen et al. 2023


engebretsen2023stockregression: indicator for whether observation was used in the regression analysis including lumpfish stocking density of Engebretsen et al. 2023


engebretsen2023conditionregression: indicator for whether observation was used in the regression analysis including lumpfish condition of Engebretsen et al. 2023


engebretsen2024: indicator for whether observation was used in the condition factor analysis of Engebretsen et al. 2024. 

References: 
Engebretsen, Solveig, et al. "Salmon lice (Lepeophtheirus salmonis) in the stomach contents of lumpfish (Cyclopterus lumpus) sampled from Norwegian fish farms: Relationship between lice grazing and operational conditions." Aquaculture 563 (2023): 738967.

Engebretsen, Solveig, et al. "Condition factor tailored to lumpfish (Cyclopterus lumpus) used as cleaner fish in salmonid farms." Aquaculture Reports 35 (2024): 101996.

