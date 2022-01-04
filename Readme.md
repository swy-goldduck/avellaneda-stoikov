# avellaneda-stoikov
This is a code replicating study Avellaneda, Marco, and Sasha Stoikov: High-frequency trading in a limit order book. Quantitative Finance 8.3 (2008): 217-224.

Our results for 1000 simulations with \gamma = 0.1 give:

| Strateg       |Profit          | Std (Profit)   | Final q       | Std (Final q)  |
| ------------- |:--------------:| :-------------:|:-------------:| --------------:| 
| Inventory     | 65.0           | 6.3            | 0.043         | 3.2            |
| Symmetric     | 69.0           | 13.7           | 0.04          | 8.4            |

The original results were:

| Strategy      |Profit          | Std (Profit)   | Final q       | Std (Final q)  |
| ------------- |:--------------:| :-------------:|:-------------:| --------------:| 
| Inventory     | 65.0           | 6.6            | 0.08          | 2.9            |
| Symmetric     | 68.4           | 12.7           | 0.26          | 8.4            |


Plots of mid-price and optimal bid and ask quotes and also of final P&L are attached, as in the original study.

### Other reference
* https://github.com/ragoragino/avellaneda-stoikov
  * 24 fork🍴, 63 star⭐️
* https://github.com/mdibo/Avellaneda-Stoikov
  * 52 fork🍴, 70 star⭐️
* https://github.com/fedecaccia/avellaneda-stoikov
  * 34 fork🍴, 56 star⭐️️
    