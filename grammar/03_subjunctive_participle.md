# Week 3: 仮定法 + 分詞構文

## 3.1 仮定法

### 解説

仮定法 = **現実と違うこと**を仮定する表現。日本語の「もし〜だったら」。

### 仮定法過去（今の現実と違う仮定）

**形: If + 主語 + 過去形, 主語 + would/could/might + 原形**

| 現実 | 仮定法 |
|------|--------|
| I don't have enough time. | If I **had** enough time, I **would** optimize the pipeline. |
| She isn't here. | If she **were** here, she **could** help us debug. |
| We can't use this tool. | If we **could** use this tool, the flow **would** be faster. |

**注意:** be動詞は主語に関係なく **were** を使う
- If I **were** you, I would rewrite this module.
- If he **were** available, we would ask him.

### 仮定法過去完了（過去の現実と違う仮定）

**形: If + 主語 + had + 過去分詞, 主語 + would have + 過去分詞**

| 現実（過去） | 仮定法過去完了 |
|-------------|--------------|
| I didn't check the constraints. | If I **had checked** the constraints, I **would have found** the bug earlier. |
| We used the wrong PDK. | If we **hadn't used** the wrong PDK, the DRC **would have passed**. |

### I wish ...

| 今の願望 | I wish I **knew** more about NoC design. (知っていたらなぁ) |
|---------|-----|
| 過去の後悔 | I wish I **had studied** English harder in college. (勉強していたらなぁ) |
| 苛立ち | I wish this simulation **would** finish faster. |

---

### 練習問題 3-1

適切な形に変えなさい。

**仮定法過去:**
1. If I _______ (have) a better GPU, I _______ (run) the simulation faster.
2. If she _______ (be) on the team, we _______ (not / have) this problem.
3. If we _______ (know) the clock constraint, we _______ (set) the SDC correctly.
4. I _______ (redesign) the pipeline if I _______ (have) more time.
5. If the tool _______ (support) sky130, we _______ (can / use) it.

**仮定法過去完了:**
6. If I _______ (read) the datasheet, I _______ (not / make) that mistake.
7. If we _______ (run) more tests, we _______ (catch) the edge case.
8. The chip _______ (not / fail) if they _______ (verify) the timing properly.

**I wish:**
9. I wish I _______ (understand) the NoC protocol better.
10. I wish we _______ (start) the physical design earlier. (過去の後悔)

---

## 3.2 分詞構文

### 解説

分詞構文 = **接続詞+主語を省略**して文を短くする。書き言葉・フォーマルで多い。

### 現在分詞 (-ing): 同時・理由・条件

| 元の文 | 分詞構文 |
|--------|---------|
| **Because** I didn't know the spec, I made an error. | **Not knowing** the spec, I made an error. |
| **While** he was reviewing the code, he found a bug. | **Reviewing** the code, he found a bug. |
| **If** you use this method, you can reduce latency. | **Using** this method, you can reduce latency. |

### 過去分詞 (-ed): 受動の意味

| 元の文 | 分詞構文 |
|--------|---------|
| **Because** it was written in SystemVerilog, the code was easy to verify. | **Written** in SystemVerilog, the code was easy to verify. |
| **Because** the chip was designed for AI workloads, it has many MAC units. | **Designed** for AI workloads, the chip has many MAC units. |

### Having + 過去分詞: 先に起きたこと

| 元の文 | 分詞構文 |
|--------|---------|
| **After** I finished the synthesis, I started P&R. | **Having finished** the synthesis, I started P&R. |
| **After** we verified all test cases, we moved to tape-out. | **Having verified** all test cases, we moved to tape-out. |

### 現在分詞 vs 過去分詞の使い分け

- **-ing**: 主語が動作をする側 → "The engineer **designing** the chip..."
- **-ed**: 主語が動作を受ける側 → "The chip **designed** by the engineer..."

---

### 練習問題 3-2

分詞構文に書き換えなさい。

1. Because I didn't understand the timing report, I asked for help.
2. After she had completed the verification, she wrote the report.
3. While he was debugging the RTL, he noticed a race condition.
4. Because the module was optimized for area, it used fewer gates.
5. If you increase the pipeline stages, you can achieve higher frequency.

分詞構文を普通の文に戻しなさい。

6. Having reviewed the floorplan, we approved the design.
7. Not knowing the correct constraint, he used the default value.
8. Designed for low power, the chip consumes only 5W.

現在分詞 (-ing) か過去分詞 (-ed) を選びなさい。

9. The test (run) _______ overnight revealed 3 new bugs.
10. The engineer (work) _______ on the NoC is very experienced.
11. The report (write) _______ in English was hard to read for me.
12. The data (flow) _______ through the pipeline must be aligned.

---

## 解答

### 3-1
1. had / would run
2. were / would not have
3. knew / would set
4. would redesign / had
5. supported / could use
6. had read / would not have made
7. had run / would have caught
8. would not have failed / had verified
9. understood
10. had started

### 3-2
分詞構文に:
1. Not understanding the timing report, I asked for help.
2. Having completed the verification, she wrote the report.
3. Debugging the RTL, he noticed a race condition.
4. Optimized for area, the module used fewer gates.
5. Increasing the pipeline stages, you can achieve higher frequency.

普通の文に:
6. After we had reviewed the floorplan, we approved the design.
7. Because he didn't know the correct constraint, he used the default value.
8. Because the chip was designed for low power, it consumes only 5W.

-ing / -ed:
9. run (過去分詞 — テストは「実行された」側)
10. working (現在分詞 — エンジニアは「働いている」側)
11. written (過去分詞 — レポートは「書かれた」側)
12. flowing (現在分詞 — データは「流れている」側)
