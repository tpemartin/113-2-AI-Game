# Chain of Thought and Strategic Reasoning

AI + 策略推理的結合練習

---

## ✦ What is Chain of Thought?

> **定義：**
> Chain of Thought（簡稱 CoT）是一種**將複雜任務拆解成一連串小步驟**來進行推理的方式。
> 此技巧有助於我們更清楚每個決策步驟背後的邏輯，並增進整體答案品質。

📌 **學生互動問題（Slido）：**

* 哪些情境會讓你需要一步步想清楚才能做決定？ （1分）

---

## 中午吃什麼

Chain of Thought prompting 的例子：

> 帶著我一步步思考，一次只引導我一個步驟，選擇中午吃什麼。


📌 **學生互動問題（Slido）：**

* 設定一個情境，讓ChatGPT帶著你一步步思考，貼上ChatGPT shared link。(2分)

---

## ✦ Rock-Paper-Scissors Example

Prompt that can create a chain of thought to find the best response in a game.

### 一次性 Prompting：

> "What is the best strategy in rock-paper-scissors?"

🌀 缺點：回答多半直接，不利於思考學習。


### 使用 CoT Prompting：

## ✦ Rock-Paper-Scissors Example

For Rock-Paper-Scissors, **take me step by step** to find the best response.



 - <https://chatgpt.com/share/68144a6a-f1b4-8006-96be-fdf07d4ad5e0>

CoT 可以幫助我們進行**層級式推理（Iterated Reasoning）**。

### 🎭 Battle of the Sexes


|          | 女：電影 🎬 | 女：球賽 🏟️ |
| -------- | ------- | -------- |
| 男：電影 🎬  | (1,2)   | (0,0)    |
| 男：球賽 🏟️ | (0,0)   | (2,1)    |

---

📌 **學生互動問題（Slido）：**

> 你的選擇？
>
> 再玩一回合，你的選擇？及ChatGPT使用CoT的過程。
>
> 如果你是男生，女生有1/2機率選擇電影，1/2機率選擇球賽，你會怎麼選擇？
>
> 如果你是男生，女生有2/3機率選擇電影，1/3機率選擇球賽，你會怎麼選擇？
