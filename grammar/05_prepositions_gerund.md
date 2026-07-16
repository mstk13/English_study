# Week 5: 前置詞 + 不定詞 vs 動名詞

## 5.1 前置詞

### 解説

### 時間の前置詞

| 前置詞 | 使う場面 | 例 |
|--------|---------|-----|
| **at** | 時刻・ピンポイント | at 3pm, at night, at noon |
| **on** | 日・曜日 | on Monday, on July 16th, on my birthday |
| **in** | 月・年・季節・長い期間 | in July, in 2026, in the morning, in 3 hours |
| **by** | 期限「〜までに」 | by Friday, by the end of the month |
| **until** | 継続「〜まで(ずっと)」 | until 5pm, until the deadline |
| **for** | 期間の長さ | for 3 hours, for 2 weeks |
| **since** | 起点「〜以来」 | since 2020, since last Monday |
| **during** | 期間中「〜の間に」 | during the meeting, during summer |

### 場所の前置詞

| 前置詞 | 使う場面 | 例 |
|--------|---------|-----|
| **at** | 地点 | at the office, at the station |
| **in** | 空間の中 | in the room, in Tokyo, in the pipeline |
| **on** | 表面・上 | on the table, on the screen, on the board |

### 技術文脈で頻出の前置詞

| 前置詞句 | 意味 | 例 |
|---------|------|-----|
| depend **on** | 〜に依存する | The frequency depends **on** the critical path. |
| result **in** | 〜という結果になる | This change results **in** better timing. |
| consist **of** | 〜から成る | The pipeline consists **of** 5 stages. |
| lead **to** | 〜につながる | Higher utilization leads **to** more congestion. |
| deal **with** | 〜を扱う | This module deals **with** memory access. |
| focus **on** | 〜に焦点を当てる | We should focus **on** timing closure first. |
| according **to** | 〜によると | According **to** the spec, the max frequency is 1GHz. |
| due **to** | 〜が原因で | The failure was due **to** a setup violation. |
| in terms **of** | 〜の観点で | In terms **of** area, the 4×4 array is better. |
| instead **of** | 〜の代わりに | We used SRAM instead **of** flip-flops. |

---

### 練習問題 5-1

適切な前置詞を入れなさい。

**時間:**
1. The meeting starts _______ 10am _______ Monday.
2. We need to finish the report _______ Friday.
3. I've been working here _______ April.
4. The simulation ran _______ 3 hours.
5. _______ the review, she found 2 critical issues.

**場所:**
6. The register file is _______ the ID stage.
7. The results are displayed _______ the screen.
8. We tested it _______ the lab.

**技術:**
9. The clock frequency depends _______ the critical path length.
10. This design consists _______ a CPU and an accelerator.
11. The DRC failure was due _______ metal spacing violations.
12. _______ terms _______ performance, design A is better.
13. Higher utilization leads _______ more routing congestion.
14. We used a FIFO instead _______ a simple register.
15. According _______ the timing report, WNS is -0.3ns.

---

## 5.2 不定詞 (to do) vs 動名詞 (-ing)

### 解説

動詞によって **to do** が来るか **-ing** が来るか決まっている。

### to do を取る動詞

| 動詞 | 例 |
|------|-----|
| want | I **want to improve** the design. |
| need | We **need to fix** this bug. |
| decide | They **decided to use** sky130. |
| plan | I **plan to finish** by Friday. |
| expect | We **expect to achieve** timing closure. |
| hope | I **hope to pass** all tests. |
| agree | She **agreed to review** my code. |
| learn | I'm **learning to use** OpenROAD. |

### -ing を取る動詞

| 動詞 | 例 |
|------|-----|
| enjoy | I **enjoy debugging** hardware. |
| avoid | **Avoid using** global signals. |
| finish | We **finished testing** the module. |
| consider | **Consider adding** more pipeline stages. |
| suggest | I **suggest running** the tests again. |
| keep | **Keep checking** the waveform. |
| mind | Do you **mind sharing** your screen? |
| practice | I need to **practice speaking** English. |

### 意味が変わる動詞（重要！）

| 動詞 | to do | -ing |
|------|-------|------|
| **stop** | stop **to check** = チェックするために立ち止まる | stop **checking** = チェックするのをやめる |
| **remember** | remember **to save** = 忘れずに保存する(これから) | remember **saving** = 保存したことを覚えている(過去) |
| **try** | try **to fix** = 修正しようと努力する | try **fixing** = 試しに修正してみる |
| **forget** | forget **to send** = 送るのを忘れる(これから) | forget **sending** = 送ったことを忘れる(過去) |

### 前置詞の後は常に -ing

- I'm interested **in learning** RISC-V.
- Thank you **for helping** me.
- I'm looking forward **to meeting** you. (to は前置詞なので -ing)
- I'm good **at writing** testbenches.

---

### 練習問題 5-2

to do / -ing の正しい形を入れなさい。

1. I want _______ (learn) more about NoC architecture.
2. She enjoys _______ (write) RTL code.
3. We decided _______ (use) a weight-stationary dataflow.
4. Avoid _______ (use) blocking assignments in sequential logic.
5. I need _______ (review) the timing report.
6. Consider _______ (add) a pipeline register here.
7. He finished _______ (debug) the testbench.
8. They agreed _______ (help) with the physical design.

意味の違いに注意して訳しなさい。

9. I stopped **to check** the waveform. → 意味:
10. I stopped **checking** the waveform. → 意味:
11. Remember **to save** your work before closing. → 意味:
12. I remember **saving** the file yesterday. → 意味:
13. Try **to fix** the timing violation. → 意味:
14. Try **using** a different clock constraint. → 意味:

前置詞 + -ing の形にしなさい。

15. I'm interested _______ _______ (work) on AI processors.
16. She's good _______ _______ (optimize) timing.
17. Thank you _______ _______ (review) my code.
18. I'm looking forward _______ _______ (join) the team.

---

## 解答

### 5-1
1. at / on
2. by
3. since
4. for
5. During
6. in
7. on
8. in (at でも可)
9. on
10. of
11. to
12. In / of
13. to
14. of
15. to

### 5-2
1. to learn
2. writing
3. to use
4. using
5. to review
6. adding
7. debugging
8. to help

意味:
9. 波形を確認するために立ち止まった
10. 波形を確認するのをやめた
11. 閉じる前に忘れずにセーブして（これからの行動）
12. 昨日ファイルをセーブしたことを覚えている（過去の記憶）
13. タイミング違反を修正しようと努力して
14. 試しに違うクロック制約を使ってみて

15. in working
16. at optimizing
17. for reviewing
18. to joining
