# ModelSim Simulator和Vivado Simulator仿真Vitis HLS效果比较

测试环境：  
| 项目 | 内容 |  
| :--- | :--- |
| CPU | `i7-10700F` |
| 操作系统 | `Windows 10 19042` |
| ModelSim Simulator版本 | `2020.4` |
| Vivado Simulator版本 | `2020.2` |
| Vitis HLS版本 | `2020.2` |
| 测试代码 | [dianhsu-cnn-base](https://github.com/fpga-accels/dianhsu-cnn-base) |
| 测试时间 | `2021/02/07` |
## 仿真时间
| - | Verilog | VHDL |
| :--- | :--- | :--- |
| ModelSim | `???` | `00:12:54` |
| Vivado | `01:05:45` | `00:45:02` |

> ModelSim仿真HLS的Verilog代码出错，暂时还没解决
