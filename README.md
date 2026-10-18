# proto2_yaw_pcb

## 役割

Yaw 軸の制御基板（Rev B）。Nucleo F303K8 と IMU を載せ、Yaw 軸モータの制御と、砲塔・車体への電源中継を行う。

## 主要部品

| 部品 | 型番 | 用途 |
|---|---|---|
| マイコンボード | NUCLEO-F303K8 | 制御 |
| CAN トランシーバ | MCP2562-E/P | CAN × 2 コネクタ |
| モータドライバ | DRV8835 | Yaw 軸モータ |
| IMU | BNO055 | Yaw 角 |
| 電源入力コネクタ | AMASS XT30U-M × 2 | アクチュエータ系、制御系 |
| 電源出力コネクタ | JST PH 8P × 1、AMASS XT30U-F × 1、JST PH 6P × 2 | アクチュエータ系、制御系 |
| CAN 終端抵抗 | 120 Ω | |

回路図は [proto2_yaw_b.pdf](./proto2_yaw_b.pdf)、部品表は [bom.csv](./bom.csv)、3D は [proto2_yaw_b.step](./proto2_yaw_b.step)。

## ライセンス

© Rabbits Robotics、[CERN-OHL-P-2.0](./LICENSE)。
