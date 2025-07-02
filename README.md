# smc-volatility
Several notebooks exploring sequential Monte Carlo methods,
Kalman filtering, and towards the end, we will play
with Snowflake + Azure to deploy a live model.

See also `requirements.txt`:
```
mkdir ./venv && python3 -m venv ./venv/
source ./venv/bin/activate/
pip3 install -r requirements.txt
```
on POSIX shells, and uhh something else on Windows.

- `volatility-model.ipynb` first notebook following a tutorial by Arnoud Doucette:
[https://www.stats.ox.ac.uk/~doucet/doucet_johansen_tutorialPF2011.pdf](https://www.stats.ox.ac.uk/~doucet/doucet_johansen_tutorialPF2011.pdf).
