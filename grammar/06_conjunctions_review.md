# Week 6: 接続詞・副詞 + 総復習

## 6.1 接続詞・接続副詞

### 解説

### 対比・譲歩（〜だけど）

| 語 | 品詞 | 使い方 | 例 |
|----|------|--------|-----|
| **although** | 接続詞 | Although + S + V, S + V | **Although** the design passed DRC, it failed LVS. |
| **even though** | 接続詞 | even thoughの方が驚き感あり | **Even though** we optimized it, the timing was still bad. |
| **despite** | 前置詞 | despite + 名詞/-ing | **Despite** the tight schedule, we finished on time. |
| **in spite of** | 前置詞 | = despite | **In spite of** the bugs, the chip worked. |
| **however** | 副詞 | 文頭/文中。カンマで区切る | The area is small. **However**, the power is high. |
| **nevertheless** | 副詞 | = however（よりフォーマル） | The test failed. **Nevertheless**, we learned a lot. |

**注意: although と despite の使い分け**
- although + **文 (S+V)**: Although **it was** difficult...
- despite + **名詞/-ing**: Despite **the difficulty** / Despite **being** difficult...
- ✕ Despite it was difficult... (文は来れない)
- ✕ Although the difficulty... (名詞だけは来れない)

### 原因・結果

| 語 | 品詞 | 使い方 | 例 |
|----|------|--------|-----|
| **because** | 接続詞 | because + S + V | We failed **because** the constraint was wrong. |
| **because of** | 前置詞 | because of + 名詞 | We failed **because of** the wrong constraint. |
| **since** | 接続詞 | = because (フォーマル) | **Since** we have limited time, let's prioritize. |
| **therefore** | 副詞 | 結果を述べる | The path is too long. **Therefore**, we need more stages. |
| **as a result** | 副詞句 | = therefore | The clock was too fast. **As a result**, setup violations occurred. |
| **due to** | 前置詞 | = because of | The failure was **due to** a hold violation. |

### 追加・列挙

| 語 | 使い方 | 例 |
|----|--------|-----|
| **in addition** | さらに | **In addition**, we need to check power. |
| **moreover** | さらに (フォーマル) | **Moreover**, the area exceeded the target. |
| **furthermore** | さらに (最もフォーマル) | **Furthermore**, the cost would increase. |
| **for example / for instance** | 例えば | **For example**, the MAC unit uses 2 cycles. |

### 対照

| 語 | 使い方 | 例 |
|----|--------|-----|
| **on the other hand** | 一方で | ASIC is fast. **On the other hand**, FPGA is flexible. |
| **in contrast** | 対照的に | Design A is area-efficient. **In contrast**, Design B focuses on speed. |
| **while / whereas** | 〜なのに対して | **While** Design A is small, Design B is fast. |

---

### 練習問題 6-1

適切な語を選びなさい。

1. (Although / Despite) the simulation took 10 hours, the results were worth it.
2. (Although / Despite) the long simulation time, the results were worth it.
3. The DRC passed. (However / Although), LVS still has errors.
4. The timing was bad (because / because of) we used the wrong SDC.
5. The timing was bad (because / because of) the wrong SDC.
6. We found 3 bugs. (Therefore / Because), we delayed the tape-out.
7. (While / However) the CPU is simple, the accelerator is complex.
8. The design is power-efficient. (In addition / In contrast), it is also small.

書き換えなさい（意味を変えずに）。

9. Although the test failed, we found useful data.
   → Despite ______________________________________
10. Because of the tight deadline, we skipped LVS.
    → Because ______________________________________
11. The area is large. However, the performance is excellent.
    → Although ______________________________________

---

## 6.2 総復習問題

全6週間の文法を混合した問題。

### Part A: 空欄補充

1. I _______ (work) on this project since last month.
2. By the time the review started, she _______ (already / finish) the report.
3. If we _______ (have) a faster tool, the flow _______ (take) less time.
4. The chip, _______ was designed for edge AI, consumes very little power.
5. This architecture is _______ (efficient) than the previous generation.
6. The RTL _______ (write) by the new engineer and _______ (review) by the lead.
7. We need _______ (complete) the DRC check before Friday.
8. I enjoy _______ (optimize) physical layouts.
9. _______ (finish) the verification, we moved on to synthesis.
10. The failure was due _______ a clock domain crossing issue.

### Part B: 誤文訂正

各文の誤りを見つけて訂正しなさい。

1. I have finished the report yesterday.
2. If I was you, I would rewrite this module.
3. The engineer which designed this is very skilled.
4. This chip is more better than the old one.
5. Despite it was raining, we went to the lab.
6. I want learning SystemVerilog.
7. She has been writing 3 reports today.
8. I remember to send the email last night.
9. The tool is not as faster as we expected.
10. He stopped to smoke last year.

### Part C: 和文英訳

1. 私はこの会社で3年間働いています。(今も働いている)
2. もしもっと時間があれば、テストケースを増やすのに。
3. OpenROADで設計されたチップは、DRCをパスした。
4. パイプラインの段数が多いほど、周波数は高くなる。
5. 合成が終わるまで、私はずっとドキュメントを書いていた。

---

## 解答

### 6-1
1. Although
2. Despite
3. However
4. because
5. because of
6. Therefore
7. While
8. In addition

書き換え:
9. Despite the test failing (/ the failed test), we found useful data.
10. Because the deadline was tight, we skipped LVS.
11. Although the area is large, the performance is excellent.

### 6-2 Part A
1. have been working
2. had already finished
3. had / would take
4. which
5. more efficient
6. was written / reviewed
7. to complete
8. optimizing
9. Having finished
10. to

### 6-2 Part B
1. I ~~have finished~~ **finished** the report yesterday. (yesterday → 過去形)
2. If I ~~was~~ **were** you... (仮定法は were)
3. The engineer ~~which~~ **who** designed... (人は who)
4. ~~more better~~ → **better** (better は既に比較級)
5. ~~Despite~~ **Although** it was raining... (despite の後に文は不可)
6. I want ~~learning~~ **to learn**... (want + to do)
7. She ~~has been writing~~ **has written** 3 reports. (回数=結果 → 現在完了)
8. I remember ~~to send~~ **sending** the email last night. (過去のことを覚えている → -ing)
9. not as ~~faster~~ **fast** as (as...as の間は原級)
10. He stopped ~~to smoke~~ **smoking** last year. (吸うのをやめた → -ing)

### 6-2 Part C
1. I have worked (/ have been working) at this company for 3 years.
2. If I had more time, I would add more test cases.
3. The chip (which was) designed with OpenROAD passed the DRC.
4. The more pipeline stages we add, the higher the frequency.
5. Until the synthesis was finished (/ completed), I had been writing documentation.
