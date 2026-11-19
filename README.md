# Exploring a car table with pandas

The most useful cell in this 2021 exercise is the empty table. The first attempt asks for rows where the same `Origin` value equals both Asia and Europe. The next cell uses `isin(['Asia', 'Europe'])` and returns the intended records. The saved outputs show the difference. [Open the notebook](DS-2_Cars_dataset.ipynb).

Other cells count makes, fill missing cylinder counts with the column mean, filter the table on weight, and add three to the city-MPG column. That last change modifies the working data frame and has no interpretation as an observed improvement in fuel economy.

The original CSV is external to the repository. To repeat the exercise, point the first `pd.read_csv` call to a compatible file with the columns `Cylinders`, `Make`, `Origin`, `Weight` and `MPG_City`. Run once from a fresh kernel so the MPG adjustment is applied once.

