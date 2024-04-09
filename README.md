![image](https://github.com/DengYaosheng/TDR-Complex-Wired-Networks-failure-analysis/assets/41530023/4eaca8e2-3ccd-4f6e-b901-5cc628a1ec25)
# Fault diagnosis method of cable network based on time domain reflectometry （TDR）

# Principle of TDR
![image](https://github.com/DengYaosheng/TDR-Complex-Wired-Networks-failure-analysis/assets/41530023/16ce3ab1-fe73-4ea9-9e2c-2276b8d5522e)


# Parameters
![image](https://github.com/DengYaosheng/TDR-Complex-Wired-Networks-failure-analysis/assets/41530023/132e5275-5a5d-48cd-a213-671a1bee0c24)


# Result 
## Data recording of short-circuit fault measurement results at different fault distances
![image](https://github.com/DengYaosheng/TDR-Complex-Wired-Networks-failure-analysis/assets/41530023/bcf752d5-936b-4c34-812d-419f55f2fbfc)
![image](https://github.com/DengYaosheng/TDR-Complex-Wired-Networks-failure-analysis/assets/41530023/a90b05d2-ccc3-4146-83c2-a5b0c5700037)
![image](https://github.com/DengYaosheng/TDR-Complex-Wired-Networks-failure-analysis/assets/41530023/480fd2fd-6ada-4e42-8254-2d67a4a16b8c)

| 实际故障距离 / Actual Fault Distance (m) | 反射延迟时间/ Reflect Delay (ms) | 测试故障距离/ Test Fault Distance (m) | 相对误差/ Relative Error (%) |
|---------------------------------------------|---------------------------------------|-------------------------------------------|--------------------------------------|
| 100                                         | 2.49                                  | 100.845                                   | 0.85                                 |
| 300                                         | 7.51                                  | 304.155                                   | 1.38                                 |
| 400                                         | 9.96                                  | 403.38                                    | 0.85                                 |
| 700                                         | 17.41                                 | 705.105                                   | 0.73                                 |
| 1000                                        | 24.88                                 | 1007.64                                   | 0.76                                 |

## Data recording of fault measurement results at different open points
![image](https://github.com/DengYaosheng/TDR-Complex-Wired-Networks-failure-analysis/assets/41530023/7c285a3b-8a66-49d3-b340-d9bd8cd22166)
![image](https://github.com/DengYaosheng/TDR-Complex-Wired-Networks-failure-analysis/assets/41530023/39348b1a-adc2-46a2-ad6d-00f66d7acefc)
![image](https://github.com/DengYaosheng/TDR-Complex-Wired-Networks-failure-analysis/assets/41530023/644691e8-f34d-4ae7-8dc6-551ecaa58007)
According to the analysis in the figure above, the round-trip time of the fault signal on the cable can be obtained, and the distance between the fault terminal and the cable beginning can be obtained by substituting the formula, as follows
![image](https://github.com/DengYaosheng/TDR-Complex-Wired-Networks-failure-analysis/assets/41530023/02c055c7-ac2e-4546-b5a2-f2314f691a02)

| 实际故障距离（m） / Actual Fault Distance (m) | 反射延迟时间( ) / Reflect Delay (ms) | 测试故障距离(m) / Test Fault Distance (m) | 相对误差（%） / Relative Error (%) |
|---------------------------------------------|---------------------------------------|-------------------------------------------|--------------------------------------|
| 100                                         | 2.56                                  | 103.68                                    | 3.68                                 |
| 300                                         | 7.51                                  | 304.15                                    | 1.38                                 |
| 400                                         | 1.00                                  | 405.00                                    | 1.25                                 |
| 700                                         | 17.41                                 | 705.11                                    | 0.73                                 |
| 1000                                        | 24.88                                 | 1007.67                                   | 0.764                                |

## Low resistance fault diagnosis experimental data
![image](https://github.com/DengYaosheng/TDR-Complex-Wired-Networks-failure-analysis/assets/41530023/63e140ee-1183-43c9-b7bd-e91c443b9240)
![image](https://github.com/DengYaosheng/TDR-Complex-Wired-Networks-failure-analysis/assets/41530023/41584935-4287-4125-b344-c8eec0717d37)
![image](https://github.com/DengYaosheng/TDR-Complex-Wired-Networks-failure-analysis/assets/41530023/e26afc7c-62a4-4f06-b5d9-7e4f3d01ec81)
![image](https://github.com/DengYaosheng/TDR-Complex-Wired-Networks-failure-analysis/assets/41530023/e60883d0-3ac8-4742-80ee-ae4700bd8f1e)
![image](https://github.com/DengYaosheng/TDR-Complex-Wired-Networks-failure-analysis/assets/41530023/27587eb6-15a6-4001-aeb6-dd001912eea2)

| 渡阻值大小 / Crossing Resistance (Ω) | 实际故障距离 / Valid Distance (m) | 反射延迟时间 / Reflect Delay (μs) | 测试故障距离 / Test Distance (m) | 相对误差（%） / R-error |
|--------------------------------------|------------------------------------|-----------------------------------|---------------------------------|-----------------------|
| 0.001                                | 100                                | 2.47                              | 100.035                         | 0.04                  |
|                                      | 600                                | 14.84                             | 601.02                          | 0.17                  |
|                                      | 1100                               | 27.35                             | 1107.675                        | 0.70                  |
| 0.01                                 | 100                                | 2.48                              | 100.44                          | 0.44                  |
|                                      | 600                                | 14.91                             | 603.855                         | 0.64                  |
|                                      | 1100                               | 27.41                             | 1110.105                        | 0.92                  |
| 0.1                                  | 100                                | 2.47                              | 100.035                         | 0.04                  |
|                                      | 600                                | 14.89                             | 603.045                         | 0.51                  |
|                                      | 1100                               | 27.39                             | 1109.295                        | 0.85                  |
![image](https://github.com/DengYaosheng/TDR-Complex-Wired-Networks-failure-analysis/assets/41530023/6bfab477-c667-407a-85d1-1df11eb6e143)

## Cable network main trunk open circuit fault data recording
![image](https://github.com/DengYaosheng/TDR-Complex-Wired-Networks-failure-analysis/assets/41530023/2c262f35-5d5d-4b51-bf91-a243eefbacdc)
![image](https://github.com/DengYaosheng/TDR-Complex-Wired-Networks-failure-analysis/assets/41530023/adf0c06a-0282-4f4c-a2ea-48ea48afa059)
![image](https://github.com/DengYaosheng/TDR-Complex-Wired-Networks-failure-analysis/assets/41530023/f5ad6bc5-5b96-4476-b08d-fe366f07fddf)

| 实际故障距离 / Actual Fault Distance (m) | 反射延迟时间/ Reflect Delay (ms) | 测试故障距离/ Test Fault Distance (m) | 相对误差/ Relative Error (%) |
|----------------------------------------|----------------------------------|--------------------------------------|------------------------------|
| 100                                    | 2.5                              | 101.25                               | 1.25                         |
| 200                                    | 4.99                             | 202.10                               | 1.05                         |
| 250                                    | 6.25                             | 253.13                               | 1.25                         |
| 300                                    | 7.48                             | 302.94                               | 0.98                         |


## Y-type cable network branch open circuit fault diagnosis simulation experiment data recording
When a high-frequency signal is injected into a cable, the cable will transmit the signal to the equivalent model of the RLCG transmission line, and this is the object of analysis. The topology structure of the minimum network unit Y-type cable network studied in this chapter is shown in Figure 4.1, and its transmission line model can be applied to the topology structure shown in the Figure below.
![image](https://github.com/DengYaosheng/TDR-Complex-Wired-Networks-failure-analysis/assets/41530023/122ef9a9-6891-4313-bd53-a20f6c182cb0)
According to the formula, the pulse signal obtained from the detection port of the signal can be used as the incident pulse signal through different paths and transmitted to the detection port under the action of cable attenuation and time delay.

![image](https://github.com/DengYaosheng/TDR-Complex-Wired-Networks-failure-analysis/assets/41530023/022c0bde-9ca0-495c-a3ce-1d8154f4f94a)
![image](https://github.com/DengYaosheng/TDR-Complex-Wired-Networks-failure-analysis/assets/41530023/704cfe20-c54d-4dfc-9268-a653d9465c27)
![image](https://github.com/DengYaosheng/TDR-Complex-Wired-Networks-failure-analysis/assets/41530023/873d05a6-31a3-4764-abf3-1a4207d6ec75)


| 实际故障距离 / Actual Fault Distance (m) | 反射延迟时间/ Reflect Delay (ms) | 测试故障距离/ Test Fault Distance (m) | 相对误差/ Relative Error (%) |
|----------------------------------------|----------------------------------|--------------------------------------|------------------------------|
| 100                                    | 2.48                             | 100.44                               | 0.44                         |
| 200                                    | 4.96                             | 200.88                               | 0.44                         |
| 250                                    | 6.23                             | 252.315                              | 0.926                        |
| 300                                    | 7.5                              | 303.75                               | 1.25                         |
