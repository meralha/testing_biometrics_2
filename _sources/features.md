# Organizing Audio Data: A BIDS-Inspired Approach

Organizing audio data effectively is crucial for efficient data retrieval, analysis, and sharing. Inspired by the Brain Imaging Data Structure (BIDS), a standardized format for organizing and describing neuroimaging data, we propose a similar methodology for audio data.

## BIDS for Audio Data

| Acoustic feature | Description |
| --- | --- |

<div style="background-color:lightpink">

| Source features | Features reflecting airflow from the lungs through the glottis (i.e. glottal features) or vocal fold vibrations (i.e., voice quality features), which is the sound source later filtered by the vocal tract following the source-filter theory of speech production. 29 |
| Jitter [%] | Deviations in individual consecutive f0 period lengths, which indicates irregular closure and asymmetric vocal-fold vibrations. |
| Shimmer [%] | Difference of the peak amplitudes of consecutive f0 periods, which indicates irregularities in voice intensity. |
| Tremor [Hz] | Frequency of the most intense low-frequency fundamental frequency-modulating component in a specified analysis range. |
| Harmonics-to-noise ratio (HNR) [dB] | Ratio between f0 and noise components, which indirectly correlates with perceived aspiration. This may be due to reducing laryngeal muscle tension resulting in a more open, turbulent glottis. 56 |
| Frequency disturbance ratio (FDR) 1%] | Relative mean value of the frequency disturbance from 5 to 5 periods (five points average) 60. |
| Amplitude Disturbance ratio (ADR %) | Relative mean amplitude value over a set of windows. 108 |
| Quasi-open quotient (QOQ) | Ratio of the vocal folds' opening time. Functional dysphonias often reduce Q0Q range. Speaking loudly requires more effort with a low QOQ and sounds more stalled |
| Normalized amplitude quotient (NAQ) | Ratio between peak-to-peak pulse amplitude and the negative peak of the differentiated flow glottogram and normalized with respect to the period time. It can be an estimate of glottal adduction. |
| Peak slope | Slope of the regression line that is fit to log 10 of the maxima of each frame. 116 |

</div>
