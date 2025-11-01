# Experimental Results - Data Tables

## Impedance Performance Summary

### Individual Channel Impedance Performance (First Hour)

| Channel | Electrode Type | Mean Impedance (kΩ) | Std. Dev (kΩ) |
|---------|----------------|---------------------|---------------|
| 1       | Wet            | 23.77               | 0.59          |
| 2       | Dry            | 193.48              | 13.16         |
| 3       | RPH-Trode      | 89.75               | 1.76          |
| 4       | Dry            | 183.30              | 14.52         |
| 5       | Wet            | 28.14               | 0.64          |
| 6       | RPH-Trode      | 57.56               | 2.33          |
| 7       | RPH-Trode      | 103.69              | 3.34          |
| 8       | RPH-Trode      | 92.50               | 1.79          |

### Average Impedance by Electrode Type (First Hour)

| Electrode Type | Mean Impedance (kΩ) | Std. Dev (kΩ) |
|----------------|---------------------|---------------|
| Wet            | 25.96               | 2.27          |
| Dry            | 188.39              | 14.76         |
| RPH-Trode      | 85.88               | 17.33         |

## Alpha Band Signal Quality

### SNR for Oz Channel (Eyes Closed vs Eyes Open)

| Electrode Type  | SNR (Alpha EC / Alpha EO) | SNR (Alpha EC / Non-Alpha EC) |
|-----------------|---------------------------|-------------------------------|
| RPH-Trode       | 5.68 dB                   | -2.58 dB                      |
| Adhesive        | 4.80 dB                   | -2.51 dB                      |
| Enobio Geltrode | 3.88 dB                   | -2.85 dB                      |
| Enobio Drytrode | 1.98 dB                   | -2.24 dB                      |

### Average SNR Across All Channels

| Electrode Type  | SNR (Alpha EC / Alpha EO) | SNR (Alpha EC / Non-Alpha EC) |
|-----------------|---------------------------|-------------------------------|
| RPH-Trode       | 6.07 dB                   | -2.49 dB                      |
| Adhesive        | 5.25 dB                   | -2.24 dB                      |
| Enobio Geltrode | 3.99 dB                   | -2.77 dB                      |
| Enobio Drytrode | 3.18 dB                   | -2.20 dB                      |

## SSVEP CCA Performance

### Overall CCA Performance Summary

| Electrode Type | Signal (Avg Stim CCA) | Baseline (Avg Break CCA) | CCA Ratio |
|----------------|-----------------------|--------------------------|-----------|
| RPH-Trode      | 0.45                  | 0.27                     | 1.67      |
| Adhesive       | 0.57                  | 0.29                     | 2.01      |
| Wet            | 0.41                  | 0.27                     | 1.51      |
| Dry            | 0.26                  | 0.19                     | 1.34      |

### Detailed CCA Averages per Stimulation Period

| Electrode Type | Baseline 1 | Stim 1 | Break 1 | Stim 2 | Break 2 | Stim 3 | Break 3 | Stim 4 | Break 4 | Stim 5 |
|----------------|-----------|--------|---------|--------|---------|--------|---------|--------|---------|--------|
| RPH-Trode      | 0.24      | 0.47   | 0.24    | 0.42   | 0.26    | 0.47   | 0.29    | 0.46   | 0.32    | 0.43   |
| Adhesive       | 0.25      | 0.61   | 0.32    | 0.62   | 0.31    | 0.53   | 0.27    | 0.54   | 0.28    | 0.57   |
| Wet            | 0.30      | 0.39   | 0.25    | 0.40   | 0.26    | 0.41   | 0.29    | 0.43   | 0.27    | 0.44   |
| Dry            | 0.19      | 0.26   | 0.21    | 0.24   | 0.22    | 0.24   | 0.17    | 0.22   | 0.18    | 0.33   |

## Motion Performance Analysis

### CCA Ratio: 7.5Hz Stimulation vs. Breaks (Mean ± Std Dev)

| Electrode | Standing    | Walking (2 mph) | Walking (4 mph) |
|-----------|-------------|-----------------|-----------------|
| Dry       | 1.53 ± 0.45 | 1.14 ± 0.21     | 0.99 ± 0.14     |
| Hybrid    | 1.93 ± 0.53 | 1.24 ± 0.31     | 1.21 ± 0.25     |

### CCA Ratio: 7.5Hz Stimulation vs. 10Hz Stimulation (Mean ± Std Dev)

| Electrode | Standing    | Walking (2 mph) | Walking (4 mph) |
|-----------|-------------|-----------------|-----------------|
| Dry       | 1.60 ± 0.41 | 1.14 ± 0.05     | 1.05 ± 0.16     |
| Hybrid    | 2.23 ± 0.53 | 1.44 ± 0.49     | 1.27 ± 0.28     |


## Notes

- All values are reported as mean ± standard deviation where applicable
- **CCA** = Canonical Correlation Analysis
- **RPH-Trode** = Rapid Prototyped Hybrid electrode
- **Hybrid** = RPH-Trode in motion experiments
- **EC** = Eyes Closed
- **EO** = Eyes Open
- **SNR** = Signal-to-Noise Ratio (in dB)
