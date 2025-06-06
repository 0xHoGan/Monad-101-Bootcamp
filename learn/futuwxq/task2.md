## 第二章：Solidity 快速入门

### 一、填空题

1. Solidity 中存储成本最高的变量类型是`storage`变量，其数据永久存储在区块链上。
2. 使用`constant`关键字声明的常量可以节省 Gas 费，其值必须在编译时确定。
3. 当合约收到不带任何数据的以太转账时，会自动触发`receive`函数。

---

### 二、选择题

4. 函数选择器(selector)的计算方法是：  
   **B)** 函数名哈希的前 4 字节

5. 以下关于 mapping 的叙述错误的是：  
   **C)** 可以通过`length`属性获取大小

---

### 三、简答题

6. `require`、`assert`、`revert`三者的使用场景差异：

   - `require`：用于验证输入或状态条件，失败时退还剩余 Gas
   - `assert`：用于检查内部错误，失败时消耗所有 Gas
   - `revert`：用于主动回滚交易，可自定义错误信息，退还剩余 Gas

7. 实际执行时会调用`B`合约的`foo()`函数，因为 Solidity 的继承顺序是从右到左，`B`是最后继承的合约。

8. 两种写法的本质区别：
   - `call`：更灵活，可以发送任意数据，Gas 限制由调用者指定
   - `transfer`：固定 Gas 限制为 2300，主要用于简单的 ETH 转账
