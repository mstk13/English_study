# Week 2: 関係代名詞 + 受動態

## 2.1 関係代名詞

### 解説

関係代名詞は**2つの文を1つにつなげる**もの。

| 関係代名詞 | 使う対象 | 例 |
|-----------|---------|-----|
| **who** | 人 | The engineer **who** designed this chip is brilliant. |
| **which** | もの・こと | The tool **which** we use is OpenROAD. |
| **that** | 人・もの両方 | The bug **that** I found was critical. |
| **whose** | 所有 | The designer **whose** code I reviewed left the company. |
| **where** | 場所 | The lab **where** we test the chips is on the 3rd floor. |

### 制限用法 vs 非制限用法（カンマの有無）

| 種類 | 例 | 意味 |
|------|-----|------|
| **制限用法** (カンマなし) | The report **that he wrote** was clear. | 「彼が書いた」レポート（他にもレポートがある中で特定） |
| **非制限用法** (カンマあり) | The report, **which he wrote last week**, was clear. | レポートの補足情報（1つしかない前提） |

**ルール:**
- 非制限用法（カンマあり）では **that は使えない**
- ✕ The CPU, that I designed, passed all tests.
- ○ The CPU, **which** I designed, passed all tests.

### 関係代名詞の省略

**目的格**のとき省略できる:
- The tool **(that/which)** we use is OpenROAD. → The tool we use is OpenROAD. ✓
- The engineer **(who/that)** I met was helpful. → The engineer I met was helpful. ✓

**主格**のときは省略できない:
- The engineer **who** designed this → 省略不可 ✕

---

### 練習問題 2-1

適切な関係代名詞を入れなさい（省略可能なら「省略可」と書く）。

1. The register file _______ holds 32 entries is in the ID stage.
2. The testbench _______ I wrote last night has a bug.
3. She is the designer _______ pipeline CPU passed all riscv-tests.
4. OpenROAD, _______ is open-source, supports the sky130 PDK.
5. The lab _______ we run simulations is always cold.
6. The constraint _______ we forgot to add caused a timing violation.
7. He showed me the layout, _______ looked impressive.
8. The signal _______ name I can't remember was causing the glitch.

---

## 2.2 受動態

### 解説

**能動態**: 主語が動作をする
**受動態**: 主語が動作を受ける → **be + 過去分詞**

| 時制 | 能動態 | 受動態 |
|------|--------|--------|
| 現在 | They **use** OpenROAD. | OpenROAD **is used** by many teams. |
| 過去 | She **designed** the chip. | The chip **was designed** by her. |
| 現在完了 | We **have completed** the test. | The test **has been completed**. |
| 未来 | They **will release** it. | It **will be released** next month. |
| 進行形 | They **are testing** it. | It **is being tested** now. |

### いつ受動態を使うか

1. **誰がやったか重要じゃない**とき: "The chip **was fabricated** in TSMC's 5nm process."
2. **結果やプロセスに焦点**を当てたいとき: "The data **is transferred** through the NoC."
3. **技術文書・論文**では受動態が多い: "The algorithm **is implemented** in hardware."

### よくある形

| パターン | 例 |
|---------|-----|
| It is said that... | **It is said that** this architecture is efficient. |
| be known to... | Tenstorrent **is known to** use a dataflow architecture. |
| be supposed to... | The test **is supposed to** pass. |
| be expected to... | The clock frequency **is expected to** reach 1GHz. |

---

### 練習問題 2-2

能動態を受動態に書き換えなさい。

1. The team designed the systolic array.
2. We have not verified the timing constraints yet.
3. They will manufacture the chip next year.
4. Someone found a critical bug in the RTL.
5. The engineers are reviewing the floorplan right now.

受動態を能動態に書き換えなさい。

6. The signal was driven by the output buffer.
7. The test results have been published on the wiki.
8. The new architecture is being evaluated by the team.

適切な受動態の形に直しなさい。

9. This tool (use) _______ by engineers worldwide.
10. The report (write) _______ by her last week.
11. The layout (not / complete) _______ yet.
12. The chip (expect) _______ to tape out in Q3.
13. All bugs (fix) _______ before the release.
14. The data (transfer) _______ through the NoC right now.

---

## 解答

### 2-1
1. which / that
2. which / that（省略可 — 目的格）
3. whose
4. which（非制限用法なので that は不可）
5. where
6. which / that（省略可 — 目的格）
7. which（非制限用法なので that は不可）
8. whose

### 2-2
能動態→受動態:
1. The systolic array was designed by the team.
2. The timing constraints have not been verified yet.
3. The chip will be manufactured next year.
4. A critical bug was found in the RTL.
5. The floorplan is being reviewed by the engineers right now.

受動態→能動態:
6. The output buffer drove the signal.
7. They/Someone has published the test results on the wiki.
8. The team is evaluating the new architecture.

空欄:
9. is used
10. was written
11. has not been completed
12. is expected
13. have been fixed (must be fixed も文脈による)
14. is being transferred
