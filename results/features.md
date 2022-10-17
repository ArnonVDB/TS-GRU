# Demographic and temporal features

Overview of the demographic and temporal features. The demographic-type marked in italic was originally a temporal feature, but is moved to the demographic data because of its low variance over time.

| **feature**                       | **type**             | **feature**                             | **type**             |
|-----------------------------------|----------------------|-----------------------------------------|----------------------|
| activity / mobility   (jh-hlm)    | time-series          | minute volume alarm - high              | *demographic*        |
| admission\_location               | demographic          | minute volume alarm - low               | time-series          |
| age                               | demographic          | non invasive blood pressure diastolic   | time-series          |
| anion gap                         | time-series          | non invasive blood pressure mean        | time-series          |
| apnea interval                    | *demographic*        | non invasive blood pressure systolic    | time-series          |
| arterial blood pressure diastolic | time-series          | null\_height                            | demographic          |
| arterial blood pressure mean      | time-series          | o2 flow                                 | time-series          |
| arterial blood pressure systolic  | time-series          | o2 saturation pulseoxymetry             | time-series          |
| base excess                       | time-series          | o2 saturation pulseoxymetry alarm - low | time-series          |
| bicarbonate                       | time-series          | oxygen saturation                       | *demographic*        |
| braden score                      | time-series          | pain level                              | time-series          |
| calcium, total                    | *demographic*        | pain level response                     | *demographic*        |
| calculated total co2              | time-series          | paw high                                | *demographic*        |
| chloride                          | time-series          | pco2                                    | time-series          |
| chloride, whole blood             | *demographic*        | peak insp. pressure                     | time-series          |
| creatinine                        | time-series          | ph                                      | time-series          |
| dialyzed                          | demographic          | phosphate                               | *demographic*        |
| ethnicity                         | demographic          | plateau pressure                        | *demographic*        |
| expiratory ratio                  | *demographic*        | platelet count                          | time-series          |
| first\_careunit                   | demographic          | po2                                     | time-series          |
| free calcium                      | *demographic*        | potassium                               | time-series          |
| gcs - eye opening                 | time-series          | potassium, whole blood                  | *demographic*        |
| gcs - motor response              | time-series          | pt                                      | *demographic*        |
| gcs - verbal response             | time-series          | ptt                                     | *demographic*        |
| gender                            | demographic          | rdw                                     | time-series          |
| glucose                           | time-series          | rdw-sd                                  | *demographic*        |
| h                                 | *demographic*        | red blood cells                         | time-series          |
| heart rate                        | time-series          | resp alarm - high                       | time-series          |
| heart rate alarm - high           | time-series          | resp alarm - low                        | *demographic*        |
| heart rate alarm - low            | time-series          | respiratory rate                        | time-series          |
| height                            | demographic          | respiratory rate (set)                  | *demographic*        |
| hematocrit                        | time-series          | respiratory rate (spontaneous)          | *demographic*        |
| hematocrit, calculated            | *demographic*        | respiratory rate (total)                | *demographic*        |
| hemoglobin                        | time-series          | sodium                                  | time-series          |
| hour                              | time-series          | sodium, whole blood                     | *demographic*        |
| hour                              | demographic          | strength l arm                          | time-series          |
| i                                 | *demographic*        | strength l leg                          | time-series          |
| inr(pt)                           | *demographic*        | strength r arm                          | time-series          |
| inspired o2 fraction              | time-series          | strength r leg                          | time-series          |
| insurance                         | demographic          | temperature fahrenheit                  | time-series          |
| intubated                         | demographic          | tidal volume (observed)                 | time-series          |
| l                                 | *demographic*        | tidal volume (set)                      | *demographic*        |
| lactate                           | *demographic*        | urea nitrogen                           | time-series          |
| magnesium                         | *demographic*        | ventilated                              | demographic          |
| mch                               | time-series          | ventilator mode                         | *demographic*        |
| mchc                              | time-series          | vti high                                | *demographic*        |
| mcv                               | time-series          | weight                                  | demographic          |
| mean airway pressure              | time-series          | white blood cells                       | time-series          |
| minute volume                     | time-series          |                                         |                      |

