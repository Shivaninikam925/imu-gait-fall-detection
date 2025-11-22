# Dataset Summary – WISDM_ar_v1.1

## Dataset Path
C:\Users\Shivani\OneDrive\Documents\B.Tech\IMU-Gait-Fall-Detection\imu-gait-fall-detection\data\raw\WISDM_ar_v1.1

---

## Total ARFF Files
*200 ARFF files total*  
(from phone+watch × accel+gyro)

---

## Activity Labels (18 Classes – From activity_key.txt)

A – Walking  
B – Jogging  
C – Stairs  
D – Sitting  
E – Standing  
F – Typing  
G – Brushing Teeth  
H – Eating Soup  
I – Eating Chips  
J – Eating Pasta  
K – Drinking  
L – Eating Sandwich  
M – Kicking  
N – Not present in your ARFF files  
O – Playing Catch  
P – Dribbling  
Q – Writing  
R – Clapping  
S – Folding  

---

## Class Distribution (Computed)

| Activity        | Label | Count |
|-----------------|-------|-------|
| Walking         | A     | 4133  |
| Jogging         | B     | 4175  |
| Stairs          | C     | 3988  |
| Sitting         | D     | 4214  |
| Standing        | E     | 4232  |
| Typing          | F     | 4006  |
| Brushing Teeth  | G     | 4160  |
| Eating Soup     | H     | 4137  |
| Eating Chips    | I     | 4116  |
| Eating Pasta    | J     | 4027  |
| Drinking        | K     | 4284  |
| Eating Sandwich | L     | 4086  |
| Kicking         | M     | 4365  |
| Playing Catch   | O     | 4293  |
| Dribbling       | P     | 4351  |
| Writing         | Q     | 4175  |
| Clapping        | R     | 4174  |
| Folding         | S     | 4183  |

---

## Balanced or Not?

The dataset is *balanced*.  
All activities (except N) have *similar number of samples*, with variation <10%.  
Class *N does not appear* in ARFF files → meaning this version of the dataset *does not include activity N recordings*.

---

## Interpretation (Simple Explanation)

- Your dataset contains *200 ARFF sensor files* from phone and watch IMU.  
- It has *18 activity labels* (A–S), mapped to real-world actions.  
- All classes have roughly equal number of samples → *no class dominates*.  
- This makes the dataset *easy to train, with **no rebalancing needed*.

---

## Notes

- Activity *N* is listed in activity_key.txt but *absent* in ARFF data → so you won't use it during training.  
- WISDM ARFF files contain pre-extracted features, not raw accelerometer signals.