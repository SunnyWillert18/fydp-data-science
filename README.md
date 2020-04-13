# fydp-data-science
Data science repo for ONDRI neurodegenerative disease monitoring system

## Heart rate analysis
Processing ECG data and calculating BPM metrics. Uses [HeartPy](https://python-heart-rate-analysis-toolkit.readthedocs.io/en/latest/).

## Sleep Detection
Looking at sleep and wake periods based on wrist accelerometer data. Algorithm based on:

`V. van Hees, et al., “Estimating sleep parameters using an accelerometer without sleep diary,” Scientific Reports, vol. 8, 2018.`

## Physical Activity Index
Calculating the activity index on each 24hr day (noon-noon). Based on index described in: 

`J. Bai,et al., “An Activity Index for Raw Accelerometer Data and Its Comparison with Other Activity Metrics,” PLoS ONE, vol. 11, 2016.`

## Stress Detection
Detecting stress in patients using HRV features and intensity of physical activity. Algorithm is based on the following paper:

`M. Salai, I. Vassanyi, and I. Kosa, “Stress Detection Using Low Cost Heart Rate Sensors,” Journal of Healthcare Engineering,  2016.`

With incorporation of the physical activity index from: <br>
`J. Bai,et al., “An Activity Index for Raw Accelerometer Data and Its Comparison with Other Activity Metrics,” PLoS ONE, vol. 11, 2016.`
