
# Type: TSW_5min




URI: [neon:TSW5min](https://data.neonscience.org/TSW5min)


![img](http://yuml.me/diagram/nofunky;dir:TB/class/[TSW5min&#124;rangeQAQCRpt:string%20%3F;persistenceQAQCRpt:string%20%3F;stepQAQCRpt:string%20%3F;nullQAQCRpt:string%20%3F;gapQAQCRpt:string%20%3F;consistencyQAQCRpt:string%20%3F;spikeQAQCRpt:string%20%3F;alphaQAQCRpt:string%20%3F;betaQAQCRpt:string%20%3F;rangeFailQM:double%20%3F;rangePassQM:double%20%3F;rangeNAQM:double%20%3F;persistenceFailQM:double%20%3F;persistencePassQM:double%20%3F;persistenceNAQM:double%20%3F;stepFailQM:double%20%3F;stepPassQM:double%20%3F;stepNAQM:double%20%3F;nullFailQM:double%20%3F;nullPassQM:double%20%3F;nullNAQM:double%20%3F;gapFailQM:double%20%3F;gapPassQM:double%20%3F;gapNAQM:double%20%3F;spikeFailQM:double%20%3F;spikePassQM:double%20%3F;spikeNAQM:double%20%3F;consistencyFailQM:double%20%3F;consistencyPassQM:double%20%3F;consistencyNAQM:double%20%3F;alphaQM:double%20%3F;betaQM:double%20%3F;finalQF:string%20%3F;startDateTime:time%20%3F;endDateTime:time%20%3F;surfWaterTempExpUncert:double%20%3F;surfWaterTempMean:double%20%3F;surfWaterTempMinimum:double%20%3F;surfWaterTempMaximum:double%20%3F;surfWaterTempVariance:double%20%3F;surfWaterTempNumPts:double%20%3F;surfWaterTempStdErMean:double%20%3F;validCalFailQM:double%20%3F;validCalNAQM:double%20%3F;validCalPassQM:double%20%3F;validCalQAQCRpt:string%20%3F;finalQFSciRvw:string%20%3F])

## Attributes


### Own

 * [alphaQAQCRpt](alphaQAQCRpt.md)  <sub>OPT</sub>
    * Description: Quality assurance and quality control report for the alpha quality flag, which indicates if one or more quality analysis failed for a datum, detailed in NEON.DOC.001113 (1=fail, 0=pass, -1=NA (i.e., could not be run))
    * range: [String](types/String.md)
 * [alphaQM](alphaQM.md)  <sub>OPT</sub>
    * Description: Quality metric detailing the outcomes of the alpha quality flag over the averaging period, as a percent and detailed in NEON.DOC.001113
    * range: [Double](types/Double.md)
 * [betaQAQCRpt](betaQAQCRpt.md)  <sub>OPT</sub>
    * Description: Quality assurance and quality control report for the beta quality flag, which indicates if one or more quality analysis could not be run for a datum, detailed in NEON.DOC.001113 (1=fail, 0=pass, -1=NA (i.e., could not be run))
    * range: [String](types/String.md)
 * [betaQM](betaQM.md)  <sub>OPT</sub>
    * Description: Quality metric detailing the outcomes of the beta quality flag over the averaging period, as a percent and detailed in NEON.DOC.001113
    * range: [Double](types/Double.md)
 * [consistencyFailQM](consistencyFailQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes the failed outcomes of the consistency test over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [consistencyNAQM](consistencyNAQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes when the consistency test could not be run over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [consistencyPassQM](consistencyPassQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes the passed outcomes of the consistency test over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [consistencyQAQCRpt](consistencyQAQCRpt.md)  <sub>OPT</sub>
    * Description: Quality assurance and quality control report for the consistency test, which indicates whether or not measurements are consistent with co-located measurements, (1=fail, 0=pass, -1=NA (i.e., could not be run))
    * range: [String](types/String.md)
 * [endDateTime](endDateTime.md)  <sub>OPT</sub>
    * Description: Date and time at which a sampling is completed
    * range: [Time](types/Time.md)
 * [finalQF](finalQF.md)  <sub>OPT</sub>
    * Description: Quality flag indicating whether a data product has passed or failed an overall assessment of its quality, detailed in NEON.DOC.001113 (1=fail, 0=pass)
    * range: [String](types/String.md)
 * [finalQFSciRvw](finalQFSciRvw.md)  <sub>OPT</sub>
    * Description: Quality flag indicating whether a data product has failed a science review of its quality, detailed in NEON.DOC.001113 (1=fail, 0=pass/not-reviewed)
    * range: [String](types/String.md)
 * [gapFailQM](gapFailQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes the failed outcomes of the gap test over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [gapNAQM](gapNAQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes when the gap test could not be run over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [gapPassQM](gapPassQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes the passed outcomes of the gap test over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [gapQAQCRpt](gapQAQCRpt.md)  <sub>OPT</sub>
    * Description: Quality assurance and quality control report for the gap test, which indicates that the datum is missing and is apart of a prolonged period of missing data, detailed in NEON.DOC.011081 (1=fail, 0=pass)
    * range: [String](types/String.md)
 * [nullFailQM](nullFailQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes the failed outcomes of the null test over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [nullNAQM](nullNAQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes when the null test could not be run over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [nullPassQM](nullPassQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes the passed outcomes of the null test over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [nullQAQCRpt](nullQAQCRpt.md)  <sub>OPT</sub>
    * Description: Quality assurance and quality control report for the null test, which indicates a missing datum, detailed in NEON.DOC.011081 (1=fail, 0=pass, -1=NA (i.e., could not be run))
    * range: [String](types/String.md)
 * [persistenceFailQM](persistenceFailQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes  the failed outcomes of the persistence test over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [persistenceNAQM](persistenceNAQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes when the persistence test could not be run over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [persistencePassQM](persistencePassQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes the passed outcomes of the persistence test over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [persistenceQAQCRpt](persistenceQAQCRpt.md)  <sub>OPT</sub>
    * Description: Quality assurance and quality control report for the persistence test, which indicates  whether there is a realistic fluctuation of values over a designated period of time, detailed in NEON.DOC.011081 (1=fail, 0=pass, -1=NA (i.e., could not be run))
    * range: [String](types/String.md)
 * [rangeFailQM](rangeFailQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes the failed outcomes of the range test over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [rangeNAQM](rangeNAQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes when the range test could not be run over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [rangePassQM](rangePassQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes the passed outcomes of the range test over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [rangeQAQCRpt](rangeQAQCRpt.md)  <sub>OPT</sub>
    * Description: Quality assurance and quality control report for the range test, which indicates whether a datum exceeds a realisitc value, detailed in NEON.DOC.011081 (1=fail, 0=pass, -1=NA (i.e., could not be run))
    * range: [String](types/String.md)
 * [spikeFailQM](spikeFailQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes the failed outcomes of the spike test over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [spikeNAQM](spikeNAQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes when the spike test could not be run over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [spikePassQM](spikePassQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes the passed outcomes of the spike test over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [spikeQAQCRpt](spikeQAQCRpt.md)  <sub>OPT</sub>
    * Description: Quality assurance and quality control report for the spike test, which indicates whether or not a datum has been identified as a spike, detailed in NEON.DOC.000783 (1=fail, 0=pass, -1=NA (i.e., could not be run))
    * range: [String](types/String.md)
 * [startDateTime](startDateTime.md)  <sub>OPT</sub>
    * Description: Date and time at which a sampling is initiated
    * range: [Time](types/Time.md)
 * [stepFailQM](stepFailQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes the failed outcomes of the step test over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [stepNAQM](stepNAQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes when the step test could not be run over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [stepPassQM](stepPassQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes the passed outcomes of the step test over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [stepQAQCRpt](stepQAQCRpt.md)  <sub>OPT</sub>
    * Description: Quality assurance and quality control report for the step test, which indicates whether unusual jumps in the data exist, detailed in NEON.DOC.011081 (1=fail, 0=pass, -1=NA (i.e., could not be run))
    * range: [String](types/String.md)
 * [surfWaterTempExpUncert](surfWaterTempExpUncert.md)  <sub>OPT</sub>
    * Description: Expanded uncertainty for temperature of surface water in degrees celsius
    * range: [Double](types/Double.md)
 * [surfWaterTempMaximum](surfWaterTempMaximum.md)  <sub>OPT</sub>
    * Description: Maximum temperature of surface water in degrees celsius
    * range: [Double](types/Double.md)
 * [surfWaterTempMean](surfWaterTempMean.md)  <sub>OPT</sub>
    * Description: Arithmetic mean of temperature of surface water in degrees celsius
    * range: [Double](types/Double.md)
 * [surfWaterTempMinimum](surfWaterTempMinimum.md)  <sub>OPT</sub>
    * Description: Minimum temperature of surface water in degrees celsius
    * range: [Double](types/Double.md)
 * [surfWaterTempNumPts](surfWaterTempNumPts.md)  <sub>OPT</sub>
    * Description: Number of points used to calculate the arithmetic mean of temperature of surface water in degrees celsius
    * range: [Double](types/Double.md)
 * [surfWaterTempStdErMean](surfWaterTempStdErMean.md)  <sub>OPT</sub>
    * Description: Standard error of the mean for temperature of surface water in degrees celsius
    * range: [Double](types/Double.md)
 * [surfWaterTempVariance](surfWaterTempVariance.md)  <sub>OPT</sub>
    * Description: Variance in temperature of surface water in degrees celsius
    * range: [Double](types/Double.md)
 * [validCalFailQM](validCalFailQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes the failed outcomes of the valid calibration check over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [validCalNAQM](validCalNAQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes when the valid calibration check could not be run over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [validCalPassQM](validCalPassQM.md)  <sub>OPT</sub>
    * Description: Quality metric that summarizes the passed outcomes of the valid calibration check over the averaging period, as a percent
    * range: [Double](types/Double.md)
 * [validCalQAQCRpt](validCalQAQCRpt.md)  <sub>OPT</sub>
    * Description: QAQC report for the valid calibration check, which indicates whether the measurements are within the valid calibration date range, detailed in NEON.DOC.011081 (1=fail, 0=pass, -1=NA (i.e., could not be run))
    * range: [String](types/String.md)

## Other properties

|  |  |  |
| --- | --- | --- |
| **Mappings:** | | neon:TSW_5min |
| **In Subsets:** | | DP1.20053.001 |

