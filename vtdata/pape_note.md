# Premises to do T-test

- Normal Distribution -> Normality test
- Equality of Variances -> Equality test
- paired *T*-test / ANOVA

## paired Data

- T_condition1 - T_condition2, S_average_condition1 - S_average_condition2
- RT1 - RT2, RS1 - RS2
- TT1 - TT2, **TS1 - TS2**

# Time Data

Target Time: the time consumed by the rotation from the start to a certain target

Round Time: total of 20 target time, the time consumed by shooting all 20 target for once

Condition Time: total of 4 round time, the time consumed by finishing one condition of experiment 

# Speed Data

Average Angular Velocity 

$$
\omega = \frac{\Delta \theta}{\Delta t}
$$

$$
\overline \omega_c = \sum\sum \theta_t / E(t_c) , 
\overline \omega_r = \sum \theta_t / E(t_r) , 
\overline \omega_t = \theta_t / E(t_t) ,
$$



Time data was preferred because they were raw data.

But time data was not suitable for comparison between targets, because time depends on angular displacement.

If mean is used,
$$
\overline \omega_t = \frac{\theta_t}{\overline t_t},
\overline \omega_t \neq \frac{\sum (\frac{\theta_t}{\overline t_t})}{4},
$$
Average Speed is the displacement divided by average time, not the mean of displacement divided by time

# Figures

## Round Time, Normality Test

- Whether Round Time has a normal distribution on **14 User**

### D’Agostino-Pearson Normality Test

### Q-Q Plot

**Quantile-quantile plot**

Validate whether two sets of data come from the same distribution

<img src="C:\Users\USER\Desktop\photo\png\combo (1).png" alt="combo (1)" style="zoom:50%;" />



### Violin Plot

Show the distribution of data

Observe the mean and median

<img src="C:\Users\USER\Desktop\photo\png\combo (3).png" alt="combo (3)" style="zoom:50%;" />

### Box Plot

Show the distribution of data

Observe the mean and median

<img src="C:\Users\USER\Desktop\photo\png\combo (2).png" alt="combo (2)" style="zoom:50%;" />

## Condition Time - User, T-test



| Test                                    | DV             | IV                      | Repeat    | H0                     | Result                                                       |
| --------------------------------------- | -------------- | ----------------------- | --------- | ---------------------- | ------------------------------------------------------------ |
| T-test: Condition Time, Inter-Condition | Condition Time | 2 Condition             | 14 User   | T_C1 = T_C2 ?          | 2 condition -> not same, effective                           |
| ANOVA: Round Time, Inter-Round          | Round Time     | 2 Condition, 4 Round    | 14 User   | condition x round ?    | 2 condition -> not same, effective; 4 rounds -> same, even; no related |
| ANOVA: Target Speed, Inter-Target       | Target Speed   | 2 Condition, 20 Target  | 14 User   | condition x target ?   | 2 condition -> not same, effective; 20 target -> not same, uneven; related |
| ANOVA: Target Speed, Inter-User         | Target Speed   | 2 Condition, 14 User    | 20 Target | condition x user ?     | 2 condition -> not same, effective; 14 user -> not same, uneven; related |
| 20 T-test: Target Time, Inter-Condition | Target Time    | 2 Condition             | 14 User   | S_T1 = S_T2 ?          | 2 condition -> (not) same , (not) effective                  |
| ANOVA: Target Speed, Inter-Target       | Target Speed   | 3 Latitude, 7 Longitude | 14 User   | latitude x longitude ? | 3 latitude -> not same, uneven; 7 longitude -> not same,     |



## Target Speed, Normality Test

- Whether Target Speed has a normal distribution on **20 Targets**

### Q-Q Plot

<img src="C:\Users\USER\Desktop\photo\png\combo (4).png" alt="combo (4)" style="zoom:50%;" />

### Violin Plot

<img src="C:\Users\USER\Desktop\photo\png\combo (5).png" alt="combo (5)" style="zoom:50%;" />

### Box Plot

<img src="C:\Users\USER\Desktop\photo\png\combo (6).png" alt="combo (6)" style="zoom:50%;" />

## Target Speed/Time, 20 t-test

 ### Target Speed

<img src="C:\Users\USER\Desktop\photo\png\combo (7).png" alt="combo (7)" style="zoom:50%;" />

### Target Time

<img src="C:\Users\USER\Desktop\photo\png\combo (8).png" alt="combo (8)" style="zoom:50%;" />

## Target Time

### Bar Chart

<img src="C:\Users\USER\Desktop\photo\png\combo (13).png" alt="combo (13)" style="zoom:50%;" />

### Line Chart

<img src="C:\Users\USER\Desktop\photo\png\combo (14).png" alt="combo (14)" style="zoom:50%;" />

### Heat Map

![combo (17)](C:\Users\USER\Desktop\photo\png\combo (17).png)

## Target Speed

### Bar Chart

<img src="C:\Users\USER\Desktop\photo\png\combo (9).png" alt="combo (9)" style="zoom:50%;" />

### Line Chart

<img src="C:\Users\USER\Desktop\photo\png\combo (10).png" alt="combo (10)" style="zoom:50%;" />



## Ratio of Target Speed

### Line Chart

<img src="C:\Users\USER\Desktop\photo\png\combo (11).png" alt="combo (11)" style="zoom:50%;" />

### Heat Map



![combo (19)](C:\Users\USER\Desktop\photo\png\combo (19).png)



## Ratio of Target Time

### Line Chart

<img src="C:\Users\USER\Desktop\photo\png\combo (15).png" alt="combo (15)" style="zoom:50%;" />