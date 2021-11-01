#  Blockchain-based ledger system & user-friendly web interfac


## Installation

Please preform the pip instalation below in order to run the python file propertly. 

```bash

conda activate dev

pip install streamlit==0.84.2
 
```

```
## Usage Examples 

Using the .plot and .loc functionalities we can select a specific date and show a graph for the desired dates. 
```python
import 

bitstampdf['Close'].loc['2018-1-29'].plot(
    legend=True, figsize=(15, 10), title="March 2018", color="blue", label="Bitstamp")
coinbasedf['Close'].loc['2018-1-29'].plot(
    legend=True, figsize=(15, 10), color="orange", label="Coinbase")
```

![Coinbase V Bitstamp closing prices for 1/29/18](/Images/Bitstamp_v_Coinbase_early.PNG)

![Coinbase V Bitstamp closing prices for 1/29/18](/Images/Bitstamp_v_Coinbase_middle.PNG)


or you can get a dataframe for your statical analysis in order view for instance which trades would be positive 

![Coinbase V Bitstamp closing prices for 1/29/18](/Images/Statistic_over_zero_early.PNG)

![Video demo]

https://user-images.githubusercontent.com/85713622/139613459-3011bc61-fafb-4f1e-b7b2-97b168bea91e.mp4


https://user-images.githubusercontent.com/85713622/139613089-5775a1f8-d007-47e3-b1a1-42e95db127e6.mp4

 ![Link to interface] (http://localhost:8501/)

## Contributors(ing)
This a project designed by:

Jose Sampedro
sampedro.jose.a@gmail.com

With the contributions and assistance of:

The Columbia Fintech Bootcamp TAs and Tutors.

## License

[See GNU v3.0](https://github.com/IJASI/Challenge-3/blob/491335d4123fae396530363cb79be7070e049796/LICENSE)





