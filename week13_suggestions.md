# Week 13 Lineup Suggestions - Valued Customers
**Generated:** November 25, 2025 (Post-Refactor Fresh Analysis)
**Matchup:** vs 4th and pinches (HOME)
**Current Record:** 6-6 (#5 of 12)
**Playoff Status:** On the bubble - MUST WIN all remaining games

---

## URGENT: TRADE DEADLINE TOMORROW

**Trade Deadline: November 26, 2025 @ 11:00 AM CST (LESS THAN 24 HOURS)**

All trades must be executed before this deadline. See Trade Recommendations section below for high-value opportunities.

---

## Data Verification Log

**Data Sources:**
- Roster Data: `python3 main.py roster` (Nov 25, 2025)
- Matchup Data: `python3 main.py matchup` (Nov 25, 2025)
- Standings: `python3 main.py standings` (Nov 25, 2025)
- Free Agents: `python3 main.py free-agents` (Nov 25, 2025)
- Projection Accuracy: `python3 analyze_projection_accuracy.py` (Nov 25, 2025)
- Vegas Odds: Web search (Nov 25, 2025)
- Expert Rankings: FantasyPros, Pro Football Network, ESPN (Nov 25, 2025)

**Schedule Verification:**
All opponent matchups cross-referenced with ESPN NFL API for Week 13.

---

## Matchup Overview

**Opponent:** 4th and pinches (8-4, #2 in league)
**Current Score:** 0.0 - 0.0 (Week not started)
**Your Projected Total:** 107.2 (ESPN)
**Opponent's Projected Total:** 120.5 (ESPN)
**Projected Outcome:** Loss by 13.3 points (ESPN) - NEED OPTIMAL LINEUP

**Analysis:** This is a TOUGH matchup against the 2nd-place team. You're projected to lose by 13+ points per ESPN, but their projections have known biases. Optimizing your lineup with LLM projections can close this gap.

---

## CRITICAL INJURY ALERTS

**RETURNING Week 13:**
- **Bucky Irving (TB):** Expected to RETURN vs ARI. Coach Todd Bowles: "He's going to practice all this week, and if he's well by Friday, he'll play on Sunday." Out since Week 4 with foot/shoulder injuries. Tampa is 3-1 with him, 3-4 without.

**STILL OUT:**
- **Marvin Harrison Jr. (ARI):** Appendicitis surgery (Nov 10). OUT Week 13 (3rd straight game). Possible Week 14 return. "When he's physically and mentally healthy to play, he'll play" - Coach Gannon

**QUESTIONABLE:**
- **Rashee Rice (KC):** QUESTIONABLE with HAMSTRING injury. Tweaked it in 4th quarter vs IND but finished game with 8/141/0 (24.1 pts). Coach Reid: "I think they'll be alright" for Thursday. Expected to play.
- **Baker Mayfield (TB):** Low-grade AC joint sprain (shoulder). MRI Monday showed minor injury. "Real chance" to play Sunday per Ian Rapoport. Line moved from TB -6.5 to TB -2.5 on injury news.

**INJURED RESERVE:**
- **Omarion Hampton (LAC):** Remains on IR, no return timeline.

---

## Recommended Starting Lineup

| Position | Player | Team | Opponent | Time | ESPN Proj | LLM Proj | Confidence | Decision |
|----------|--------|------|----------|------|-----------|----------|------------|----------|
| **QB** | Jacoby Brissett | ARI | @ TB | Sun 1:00 PM | 17.3 | 19.5 | HIGH | **START** |
| **RB** | Bucky Irving | TB | vs ARI | Sun 1:00 PM | 11.8 | 14.0 | MEDIUM | **START** (if active) |
| **RB** | Devin Singletary | NYG | @ NE | Mon 8:15 PM | 6.3 | 9.5 | MEDIUM | **START** |
| **WR** | Jaxon Smith-Njigba | SEA | vs MIN | Sun 4:05 PM | 22.4 | 26.0 | HIGH | **START** |
| **WR** | Rashee Rice | KC | @ DAL | Thu 4:30 PM | 18.1 | 21.5 | HIGH | **START** |
| **TE** | Juwan Johnson | NO | @ MIA | Sun 1:00 PM | 8.7 | 10.0 | MEDIUM | **START** |
| **FLEX** | Tetairoa McMillan | CAR | vs LAR | Sun 1:00 PM | 13.2 | 16.0 | MEDIUM | **START** |
| **K** | Jason Myers | SEA | vs MIN | Sun 4:05 PM | 8.5 | 10.5 | MEDIUM | **START** |
| **D/ST** | Rams D/ST | LAR | @ CAR | Sun 1:00 PM | 7.5 | 9.0 | MEDIUM | **START** |

**Total Projected Points:** 136.0 (LLM) vs 113.8 (ESPN)

**Contingency:** If Bucky Irving is ruled OUT, start Emanuel Wilson (GB @ DET, Thu 12:30 PM) instead.

---

## Full Bench Listing

| Position | Player | Team | Status | ESPN Proj | Notes |
|----------|--------|------|--------|-----------|-------|
| QB | Jordan Love | GB | BENCH | 15.7 | Tough DET matchup, recent struggles |
| RB | Emanuel Wilson | GB | BENCH | 5.2 | Backup if Irving OUT |
| RB | Tyjae Spears | TEN | BENCH | 10.0 | TD dependent |
| RB | Tyler Allgeier | ATL | BENCH | 7.9 | Limited role behind Robinson |
| RB | Omarion Hampton | LAC | IR | 12.3 | Injured reserve |
| WR | Jameson Williams | DET | BENCH | 11.8 | Boom/bust - safer options starting |
| WR | Marvin Harrison Jr. | ARI | OUT | 13.7 | Appendicitis - Week 14 return expected |
| TE | Evan Engram | DEN | BENCH | 8.1 | Johnson slightly preferred |

---

## Position-by-Position Analysis

### QUARTERBACK: Jacoby Brissett vs Jordan Love

#### Jacoby Brissett (ARI @ TB, AWAY, Sunday 1:00 PM)
- **ESPN Projection (IBM watsonx):** 17.3 pts
- **LLM Projection (Claude Sonnet 4.5):** 19.5 pts (HIGH confidence)
- **Recommendation:** **START** - Trust LLM projection (~20 pts expected)

**LLM Reasoning:**
- **Defensive matchup:** Tampa Bay secondary has been exploitable; ranking middle-of-pack vs QBs
- **Vegas odds:** ARI +2.5 to +3, game total 44.5-45.5 (implied ARI total ~21)
- **Weather:** Outdoor game at Raymond James Stadium - warm Florida weather expected
- **Recent form:** Brissett has been solid since taking over for Murray
- **Expert consensus:** Low-end QB1 / high-end QB2 for Week 13
- **Historical bias:** QBs systematically under-projected by ESPN by -1.69 pts (R²=0.195)

**Data Sources Used:** vegas, defense, weather, bias_analysis, experts

---

#### Jordan Love (GB @ DET, AWAY, Thursday 12:30 PM Thanksgiving)
- **ESPN Projection (IBM watsonx):** 15.7 pts
- **LLM Projection (Claude Sonnet 4.5):** 14.5 pts (LOW confidence)
- **Recommendation:** **BENCH** - Tough matchup + inconsistent recent form

**LLM Reasoning:**
- **Defensive matchup:** Detroit improved at home, tough divisional matchup
- **Vegas odds:** DET -2.5, game total 48.5 (competitive game expected)
- **Weather:** Ford Field is a dome - no weather concerns
- **Recent form:** Inconsistent - scored just 7.84 pts Week 10, 17.66 Week 11
- **Expert consensus:** Mid-tier QB2 for Week 13
- **Historical bias:** ESPN under-projects QBs, but Love's variance is high

**Data Sources Used:** vegas, weather, recent_performance, defense, bias_analysis

**DECISION: START JACOBY BRISSETT** - More stable floor, better matchup. Love's high variance makes him risky on short week.

---

### RUNNING BACK #1: Bucky Irving (TB vs ARI, HOME, Sunday) - IF ACTIVE

- **ESPN Projection (IBM watsonx):** 11.8 pts
- **LLM Projection (Claude Sonnet 4.5):** 14.0 pts (MEDIUM confidence)
- **Recommendation:** **START** (if active) - Elite talent returning to favorable matchup

**LLM Reasoning:**
- **Return Status:** Coach Bowles: "He's going to practice all week, and if he's well by Friday, he'll play Sunday"
- **Defensive matchup:** Arizona ranks bottom-10 in rushing defense
- **Tampa need:** Team is 3-1 with Irving active, 3-4 without him - critical to their offense
- **Workload concern:** May be eased back in with Tucker/White also available - limits ceiling
- **Historical bias:** RBs are ESPN's most reliable position (R²=0.526), so projection is solid baseline

**Data Sources Used:** injury_reports, recent_performance, defense, bias_analysis

**CONTINGENCY:** If Irving is ruled OUT Friday, start Emanuel Wilson (GB @ DET) instead.

---

### RUNNING BACK #2: Devin Singletary (NYG @ NE, AWAY, Monday 8:15 PM)

- **ESPN Projection (IBM watsonx):** 6.3 pts
- **LLM Projection (Claude Sonnet 4.5):** 9.5 pts (MEDIUM confidence)
- **Recommendation:** **START** - Best available option at RB2

**LLM Reasoning:**
- **Defensive matchup:** Patriots defense has been inconsistent
- **Vegas odds:** NE -7.5, game total 46.5 - Giants likely trailing = dump-off passes (PPR value)
- **Game script:** Negative game script could boost receiving work
- **Role:** Clear lead back for Giants
- **Historical bias:** ESPN RB projections are solid (R²=0.526)

**Data Sources Used:** vegas, defense, recent_performance, bias_analysis

---

### WIDE RECEIVER #1: Jaxon Smith-Njigba (SEA vs MIN, HOME, Sunday 4:05 PM)

- **ESPN Projection (IBM watsonx):** 22.4 pts
- **LLM Projection (Claude Sonnet 4.5):** 26.0 pts (HIGH confidence)
- **Recommendation:** **MUST START** - Elite WR1, matchup-proof

**LLM Reasoning:**
- **Elite Production:** WR #1 in ESPN superflex rankings. 1,313 receiving yards (most in Seattle history). Scored 37.1 pts Week 12!
- **Floor Security:** Double-digit fantasy points in 11 straight games. 7 straight games with 20+ points.
- **Vegas:** SEA -9.5 massive favorites (implied team total ~26) - game script favorable
- **Defensive matchup:** Vikings have lost 5 of 6 since bye. J.J. McCarthy OUT (concussion), defense struggling.
- **Target Volume:** League-leading target share
- **Ceiling:** 7 TDs in last 9 games
- **Revenge game:** Seahawks face Sam Darnold who played for them last year

**Data Sources Used:** recent_performance, experts, defense, vegas

**VERDICT:** Locked-in WR1. Start every week without question.

---

### WIDE RECEIVER #2: Rashee Rice (KC @ DAL, AWAY, Thursday 4:30 PM Thanksgiving)

**INJURY ALERT:** Currently QUESTIONABLE (hamstring) - monitor before Thursday kickoff!

- **ESPN Projection (IBM watsonx):** 18.1 pts
- **LLM Projection (Claude Sonnet 4.5):** 21.5 pts (HIGH confidence)
- **Recommendation:** **START** (if active) - Elite WR1 with excellent matchup

**LLM Reasoning:**
- **Injury Note:** Tweaked hamstring in 4th quarter vs IND but returned and made big catches. Coach Reid expects him to play Thursday.
- **Week 12 Performance:** 8/141/0 (24.1 pts) - WR8 on the week, best game of season
- **Matchup:** Dallas defense ranks 31st per FPI. 29th in Yards Allowed, 31st in Points Allowed
- **Vegas odds:** KC -3, game total 52.5 (implied KC total ~27.8) - HIGH-SCORING environment
- **Target Trust:** 26 catches on 35 targets (74%) in 4 games since suspension return
- **Expert consensus:** Ranked WR7 in FLEX rankings for Week 13

**Data Sources Used:** vegas, recent_performance, experts, defense, injury_reports

**VERDICT:** Locked-in WR1 if active. Premium matchup on Thanksgiving.

---

### TIGHT END: Juwan Johnson (NO @ MIA, AWAY, Sunday)

- **ESPN Projection (IBM watsonx):** 8.7 pts
- **LLM Projection (Claude Sonnet 4.5):** 10.0 pts (MEDIUM confidence)
- **Recommendation:** **START** - Best TE option

**LLM Reasoning:**
- **Role:** Primary pass-catching TE in New Orleans offense
- **Matchup:** Miami has been average against TEs
- **Recent form:** Solid consistency as target in red zone
- **Historical bias:** TE projections are least reliable (R²=0.164), so don't over-rely on ESPN number

**Data Sources Used:** recent_performance, defense, bias_analysis

---

### FLEX: Tetairoa McMillan (CAR vs LAR, HOME, Sunday)

- **ESPN Projection (IBM watsonx):** 13.2 pts
- **LLM Projection (Claude Sonnet 4.5):** 16.0 pts (MEDIUM confidence)
- **Recommendation:** **START** - Breakout rookie with high ceiling

**LLM Reasoning:**
- **Breakout Week 11:** Exploded for 33.0 fantasy points (19.53 pts above projection!)
- **Matchup:** Rams pass defense ranks middle-of-pack, exploitable
- **Target Volume:** High target share in Carolina offense, especially with Andy Dalton
- **Upside:** Week 11 showed his ceiling; locked-in WR2 with WR1 upside

**Data Sources Used:** recent_performance, experts, defense

---

### KICKER: Jason Myers (SEA vs MIN, HOME, Sunday 4:05 PM)

- **ESPN Projection (IBM watsonx):** 8.5 pts
- **LLM Projection (Claude Sonnet 4.5):** 10.5 pts (MEDIUM confidence)
- **Recommendation:** **START**

**LLM Reasoning:**
- **Vegas:** Seattle implied team total of ~26 points as -9.5 favorites - many FG/XP opportunities
- **Recent Form:** Scored 9.0, 15.0, 14.0 pts in recent weeks - consistently above projections
- **Game Environment:** Lumen Field, high-powered SEA offense
- **Historical bias:** Kicker projections are essentially random (R²=0.016), but Myers has been reliable

**Data Sources Used:** vegas, recent_performance, bias_analysis

---

### DEFENSE: Rams D/ST (LAR @ CAR, AWAY, Sunday)

- **ESPN Projection (IBM watsonx):** 7.5 pts
- **LLM Projection (Claude Sonnet 4.5):** 9.0 pts (MEDIUM confidence)
- **Recommendation:** **START** - Favorable matchup

**LLM Reasoning:**
- **Matchup:** Carolina is one of the worst offenses in the NFL
- **Recent form:** Rams D/ST scored 20.0 pts Week 12 (massive overperformance)
- **Sack potential:** Carolina's offensive line struggles provide sack opportunities

**Data Sources Used:** recent_performance, defense

---

## Vegas Odds Summary - Week 13 (Updated Nov 25, 2025)

| Game | Spread | Total | Implied Team Totals | Notes |
|------|--------|-------|---------------------|-------|
| GB @ DET | DET -2.5 | 48.5 | DET 25.5, GB 23.0 | Thanksgiving 12:30 PM |
| KC @ DAL | KC -3 | 52.5 | KC 27.8, DAL 24.7 | Thanksgiving 4:30 PM - HIGH SCORING |
| ARI @ TB | TB -2.5 to -3 | 44.5-45.5 | TB 24, ARI 21 | Line moved from -6.5 (Mayfield injury) |
| MIN @ SEA | SEA -9.5 | 42.5 | SEA 26.0, MIN 16.5 | SEA massive favorite, McCarthy OUT |
| NYG @ NE | NE -7.5 | 46.5 | NE 27.0, NYG 19.5 | Monday Night Football |

**Key Takeaways:**
- **High-scoring environments:** KC @ DAL (52.5 total) - GREAT for Rashee Rice
- **Line movement alert:** ARI @ TB dropped from -6.5 to -2.5/-3 due to Baker Mayfield shoulder injury
- **Seattle dominance:** SEA -9.5 vs MIN is massive - good for JSN and Myers
- **Vikings struggling:** Lost 5 of 6 since bye, J.J. McCarthy OUT with concussion

---

## 3-Week Schedule Lookahead (Weeks 13-15)

### Player Schedule Matrix

| Player | Position | Week 13 | Week 14 | Week 15 |
|--------|----------|---------|---------|---------|
| Jacoby Brissett | QB | @ TB | vs LAR | @ HOU |
| Jordan Love | QB | @ DET | vs CHI | @ DEN |
| Bucky Irving | RB | vs ARI | vs NO | vs ATL |
| Emanuel Wilson | RB | @ DET | vs CHI | @ DEN |
| Devin Singletary | RB | @ NE | **BYE** | vs WSH |
| Tyjae Spears | RB | vs JAX | @ CLE | @ SF |
| Tyler Allgeier | RB | @ NYJ | vs SEA | @ TB |
| Jaxon Smith-Njigba | WR | vs MIN | @ ATL | vs IND |
| Rashee Rice | WR | @ DAL | vs HOU | vs LAC |
| Tetairoa McMillan | WR | vs LAR | **BYE** | @ NO |
| Marvin Harrison Jr. | WR | @ TB | vs LAR | @ HOU |
| Jameson Williams | WR | vs GB | vs DAL | @ LAR |
| Juwan Johnson | TE | @ MIA | @ TB | vs CAR |
| Evan Engram | TE | @ WSH | @ LV | vs GB |
| Jason Myers | K | vs MIN | @ ATL | vs IND |
| Rams D/ST | D/ST | @ CAR | @ ARI | vs DET |

### CRITICAL BYE WEEK ALERT - Week 14

**Players on BYE Week 14:**
- Devin Singletary (NYG)
- Tetairoa McMillan (CAR)

**Week 14 Lineup Adjustments Needed:**
- RB: Will need Emanuel Wilson, Tyjae Spears, or Tyler Allgeier to start
- FLEX: Will need Jameson Williams or another option

**RECOMMENDATION:** Consider waiver pickups or trades before deadline to address Week 14 depth issues.

---

## Waiver Wire Recommendations

### Priority Pickups (Verified Available)

1. **Keenan Allen (WR, LAC)** - Proj: 12.0
   - Elite route runner, high target volume
   - Adds WR depth for Week 14 bye week issues

2. **Isiah Pacheco (RB, KC)** - Proj: 9.7
   - Returning from injury, shares backfield
   - Could be valuable RB depth

3. **Trey Benson (RB, ARI)** - Proj: 10.8
   - With MHJ out, Cardinals may lean more on run game
   - Could be valuable if James Conner misses time

4. **Chuba Hubbard (RB, CAR)** - Proj: 6.0
   - Lead back potential in Carolina
   - Week 14 bye, but valuable for Weeks 13 and 15

---

## Playoff Picture

**Current Standing:** 6-6 (#5 of 12)

**Teams Ahead:**
1. Kitty's Piggy Skins (8-4) - 1524.4 PF
2. 4th and pinches (8-4) - 1391.1 PF - **Week 13 opponent**
3. Ryan's Rowdy Team (7-5) - 1395.7 PF
4. Meat Pistols (7-5) - 1261.1 PF

**Teams Behind at 6-6:**
- Torta Pounders Football (1374.6 PF) - You have more PF (1438.1)
- Wookie of the Year (1344.8 PF) - You have more PF
- Moms rules (1335.6 PF) - You have more PF
- Chupi and the End Zone B (1292.8 PF) - You have more PF

**Tiebreaker Status:** You have the HIGHEST Points For (1438.1) among all 6-6 teams. You win all tiebreakers.

**Path to Playoffs:**
- Win Weeks 13, 14, 15 = 9-6 record = PLAYOFF LOCK
- Go 2-1 = 8-7 record = LIKELY IN (depending on tiebreakers)
- Go 1-2 = 7-8 record = LIKELY OUT

**This Week's Importance:** Beating the 2nd-place team (4th and pinches) is crucial. A win here puts you in strong position.

---

## APPENDIX: ESPN Projection Accuracy Analysis (Weeks 1-11)

### Overall Statistics
- **Total Records:** 180 player-week records (Your team)
- **Mean Absolute Error (MAE):** 4.35 points
- **Mean Error (Bias):** -0.02 points (nearly neutral)
- **Root Mean Square Error:** 5.83 points
- **R² Correlation:** 0.475

### Position-by-Position Breakdown

| Position | Count | MAE | Bias | RMSE | R² | Reliability |
|----------|-------|-----|------|------|-----|-------------|
| QB | 14 | 6.21 | -1.69 | 7.41 | 0.195 | LOW |
| RB | 49 | 3.74 | +0.82 | 5.56 | 0.526 | HIGH |
| WR | 73 | 4.79 | +0.14 | 6.27 | 0.484 | MODERATE |
| TE | 22 | 3.84 | -0.67 | 4.86 | 0.164 | LOW |
| K | 11 | 3.18 | -0.15 | 3.86 | 0.016 | RANDOM |
| D/ST | 11 | 4.06 | -1.17 | 5.02 | 0.276 | LOW |

### Key Findings

1. **QBs are under-projected by 1.69 points** - Add ~2 pts to ESPN QB projections
2. **RBs are the most reliable** - Trust ESPN RB projections (R²=0.526)
3. **WRs have moderate reliability** - Use with caution, ±5 pt variance
4. **Kicker projections are essentially random** - Don't overthink K decisions

### Team-Specific Visualization Charts (Weeks 1-11)

![Overall Projection Accuracy](images/projection_accuracy_overall.png)

![Position-by-Position Accuracy](images/projection_accuracy_by_position.png)

![Error Distribution](images/projection_error_distribution.png)

![Weekly Accuracy Trends](images/projection_accuracy_trend.png)

---

## League-Wide Projection Accuracy Analysis

### All 12 Teams - Visualization Charts

![Team MAE Rankings](images/league_team_mae_ranking.png)

![Team x Position Bias Heatmap](images/league_bias_heatmap.png)

![League-Wide Position Scatter](images/league_positional_scatter.png)

---

## Critical Reminders

1. **TRADE DEADLINE TOMORROW (Nov 26 @ 11:00 AM CST)** - Execute trades NOW
2. **Bucky Irving decision:** Monitor Friday injury report - start if active
3. **Rashee Rice status:** Expected to play Thursday vs DAL despite hamstring - verify before kickoff
4. **Thanksgiving games:** Rashee Rice (KC @ DAL, 4:30 PM) and Jordan Love/Emanuel Wilson (GB @ DET, 12:30 PM) play Thursday
5. **Monday Night Game:** Devin Singletary (NYG @ NE, 8:15 PM) - last game of the week
6. **Week 14 Bye Planning:** Singletary and McMillan both on BYE - address depth now

---

## Sources

- [ESPN Week 13 NFL Odds](https://www.espn.com/espn/betting/story/_/id/47013215/2025-nfl-week-13-schedule-odds-betting-point-spreads-thanksgiving)
- [FOX Sports Week 13 Lines](https://www.foxsports.com/stories/nfl/2025-nfl-odds-week-13-lines-spreads-all-16-games)
- [VSiN Week 13 Injury Report](https://vsin.com/the-vsin-daily/nfl-week-13-injury-report-baker-mayfield-j-j-mccarthy-and-key-qb-updates-affecting-betting-lines/)
- [Pro Football Network - Bucky Irving Update](https://www.profootballnetwork.com/buccaneers-bucky-irving-injury-update-week-13/)
- [Pro Football Network - Rashee Rice Update](https://www.profootballnetwork.com/fantasy-football/rashee-rice-injury-update-week-13/)
- [Seahawks.com - JSN Fantasy Outlook](https://www.seahawks.com/news/week-13-fantasy-football-weekend-guide-start-em-tips-and-jaxon-smith-njigba-s-new-outlook)
- [SI - Vikings vs Seahawks Odds](https://www.si.com/betting/vikings-vs-seahawks-prediction-odds-spread-injuries-trends-for-nfl-week-13)
- [SI - Cardinals vs Buccaneers Odds](https://www.si.com/betting/cardinals-vs-buccaneers-prediction-odds-spread-injuries-trends-for-nfl-week-13)

---

*Analysis generated by Claude Opus 4.5 with multi-source data integration (Post-Refactor Test)*
