# 八皇后问题工程化实践
## 项目简介
基于回溯法实现八皇后问题求解器，包含完整的单元测试和工程化结构。

## 运行方式
```python
from src.eight_queens import solve
# 求解8皇后
solutions = solve(8)
print(f"8皇后解数量：{len(solutions)}")