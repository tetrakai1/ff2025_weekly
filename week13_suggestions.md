# Week 13 Fantasy Football Analysis - Valued Customers

**Week 13 | November 27 - December 1, 2025**
**Opponent:** 4th and pinches (8-4)
**Current Record:** 6-6 (5th place)

---

## Executive Summary

**Win Probability: 83.1%** | **Expected Margin: +31.9 pts**

Strong Week 13 matchup against a division rival. Our team has significant projected advantages across multiple positions, particularly at WR where Jaxon Smith-Njigba (historic pace) and Rashee Rice (elite matchup vs Dallas) lead the way. The Monte Carlo simulation shows 83% win probability with an expected margin of nearly 32 points.

**Key Storylines:**
- **Jaxon Smith-Njigba** continues record-breaking pace ([1,313 yds, on track for 2,000+](https://www.cbssports.com/nfl/players/3162959/jaxon-smith-njigba/fantasy/))
- **Rashee Rice** faces NFL's worst pass defense ([Dallas allows 18 WR TDs](https://www.si.com/onsi/fantasy/rankings/drake-maye-rashee-rice-top-fantasy-football-offenses-week-13))
- **Bucky Irving** [returns from 7-game injury absence](https://www.profootballnetwork.com/fantasy-football/bucky-irving-start-sit-injury-update-week-13/) vs vulnerable ARI rush D
- **Tetairoa McMillan** emerging as CAR WR1 ([748 yds, 54 rec through 11 games](https://www.cbssports.com/nfl/players/28877124/tetairoa-mcmillan/fantasy/))

---

## Recommended Starting Lineup

| Position | Player | Team | Opponent | ESPN Proj | LLM Proj | XGB Boom | Conf | Notes |
|----------|--------|------|----------|-----------|----------|----------|------|-------|
| QB | Jacoby Brissett | ARI | @ TB | 17.3 | 23.8 | 19.5% | HIGH | 18+ pts in all 5 starts, TB allows 5th most QB FPTS |
| RB | Bucky Irving | TB | vs ARI | 11.8 | 15.3 | 9.5% | MEDIUM | Returns from injury, ARI allows 142 rush yds/game |
| RB | Tyjae Spears | TEN | vs JAX | 9.9 | 8.0 | 13.2% | LOW | 50% snap share, light rain expected |
| WR | Jaxon Smith-Njigba | SEA | vs MIN | 21.9 | 34.3 | 50.0% | HIGH | WR1 overall, 11 straight 75+ yd games, MIN weak secondary |
| WR | Rashee Rice | KC | @ DAL | 18.1 | 25.9 | 13.2% | HIGH | 20%+ target share, DAL worst vs WR (18 TDs allowed) |
| TE | Juwan Johnson | NO | @ MIA | 8.7 | 14.0 | 21.0% | MEDIUM | 5 straight games 10+ FPTS, MIA 4th worst vs TE |
| FLEX | Tetairoa McMillan | CAR | vs LAR | 13.2 | 16.5 | 21.1% | MEDIUM | CAR WR1, 22% target share, 10-pt underdog limits ceiling |
| K | Jason Myers | SEA | vs MIN | 8.5 | 11.5 | 12.1% | MEDIUM | SEA -11.5 favorites, high FG opportunities |
| D/ST | Rams D/ST | LAR | @ CAR | 7.5 | 8.9 | 18.1% | HIGH | 10-pt favorites, CAR implied total 17.25 |

**Total ESPN Projection:** 128.2 pts
**Total LLM Projection:** 163.1 pts

---

## XGBoost Boom/Bust Analysis

The XGBoost model (v13) provides probability-based boom/bust predictions using historical data and weekly context:

| Player | Position | XGB Boom | XGB Bust | Confidence | Decision |
|--------|----------|----------|----------|------------|----------|
| Jaxon Smith-Njigba | WR | **50.0%** | 14.0% | HIGH | **High boom** - Start with confidence |
| Jordan Love | QB | 28.4% | 20.9% | MEDIUM | Moderate upside, bench for Brissett |
| Marvin Harrison Jr. | WR | 25.7% | 18.2% | MEDIUM | Injured - avoid |
| Keenan Allen | WR | 25.3% | 24.3% | MEDIUM | Bench - solid floor, limited upside |
| Evan Engram | TE | 25.0% | 25.6% | MEDIUM | Bench behind Juwan |
| Tetairoa McMillan | WR | 21.1% | 18.1% | HIGH | Start - CAR WR1, high target share |
| Juwan Johnson | TE | 21.0% | 25.0% | HIGH | Start - hot streak + matchup |
| Jameson Williams | WR | 20.6% | 20.3% | MEDIUM | Boom/bust - bench |
| Jacoby Brissett | QB | 19.5% | 43.3% | MEDIUM | Start - 5-game hot streak |
| Rams D/ST | D/ST | 18.1% | 32.9% | MEDIUM | Start - elite matchup |
| Rashee Rice | WR | 13.2% | 27.0% | HIGH | Start - elite opportunity |
| Tyjae Spears | RB | 13.2% | 33.1% | HIGH | Start - best available |
| Bucky Irving | RB | 9.5% | **54.5%** | HIGH | **High bust risk** - injury return |
| Omarion Hampton | RB | 8.3% | 54.4% | MEDIUM | IR - unavailable |

**High Boom Targets:** JSN (50.0%)
**High Bust Risks:** Bucky Irving (54.5%), Omarion Hampton (54.4%)

---

## Position-by-Position Analysis

### QB Decision: Jacoby Brissett vs Jordan Love

#### Jacoby Brissett (ARI @ TB, Sun 1:00 PM)
- **ESPN Projection (IBM watsonx):** 17.3 pts
- **LLM Projection (Claude Opus 4.5):** 23.8 pts (HIGH confidence)
- **XGBoost:** 19.5% boom, 43.3% bust
- **Recommendation:** START

**LLM Reasoning:**
- 5 consecutive games of 18+ fantasy points since becoming starter
- 1,887 passing yards in 6 games (most by any QB in 6-game span)
- [Tampa Bay allows 5th most fantasy points to QBs](https://www.si.com/fantasy/fab-s-five-fantasy-football-quarterback-streamers-for-week-13-start-jacoby-brissett-01kb0et5mjkx)
- Expert consensus: QB8 for week
- Pass-heavy Cardinals offense with no running game

**Boom/Bust Signals:**
- HOT streak (5 games): +boom adjustment
- Favorable matchup: TB defense allows 19.4 FPG to QBs

---

### WR Analysis

#### Jaxon Smith-Njigba (SEA vs MIN, Sun 4:05 PM)
- **ESPN Projection:** 21.9 pts
- **LLM Projection:** 34.3 pts (HIGH confidence)
- **XGBoost:** **50.0% boom**, 14.0% bust
- **Recommendation:** MUST-START - Best receiver in fantasy

**LLM Reasoning:**
- WR1 overall for Week 13 (expert consensus)
- [1,313 receiving yards (on pace for 2,030 - record pace)](https://www.cbssports.com/nfl/players/3162959/jaxon-smith-njigba/fantasy/)
- 11 consecutive games with 75+ receiving yards
- 35% target share (elite volume)
- Minnesota starting 3rd string QB Max Brosmer
- Vegas: SEA -11.5, implied team total 26.5 ([source](https://www.vegasinsider.com/nfl/nfl-week-13-odds-2025/))

**Props:**
- Receiving yards O/U: 105.5
- Anytime TD: -115

---

#### Rashee Rice (KC @ DAL, Thu 4:30 PM)
- **ESPN Projection:** 18.1 pts
- **LLM Projection:** 25.9 pts (HIGH confidence)
- **XGBoost:** 13.2% boom, 27.0% bust
- **Recommendation:** START - Elite matchup

**LLM Reasoning:**
- [Dallas allows MOST fantasy points to WRs](https://www.si.com/onsi/fantasy/rankings/drake-maye-rashee-rice-top-fantasy-football-offenses-week-13) (30th ranked defense)
- 18 WR touchdowns allowed by Dallas (NFL worst)
- 20%+ target share in every game this season
- Season-high 141 yards in Week 12
- Leads KC in red zone targets (13)
- Zone coverage killer (+42% boost vs zone)

**Props:**
- Receiving yards O/U: 77.5
- Anytime TD: -120

---

#### Tetairoa McMillan (CAR vs LAR, Sun 1:00 PM)
- **ESPN Projection:** 13.2 pts
- **LLM Projection:** 16.5 pts (MEDIUM confidence)
- **XGBoost:** 21.1% boom, 18.1% bust
- **Recommendation:** START at FLEX - CAR WR1 with high volume

**LLM Reasoning:**
- CAR WR1 as a rookie ([748 yds, 54 rec through 11 games](https://www.cbssports.com/nfl/players/28877124/tetairoa-mcmillan/fantasy/))
- 22% target share with increasing trend
- Week 11 breakout: 8 rec, 130 yds, 2 TDs (33 PPR pts)
- Building chemistry with Bryce Young
- LAR defense allows 15th most to WRs

**Concerns:**
- CAR 10-pt underdog limits ceiling
- Implied team total only 17.25 pts
- Tough matchup vs LAR pass rush

---

### RB Analysis

#### Bucky Irving (TB vs ARI, Sun 1:00 PM)
- **ESPN Projection:** 11.8 pts
- **LLM Projection:** 15.3 pts (MEDIUM confidence)
- **XGBoost:** 9.5% boom, **54.5% bust**
- **Recommendation:** START with caution - High bust risk

**LLM Reasoning:**
- [Returning from 7-game injury absence](https://www.profootballnetwork.com/fantasy-football/bucky-irving-start-sit-injury-update-week-13/) (subluxated shoulder + foot sprain)
- Arizona allows 142 rushing yards per game (last 3 weeks)
- Arizona ranked 21st DVOA vs rush
- [May be eased back into action](https://www.profootballnetwork.com/fantasy-football/bucky-irving-injury-update-week-13/) (expect 13-15 touches)
- Pre-injury: Scored 13.9+ PPR in all 4 starts

**Bust Risk:**
- Injury return limits volume
- Committee with Rachaad White possible

---

#### Tyjae Spears (TEN vs JAX, Sun 1:00 PM)
- **ESPN Projection:** 9.9 pts
- **LLM Projection:** 8.0 pts (LOW confidence)
- **XGBoost:** 13.2% boom, 33.1% bust
- **Recommendation:** START - Best available option

**LLM Reasoning:**
- 50% snap share split with Tony Pollard
- Jacksonville favored by 6.5 points
- Light rain expected (may help run game)
- Floor play only, limited upside

---

### TE Analysis

#### Juwan Johnson (NO @ MIA, Sun 1:00 PM)
- **ESPN Projection:** 8.7 pts
- **LLM Projection:** 14.0 pts (MEDIUM confidence)
- **XGBoost:** 21.0% boom, 25.0% bust
- **Recommendation:** START - Hot streak + favorable matchup

**LLM Reasoning:**
- 5 consecutive games with 10+ fantasy points
- [Miami allows 4th-6th most fantasy points to TEs](https://www.si.com/fantasy/fab-s-five-fantasy-football-tight-end-streamers-for-week-13-start-juwan-johnson-01kb0f8wdsnd)
- Only 24% rostered (streaming gem)
- 2nd pass-catching option for Saints
- Low team total (17.75 implied) limits ceiling

**Props:**
- Receiving yards O/U: 44.5

---

## Bench Analysis

| Position | Player | Team | Status | ESPN | LLM | XGB Boom/Bust | Notes |
|----------|--------|------|--------|------|-----|---------------|-------|
| QB | Jordan Love | GB | BENCH | 15.7 | 17.7 | 28.4%/20.9% | Thanksgiving dome game, shootout potential |
| WR | Marvin Harrison Jr. | ARI | QUESTIONABLE | 13.7 | 10.6 | 25.7%/18.2% | [Appendicitis surgery Nov 10](https://www.profootballnetwork.com/fantasy-football/marvin-harrison-jr-start-sit-injury-update-week-13/), check status |
| WR | Jameson Williams | DET | BENCH | 11.8 | 11.5 | 20.6%/20.3% | Boom/bust, Thanksgiving game |
| WR | Keenan Allen | LAC | BENCH | 12.0 | 14.3 | 25.3%/24.3% | Consistent, LAC heavy run game |
| RB | Omarion Hampton | LAC | IR | 12.3 | 15.4 | 8.3%/54.4% | Injured - unavailable |
| RB | Emanuel Wilson | GB | BENCH | 5.6 | 8.5 | 10.7%/34.2% | Backup role |
| TE | Evan Engram | DEN | BENCH | 8.1 | 6.5 | 25.0%/25.6% | Adjusting to new system |

---

## Vegas Lines Summary

| Game | Spread | Total | Implied Team Totals |
|------|--------|-------|---------------------|
| KC @ DAL (Thu) | KC -3.5 | 52.5 | KC 28.0, DAL 24.5 |
| GB @ DET (Thu) | DET -2.5 | 48.5 | DET 25.5, GB 23.0 |
| ARI @ TB | TB -3.0 | 43.5 | TB 23.25, ARI 20.25 |
| SEA vs MIN | SEA -11.5 | 41.5 | SEA 26.5, MIN 15.0 |
| NO @ MIA | MIA -6.0 | 41.5 | MIA 23.75, NO 17.75 |
| JAX @ TEN | JAX -6.5 | 42.0 | JAX 24.25, TEN 17.75 |
| LAR @ CAR | LAR -10.0 | 44.5 | LAR 27.25, CAR 17.25 |
| LAC vs LV | LAC -8.5 | 40.5 | LAC 24.5, LV 16.0 |

---

## Opponent Analysis (4th and pinches)

**Opponent Projected Total:** 132.4 pts
**Key Injuries:** Baker Mayfield (QUESTIONABLE - shoulder)

If Baker Mayfield sits, Shedeur Sanders would start (6.0 EV vs 17+ for Mayfield).

**Bench Substitution Scenario:**
- Baker Mayfield OUT (15% probability): Sanders subs in (-11 pt swing)

---

## Waiver Wire Notes

**Free Agents to Monitor:**
- Hunter Henry (TE, NE) - Proj 11.2, strong TE option
- Terry McLaurin (WR, WSH) - Proj 11.0, Daniels returning
- Isiah Pacheco (RB, KC) - Proj 9.7, may return from injury

---

## Historical Accuracy Context

**Your Team's ESPN Projection Accuracy (Weeks 1-12):**
- Overall MAE: 4.45 pts
- QB Bias: -2.00 pts (ESPN under-projects QBs)
- RB R-squared: 0.541 (most reliable)
- WR R-squared: 0.498 (reliable)

---

## APPENDIX: Visualization Charts

### Team-Specific Visualization Charts
![Overall Projection Accuracy](images/projection_accuracy_overall.png)
![Position-by-Position Accuracy](images/projection_accuracy_by_position.png)
![Error Distribution](images/projection_error_distribution.png)
![Weekly Accuracy Trends](images/projection_accuracy_trend.png)

### League-Wide Visualization Charts
![Team MAE Rankings](images/league_team_mae_ranking.png)
![Team x Position Bias Heatmap](images/league_bias_heatmap.png)
![League-Wide Position Scatter](images/league_positional_scatter.png)

### Monte Carlo Report
[Week 13 MC Report](mc_reports/week13_mc_report.html)

---

*Analysis generated: November 28, 2025*
*Model: Claude Opus 4.5 with XGBoost v13*
*Data sources: ESPN API, Vegas odds, expert rankings, weekly context*

---

## Sources

- [Jacoby Brissett QB Streamer Rankings](https://www.si.com/fantasy/fab-s-five-fantasy-football-quarterback-streamers-for-week-13-start-jacoby-brissett-01kb0et5mjkx) - SI Fantasy
- [Rashee Rice Elite Matchup vs Cowboys](https://www.si.com/onsi/fantasy/rankings/drake-maye-rashee-rice-top-fantasy-football-offenses-week-13) - SI Fantasy
- [Bucky Irving Injury Return Update](https://www.profootballnetwork.com/fantasy-football/bucky-irving-start-sit-injury-update-week-13/) - PFN
- [Jason Myers Kicker Rankings](https://www.si.com/fantasy/week-13-fantasy-football-kicker-rankings-jason-myers-moves-to-the-top-01kaxxwp022f) - SI Fantasy
- [Rams D/ST Streaming Analysis](https://www.fantasypoints.com/nfl/articles/2025/week-13-streaming-dsts-and-kickers) - Fantasy Points
- [Marvin Harrison Jr. Injury Status](https://www.profootballnetwork.com/fantasy-football/marvin-harrison-jr-start-sit-injury-update-week-13/) - PFN
- [Jaxon Smith-Njigba Record Pace](https://www.cbssports.com/nfl/players/3162959/jaxon-smith-njigba/fantasy/) - CBS Sports
- [NFL Week 13 Betting Lines](https://www.vegasinsider.com/nfl/nfl-week-13-odds-2025/) - Vegas Insider
- [Juwan Johnson TE Rankings](https://www.si.com/fantasy/fab-s-five-fantasy-football-tight-end-streamers-for-week-13-start-juwan-johnson-01kb0f8wdsnd) - SI Fantasy
- [Jordan Love Injury Update](https://www.profootballnetwork.com/fantasy-football/jordan-love-fantasy-hub-week-13-2025/) - PFN
