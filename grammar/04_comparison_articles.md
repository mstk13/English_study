# Week 4: 比較表現 + 冠詞

## 4.1 比較表現

### 解説

### 基本の3パターン

| パターン | 形 | 例 |
|---------|-----|-----|
| **比較級** | -er / more + than | This design is **faster than** the previous one. |
| **最上級** | -est / most | This is the **fastest** chip in the lineup. |
| **同等** | as ... as | This array is **as efficient as** the reference design. |

### 比較級のルール

| 語 | 比較級 | 最上級 |
|----|--------|--------|
| 短い語 (1音節) | fast → fast**er** | fast**est** |
| -y で終わる | easy → eas**ier** | eas**iest** |
| 長い語 (2音節以上) | efficient → **more** efficient | **most** efficient |
| 不規則 | good → **better** | **best** |
| 不規則 | bad → **worse** | **worst** |
| 不規則 | far → **further** | **furthest** |

### 重要パターン

**the + 比較級, the + 比較級** （〜すればするほど〜）
- **The more** pipeline stages we add, **the higher** the frequency.
- **The smaller** the process node, **the more** power we save.

**比較級 + and + 比較級** （だんだん〜）
- The design is getting **more and more** complex.
- Chips are becoming **smaller and smaller**.

**not as ... as** （〜ほど...ではない）
- The new tool is **not as fast as** the old one.
- My design is **not as power-efficient as** his.

**倍数表現**
- This chip is **twice as fast as** the previous generation.
- The array has **three times as many** PEs as the original.

---

### 練習問題 4-1

適切な形に変えなさい。

1. OpenROAD is _______ (good) than I expected.
2. This is the _______ (bad) timing violation I've ever seen.
3. The 4×4 array is _______ (efficient) than the 2×2.
4. The _______ (much) memory bandwidth we have, the _______ (good) the performance.
5. My simulation runs twice _______ _______ _______ (fast) yours.
6. This PDK is not _______ _______ _______ (well-documented) the other one.
7. The routing is getting _______ _______ _______ (congested).
8. She writes the _______ (clean) SystemVerilog on the team.

正しいものを選びなさい。

9. This chip is (more powerful / powerfuler) than the competitor.
10. He is the (most experienced / experiencedest) engineer here.
11. The result was (worse / more bad) than we thought.
12. This is (further / farther) from the target than expected.

---

## 4.2 冠詞 (a / the / 無冠詞)

### 解説

日本語にない概念なので最も間違いやすい。

### a / an (不定冠詞): 「ある1つの」「どれでもいい1つ」

- I found **a** bug in the code. （バグの1つ。初めて言及）
- She is **an** engineer. （職業。1人のエンジニア）
- We need **a** faster clock. （特定のではなく、とにかく速いクロック）

### the (定冠詞): 「その」「例の」「唯一の」

- I found a bug. → **The** bug was in the ALU. （さっき言ったバグ）
- **The** sun rises in the east. （1つしかない）
- Can you check **the** timing report? （どのレポートか互いにわかっている）
- **The** register file stores 32 values. （設計上1つしかない）

### 無冠詞: 一般論・抽象概念・不可算名詞

- **Software** is easier to change than **hardware**. （一般論）
- I'm studying **English**. （言語名）
- **Silicon** is a semiconductor. （物質名）
- We discussed **performance** and **power**. （抽象概念）

### 判断フロー

```
1. 特定のもの？ → the
2. 初めて出す？ 数えられる？ 単数？ → a/an
3. 一般論・抽象・不可算・複数の一般論？ → 無冠詞
```

### 間違いやすいケース

| ✕ | ○ | 理由 |
|---|---|------|
| I like the music. | I like **music**. | 音楽一般 → 無冠詞 |
| She is engineer. | She is **an** engineer. | 職業は a/an 必要 |
| The life is short. | **Life** is short. | 人生一般 → 無冠詞 |
| I went to the bed. | I went to **bed**. | go to bed は定型句 |
| Open the OpenROAD. | Open **OpenROAD**. | ツール名は無冠詞 |

### 定型句

| the あり | the なし |
|---------|---------|
| go to **the** office | go to **school/work/bed** |
| in **the** morning | at **night** |
| **the** internet | **breakfast/lunch/dinner** |
| play **the** piano | play **soccer** |

---

### 練習問題 4-2

a / an / the / 無冠詞(—) を入れなさい。

1. I need to buy _______ new laptop.
2. _______ laptop I bought last week is already slow.
3. She is _______ best engineer on _______ team.
4. _______ RISC-V is _______ open-source ISA.
5. I found _______ error in _______ code. _______ error was in line 42.
6. He goes to _______ gym every day.
7. _______ silicon is used to make _______ chips.
8. We had _______ meeting about _______ new design. _______ meeting lasted 2 hours.
9. _______ performance of _______ systolic array depends on _______ data reuse.
10. Can you send me _______ email about _______ timing violation we discussed?
11. She plays _______ piano and also likes _______ swimming.
12. I usually have _______ coffee for _______ breakfast.

---

## 解答

### 4-1
1. better
2. worst
3. more efficient
4. more / better
5. as fast as
6. as well-documented as
7. more and more congested
8. cleanest
9. more powerful
10. most experienced
11. worse
12. further

### 4-2
1. a
2. The
3. the / the
4. — / an
5. an / the / The
6. the
7. — / —
8. a / the (or a) / The
9. The / the / — (data reuse は一般概念)
10. an / the
11. the / — (スポーツは無冠詞)
12. — / — (coffee, breakfast は不可算/定型)
