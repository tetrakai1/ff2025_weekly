# Week 13 Lineup Suggestions - Valued Customers
**Generated:** November 27, 2025 (Thanksgiving Day)
**Matchup:** vs 4th and pinches (HOME)
**Current Record:** 6-6 (#5 of 12)
**Playoff Status:** On the bubble - every win crucial for playoff positioning

---

## Data Verification Log

**Data Sources:**
- Roster Data: `python3 main.py roster` (Nov 27, 2025)
- Matchup Data: `python3 main.py matchup` (Nov 27, 2025)
- Free Agents: `python3 main.py free-agents` (Nov 27, 2025)
- Standings: `python3 main.py standings` (Nov 27, 2025)
- Projection Accuracy: `./run_projection_analysis.sh --week 13 --matchup` (Nov 27, 2025)
- Monte Carlo Report: `python3 generate_weekly_mc_report.py --week 13` (Nov 27, 2025)

**Schedule Verification:**
All opponent matchups cross-referenced with NFL.com and ESPN.com Week 13 official schedule (Nov 27, 2025).

**Key Games This Week:**
- **Thanksgiving Thursday:** GB @ DET (Jordan Love, Jameson Williams), KC @ DAL (Rashee Rice)
- **Sunday:** ARI @ TB (Brissett, Bucky Irving), SEA vs MIN (JSN, Myers), CAR @ LAR (McMillan, Rams D/ST)
- **Sunday:** NO @ MIA (Juwan Johnson), LAC vs LV (Keenan Allen), TEN @ JAX (Spears)

---

## Matchup Overview

**Opponent:** 4th and pinches (8-4, #2 in league)
**Your Projected Total:** 112.2 (ESPN) / 131.0 (LLM)
**Opponent's Projected Total:** 122.7 (ESPN) / 116.3 (LLM)
**Monte Carlo Win Probability:** 68.7%
**Expected Margin:** +14.6 pts

**Opponent's Top Threats:**
- Jahmyr Gibbs (RB): Elite RB1 in high-powered Lions offense
- Trey McBride (TE): Top-tier TE with heavy target volume
- DK Metcalf (WR): QUESTIONABLE - potential bench substitution

**Key Opponent Injuries:**
- Baker Mayfield (QB): QUESTIONABLE - shoulder injury (potential backup: Shedeur Sanders)
- DK Metcalf (WR): QUESTIONABLE

**Analysis:** Monte Carlo simulation gives us a 68.7% win probability despite being underdogs on ESPN projections. The key advantage is our LLM projections account for real-time context that ESPN (IBM watsonx) misses, including injury impacts and matchup adjustments.

---

## CRITICAL INJURY ALERTS

**OUT - Marvin Harrison Jr. (ARI):** Appendicitis surgery (Nov 10). **Returned to practice Wednesday** - QUESTIONABLE for Week 13. ESPN still projecting 13.7 pts (BUG) - LLM projection 9.4 pts if active, 0.0 if out.

**RETURNING - Bucky Irving (TB):** Full practice Wednesday. Expected to play Week 13 vs ARI on a **pitch count**. Coach Bowles says he'll be "eased back" similar to Chris Godwin's return (~36% snaps).

**INJURED RESERVE - Omarion Hampton (LAC):** Remains on IR, no return timeline.

---

## Recommended Starting Lineup

| Position | Player | Team | Opponent | Time | ESPN Proj | LLM Proj | Conf | Decision |
|----------|--------|------|----------|------|-----------|----------|------|----------|
| **QB** | Jacoby Brissett | ARI | @ TB | Sun 1:00 PM | 17.3 | 17.9 | HIGH | **START** |
| **RB** | Bucky Irving | TB | vs ARI | Sun 1:00 PM | 11.8 | 18.0 | MED | **START** |
| **RB** | Emanuel Wilson | GB | @ DET | Thu 12:30 PM | 5.2 | 7.4 | LOW | **START** |
| **WR** | Jaxon Smith-Njigba | SEA | vs MIN | Sun 4:05 PM | 21.9 | 23.2 | HIGH | **START** |
| **WR** | Rashee Rice | KC | @ DAL | Thu 4:30 PM | 18.1 | 20.2 | HIGH | **START** |
| **TE** | Juwan Johnson | NO | @ MIA | Sun 1:00 PM | 8.7 | 10.8 | MED | **START** |
| **FLEX** | Tetairoa McMillan | CAR | @ LAR | Sun 4:25 PM | 13.2 | 13.7 | MED | **START** |
| **K** | Jason Myers | SEA | vs MIN | Sun 4:05 PM | 8.5 | 10.9 | MED | **START** |
| **D/ST** | Rams D/ST | LAR | vs CAR | Sun 4:25 PM | 7.5 | 8.8 | HIGH | **START** |

**Total Projected Points:** 131.0 (LLM) vs 112.2 (ESPN)

---

## Full Bench Listing

| Position | Player | Team | Status | ESPN Proj | LLM Proj | Conf | Notes |
|----------|--------|------|--------|-----------|----------|------|-------|
| QB | Jordan Love | GB | BENCH | 15.7 | 15.7 | MED | Tough matchup vs DET - struggled to 7.1 pts in Week 12 |
| RB | Tyjae Spears | TEN | BENCH | 9.9 | 8.4 | LOW | Committee back with Pollard - flex only in desperation |
| RB | Devin Singletary | NYG | BENCH | 6.3 | 4.5 | LOW | Brutal matchup @ DAL - no start value |
| WR | Marvin Harrison Jr. | ARI | QUEST | 13.7 | 9.4 | LOW | ESPN BUG - still projecting. First practice since surgery |
| WR | Keenan Allen | LAC | BENCH | 12.0 | 12.7 | MED | WR36 - declining target share, borderline flex |
| WR | Jameson Williams | DET | BENCH | 11.8 | 10.8 | LOW | BUST ALERT - 0.0 pts Week 12, tough GB matchup |
| TE | Evan Engram | DEN | BENCH | 8.1 | 6.5 | LOW | Declining role - Johnson clearly better |
| RB | Omarion Hampton | LAC | IR | 12.3 | 15.4 | N/A | Injured Reserve - not available |

---

## Position-by-Position Analysis

### QUARTERBACK: Jacoby Brissett vs Jordan Love

#### Jacoby Brissett (ARI @ TB, AWAY, Sunday 1:00 PM)
- **ESPN Projection (IBM watsonx):** 17.3 pts
- **LLM Projection (Claude Sonnet 4.5):** 17.9 pts (HIGH confidence)
- **Recommendation:** **START** - Consistent QB1 production, favorable matchup

**LLM Reasoning:**
- **Defensive matchup:** Buccaneers secondary has been torched repeatedly - allowing most fantasy PPG to QBs over past 3 weeks
- **Recent form:** Attempted 44+ passes in 4 of 6 starts, scored 18+ fantasy pts in ALL of them
- **Pass volume:** Set NFL record with 47 completions vs 49ers (Week 11) - elite passing game
- **Expert consensus:** SI.com ranks him as QB9 for Week 13, "strong QB1 week firmly in play"
- **Weather:** Raymond James Stadium outdoor but warm conditions expected
- **Historical bias:** QBs systematically under-projected by ESPN by -2.00 pts (R²=0.169)

**Data Sources Used:** vegas, defense, recent_performance, experts, bias_analysis

---

#### Jordan Love (GB @ DET, AWAY, Thursday 12:30 PM)
- **ESPN Projection (IBM watsonx):** 15.7 pts
- **LLM Projection (Claude Sonnet 4.5):** 15.7 pts (MEDIUM confidence)
- **Recommendation:** **BENCH** - Worst fantasy finish of the year last week

**LLM Reasoning:**
- **Recent disaster:** 7.1 fantasy pts vs Vikings (Week 12) - worst performance of season
- **Passing struggles:** Hasn't surpassed 200 passing yards in last 3 games
- **Defensive matchup:** Lions rank 15th vs pass (210.5 yards allowed) - middle of pack
- **Historical Thanksgiving:** Usually plays well vs Lions (268 yds, 3 TDs Thanksgiving 2023)
- **Expert consensus:** CBS predicts Packers win 34-31, Love "will play big" - but too risky after bust
- **Weather:** Ford Field dome - perfect conditions

**Data Sources Used:** vegas, defense, recent_performance, experts, bias_analysis

**DECISION: START JACOBY BRISSETT** - His floor is higher (18+ in all 6 starts) vs Love's bust potential (7.1 pts last week).

---

### RUNNING BACK #1: Bucky Irving (TB vs ARI, HOME, Sunday 1:00 PM)
- **ESPN Projection (IBM watsonx):** 11.8 pts
- **LLM Projection (Claude Sonnet 4.5):** 18.0 pts (MEDIUM confidence)
- **Recommendation:** **START** - Returning from injury with favorable matchup

**LLM Reasoning:**
- **Injury status:** Full practice Wednesday - cleared to play. Coach Bowles expects pitch count (~36% snaps like Godwin's return)
- **Missed time:** Out since Week 4 with shoulder/foot injuries
- **Matchup:** Cardinals rank 17th vs run (114.2 YPG allowed), 22nd in fantasy PPG to RBs
- **Backfield context:** Sean Tucker and Rachaad White expanded roles, but Irving is the most talented back
- **Upside:** High ceiling (boom-or-bust) but even limited snaps could produce vs weak run D
- **Baker Mayfield:** QUESTIONABLE with shoulder injury - backup Teddy Bridgewater could mean more conservative playcalling
- **Expert consensus:** CBS ranks as No. 2 fantasy RB starter - high ceiling play

**Data Sources Used:** injury_reports, defense, recent_performance, experts, vegas

**WARNING:** Pitch count limits ceiling. Monitor pregame reports for snap allocation.

---

### RUNNING BACK #2: Emanuel Wilson (GB @ DET, AWAY, Thursday 12:30 PM)
- **ESPN Projection (IBM watsonx):** 5.2 pts
- **LLM Projection (Claude Sonnet 4.5):** 7.4 pts (LOW confidence)
- **Recommendation:** **START** (by necessity) - RB2 role despite low ceiling

**LLM Reasoning:**
- **Week 12 explosion:** 26.5 actual pts on 14.5 ESPN projection - massive overperformance
- **Role:** With Josh Jacobs limited, Wilson became lead back last week
- **Matchup:** Lions have strong run defense, but Thanksgiving games often feature RB-heavy scripts
- **Vegas odds:** Packers +3 underdogs (O/U 47.5) - trailing game script could limit rushing
- **Historical bias:** ESPN RB projections most reliable (R²=0.541) - but 5.2 seems too low given expanded role

**Data Sources Used:** vegas, defense, recent_performance, bias_analysis

---

### WIDE RECEIVER #1: Jaxon Smith-Njigba (SEA vs MIN, HOME, Sunday 4:05 PM)
- **ESPN Projection (IBM watsonx):** 21.9 pts
- **LLM Projection (Claude Sonnet 4.5):** 23.2 pts (HIGH confidence)
- **Recommendation:** **START** - Must-start WR1, NFL's leading receiver

**LLM Reasoning:**
- **Historic season:** 1,313 receiving yards in 11 games - BROKE DK Metcalf's Seahawks single-season record
- **Week 12 explosion:** 8-167-2 (37.1 fantasy pts) vs Titans - 5th most receiving yards through 11 games in Super Bowl era
- **Consistency:** 100+ yards in 8 of 11 games, 90+ in 10 of 11 games - ELITE floor
- **Matchup:** Vikings have struggled vs perimeter plays, Sam Darnold's efficient play-action opens intermediate routes
- **Expert consensus:** WR1 overall for Week 13 - "Jaxon Smith-Njigba will continue to thrive. The Vikings don't stand a chance."
- **Weather:** Lumen Field outdoor but minimal impact - partly cloudy, cool temps, calm winds
- **Projection:** WalterFootball projects 7 catches, 110 yards, 1 TD (23 pts)

**Data Sources Used:** vegas, weather, defense, recent_performance, experts, bias_analysis

---

### WIDE RECEIVER #2: Rashee Rice (KC @ DAL, AWAY, Thursday 4:30 PM)
- **ESPN Projection (IBM watsonx):** 18.1 pts
- **LLM Projection (Claude Sonnet 4.5):** 20.2 pts (HIGH confidence)
- **Recommendation:** **START** - Elite matchup vs Cowboys' struggling secondary

**LLM Reasoning:**
- **Injury status:** OFF injury report - full practice Tuesday/Wednesday after limited Monday (hamstring)
- **Matchup:** Cowboys allow MOST fantasy PPG to WRs this season - ELITE opportunity
- **Recent form:** 8-141 vs Colts (Week 11), 4 TDs in 5 games since return from suspension
- **Offensive fit:** Chiefs run 72% zone coverage, which exploits Dallas's scheme perfectly (0.27 EPA/play vs zone)
- **Vegas odds:** O/U 52 points - high-scoring Thanksgiving game expected
- **Expert consensus:** WR6 overall, SI.com "must-start Chiefs trio emerges" - Rice is priority target
- **Route efficiency:** 259 of ~400 yards since return have come after the catch - YAC monster

**Data Sources Used:** injury_reports, vegas, defense, recent_performance, experts

---

### TIGHT END: Juwan Johnson (NO @ MIA, AWAY, Sunday 1:00 PM)
- **ESPN Projection (IBM watsonx):** 8.7 pts
- **LLM Projection (Claude Sonnet 4.5):** 10.8 pts (MEDIUM confidence)
- **Recommendation:** **START** - Strong streaming option with Tyler Shough chemistry

**LLM Reasoning:**
- **Matchup:** Dolphins allow 4th-most fantasy PPG to TEs, 10+ pts to 7 TEs this season
- **Recent form:** Double-digit fantasy pts in 5 straight games (averaging 13 PPG with Tyler Shough)
- **Role:** Clear #2 passing option behind Chris Olave, especially with Alvin Kamara (MCL) out
- **Shough connection:** 23-301-2 over last 5 games - increased usage under new QB
- **Expert consensus:** SI.com Fab's Five "START Juwan Johnson", ranked TE6-TE10 across platforms
- **Historical bias:** ESPN TE projections very low accuracy (R²=0.231) - use recent form instead

**Data Sources Used:** defense, recent_performance, experts, injury_reports, bias_analysis

---

### FLEX: Tetairoa McMillan (CAR @ LAR, AWAY, Sunday 4:25 PM)
- **ESPN Projection (IBM watsonx):** 13.2 pts
- **LLM Projection (Claude Sonnet 4.5):** 13.7 pts (MEDIUM confidence)
- **Recommendation:** **START** - Target volume + late game = FLEX positioning

**LLM Reasoning:**
- **Week 11 explosion:** 8-130-2 (33.0 fantasy pts) vs Falcons - showed elite upside
- **Week 12:** More modest 2-35-1 (11.5 pts) but still found end zone
- **Role:** Leads Carolina in catches (54), receiving yards (748), TDs (4)
- **Matchup:** Rams defense is elite (#1 in points allowed) but Panthers have shown they can move the ball
- **Bryce Young chemistry:** Clearly the #1 target - 7 targets in Week 12, 12 targets in Week 11
- **Expert consensus:** WR13-16 range for Week 13 - FLEX conversation player
- **Game time:** 4:25 PM - LATEST Sunday game on roster (put in FLEX for flexibility)

**Data Sources Used:** defense, recent_performance, experts, game_script

**FLEX POSITIONING:** McMillan plays at 4:25 PM - place in FLEX slot for maximum roster flexibility.

---

### KICKER: Jason Myers (SEA vs MIN, HOME, Sunday 4:05 PM)
- **ESPN Projection (IBM watsonx):** 8.5 pts
- **LLM Projection (Claude Sonnet 4.5):** 10.9 pts (MEDIUM confidence)
- **Recommendation:** **START** - Seahawks high-scoring offense = FG opportunities

**LLM Reasoning:**
- **Recent form:** 9, 15, 14, 13 pts over last 4 weeks - averaging 12.8 PPG
- **Vegas environment:** Seahawks favored, high team total expected vs Vikings
- **Weather:** Lumen Field outdoor, partly cloudy, cool temps, minimal wind - good kicking conditions
- **Historical bias:** ESPN K projections RANDOM (R²=0.039) - ignore ESPN projection entirely
- **Expert consensus:** SI.com ranks Myers as #1 kicker for Week 13

**Data Sources Used:** vegas, weather, recent_performance, bias_analysis

---

### DEFENSE: Rams D/ST (LAR vs CAR, HOME, Sunday 4:25 PM)
- **ESPN Projection (IBM watsonx):** 7.5 pts
- **LLM Projection (Claude Sonnet 4.5):** 8.8 pts (HIGH confidence)
- **Recommendation:** **START** - Elite defense vs struggling offense

**LLM Reasoning:**
- **Elite defense:** #1 in points allowed per game (16.3), top-3 D/ST play this week
- **Recent form:** 20 pts in Week 12 vs TB - dominating recent opponents
- **Turnover machine:** 10 turnovers over past 4 weeks - forced fumbles and INTs
- **Matchup:** Panthers held under 17 pts in 5 of last 6 games, rank 25th in pass block win rate
- **Expert consensus:** Ranked #5 D/ST for Week 13 across platforms
- **Historical bias:** ESPN D/ST projections moderate (R²=0.044, Bias=+0.12)

**Data Sources Used:** defense, recent_performance, experts, bias_analysis

---

## Alternative Lineup Considerations

### Bench Player Rankings (If Injuries Force Changes)

| Priority | Player | Position | LLM Proj | When to Start |
|----------|--------|----------|----------|---------------|
| 1 | Keenan Allen | WR | 12.7 | If McMillan out or flex upgrade needed |
| 2 | Jordan Love | QB | 15.7 | If Brissett injured pregame |
| 3 | Jameson Williams | WR | 10.8 | AVOID - 0.0 pts Week 12, boom/bust |
| 4 | Tyjae Spears | RB | 8.4 | If Irving limited more than expected |
| 5 | Marvin Harrison Jr. | WR | 9.4 | Only if cleared and full practice |
| 6 | Evan Engram | TE | 6.5 | Only if Johnson injured |
| 7 | Devin Singletary | RB | 4.5 | Last resort only |

---

## Waiver Wire Recommendations

### Priority Adds (Verified Availability from `free-agents` output)

#### 1. **Isiah Pacheco (RB, KC)** - Rank #44 RB, 9.7 ESPN proj
- **Availability:** AVAILABLE (#4 free agent)
- **Analysis:** Chiefs RB1 returning from injury - immediate RB2/FLEX value
- **Thanksgiving impact:** Plays Thursday @ DAL, could dominate touches vs weak run D
- **Drop candidate:** Devin Singletary (6.3 proj, brutal matchups ahead)

#### 2. **Chuba Hubbard (RB, CAR)** - Rank #35 RB, 6.0 ESPN proj
- **Availability:** AVAILABLE (#5 free agent)
- **Analysis:** Lead back in Carolina - volume play
- **Drop candidate:** Tyler Allgeier (if still rostered)

#### 3. **Cooper Kupp (WR, SEA)** - Rank #56 WR, 8.4 ESPN proj
- **Availability:** AVAILABLE (#8 free agent)
- **Analysis:** Veteran WR in elite offense - WR3/FLEX upside
- **Drop candidate:** Consider if waiver claim clears

#### 4. **Browns D/ST (CLE)** - Rank #8 D/ST, 5.2 ESPN proj
- **Availability:** AVAILABLE (#3 free agent)
- **Analysis:** Potential Week 14+ streaming option
- **Hold:** Rams D/ST is better for Week 13

---

## Critical Reminders

### Bye Week Check
**NO BYE WEEKS IN WEEK 13** - All 32 teams play

### Thanksgiving Day Strategy
**CRITICAL:** Two of your players play Thursday (Thanksgiving):
- **Rashee Rice (KC)** - 4:30 PM vs DAL - **LOCKED IN as WR2**
- **Emanuel Wilson (GB)** - 12:30 PM vs DET - **LOCKED IN as RB2**

Monitor injury reports closely Thursday morning for any last-minute scratches.

### Game Time Strategy: FLEX Positioning
**CRITICAL RULE:** Put LATEST-playing game in FLEX slot.

**Your Week 13 Schedule:**
- **Thursday 12:30 PM:** Emanuel Wilson (RB)
- **Thursday 4:30 PM:** Rashee Rice (WR)
- **Sunday 1:00 PM:** Jacoby Brissett (QB), Bucky Irving (RB), Juwan Johnson (TE)
- **Sunday 4:05 PM:** Jaxon Smith-Njigba (WR), Jason Myers (K)
- **Sunday 4:25 PM:** Tetairoa McMillan (WR/FLEX), Rams D/ST

**FLEX: Tetairoa McMillan (Sunday 4:25 PM)** - Latest game = FLEX slot

### Vegas Odds Summary
| Game | Spread | Total | Your Player's Implied Total |
|------|--------|-------|---------------------------|
| GB @ DET | DET -3 | 47.5 | 22.3 (RB Wilson) |
| KC @ DAL | KC -3 | 52 | 27.5 (WR Rice) |
| ARI @ TB | TB -3 | Unk | ~24 (QB Brissett, RB Irving) |
| SEA vs MIN | Unk | Unk | High (WR JSN, K Myers) |
| NO @ MIA | Unk | Unk | ~20 (TE Johnson) |
| CAR @ LAR | LAR -10.5 | Unk | ~17 (WR McMillan, D/ST Rams) |

**High-Scoring Environments:** KC (52 total), GB/DET (47.5 total) - key offensive players in shootout potential.

---

## APPENDIX: ESPN Projection Accuracy Analysis

**Analysis Date:** November 27, 2025
**Weeks Analyzed:** 1-12 (197 player-week records)
**Purpose:** Understand ESPN (IBM watsonx) projection reliability by position

---

### Overall ESPN Projection Accuracy (Weeks 1-12)

**Aggregate Statistics:**
- **Mean Absolute Error (MAE):** 4.45 points
- **Mean Bias:** +0.08 points (ESPN nearly neutral)
- **Root Mean Square Error (RMSE):** 6.01 points
- **R² Correlation:** 0.477 (moderate predictive power)

---

### Position-Specific Accuracy Analysis

| Position | Sample Size | MAE | Bias | RMSE | R² | Reliability |
|----------|-------------|-----|------|------|-----|-------------|
| **QB** | 16 | 6.20 | **-2.00** | 7.41 | **0.169** | VERY LOW |
| **RB** | 55 | 3.71 | +0.78 | 5.55 | **0.541** | HIGH |
| **WR** | 78 | 5.00 | +0.18 | 6.56 | 0.498 | MODERATE |
| **TE** | 24 | 3.57 | -0.56 | 4.66 | **0.231** | LOW |
| **K** | 12 | 3.29 | +0.24 | 3.92 | **0.039** | RANDOM |
| **D/ST** | 12 | 4.91 | +0.12 | 6.34 | 0.044 | RANDOM |

---

### Key Findings

**QBs:** ESPN under-projects by -2.00 pts on average - add 2 pts to ESPN projection
**RBs:** Most reliable position (R²=0.541) - trust ESPN base projections
**WRs:** Moderate reliability - use ESPN as starting point with context adjustments
**TEs:** Low correlation - use target volume and matchup instead
**K/D/ST:** Essentially random - use Vegas environment exclusively

---

### Team-Specific Bias: Your Opponent (4th and pinches)

From league-wide analysis:
- **4th and pinches QBs:** -2.69 pts bias (UNDERPERFORM projections)
- **4th and pinches RBs:** +0.70 pts bias (slightly beat projections)
- **4th and pinches WRs:** -1.56 pts bias (underperform)

**Implication:** Opponent's players may underperform ESPN projections, benefiting your matchup.

---

### Team-Specific Visualization Charts

![Overall Projection Accuracy](images/projection_accuracy_overall.png)
![Position-by-Position Accuracy](images/projection_accuracy_by_position.png)
![Error Distribution](images/projection_error_distribution.png)
![Weekly Accuracy Trends](images/projection_accuracy_trend.png)

### League-Wide Visualization Charts

![Team MAE Rankings](images/league_team_mae_ranking.png)
![Team x Position Bias Heatmap](images/league_bias_heatmap.png)
![League-Wide Position Scatter](images/league_positional_scatter.png)

---

## Monte Carlo Simulation Results

**My Team Total EV:** 131.0 pts
**Opponent Total EV (base):** 116.3 pts
**Win Probability:** 68.7%
**Expected Margin:** +14.6 pts

**Opponent Bench Substitution Analysis:**
- If DK Metcalf (QUESTIONABLE) sits: Quentin Johnston (12.2 pts) fills in
- If Baker Mayfield (QUESTIONABLE) sits: Shedeur Sanders (5.9 pts) fills in

**Monte Carlo Report:** [View Full Report](output/mc_reports/week13_mc_report.html)

---

## Conclusion

**Week 13 Strategy Summary:**
1. **START Jacoby Brissett over Jordan Love** - consistent floor (18+ in all starts) vs bust risk
2. **START Bucky Irving** despite pitch count - favorable matchup vs Cardinals D
3. **Emanuel Wilson RB2** by necessity - ride the hot hand from 26.5 pt Week 12
4. **JSN + Rashee Rice = locked-in WR1/WR2** - elite projections confirmed
5. **Juwan Johnson TE1** - strong streaming option with Shough chemistry
6. **McMillan in FLEX** - latest game time (4:25 PM) for flexibility
7. **Rams D/ST** - elite matchup vs struggling Panthers
8. **Trust Myers** based on Seahawks scoring environment, not random ESPN K projections

**Critical Actions:**
- **Thursday Morning:** Final injury check for Rice (hamstring) and Wilson (role)
- **Sunday Morning:** Monitor Bucky Irving snap allocation reports
- **Sunday 12:45 PM:** Final check before 1:00 PM games

**Projected Outcome:** 131.0 total points (LLM) vs 116.3 opponent projection = **+14.6 point WIN**

**68.7% win probability per Monte Carlo simulation. Happy Thanksgiving!**

---

*Analysis generated using ESPN Fantasy API, multi-source web research (Vegas odds, weather, expert consensus, defensive rankings), Monte Carlo simulation (10,000 iterations), and historical projection accuracy data (Weeks 1-12, 197 player-week records).*

**Sources:**
- [ESPN Week 13 Fantasy Rankings](https://www.espn.com/fantasy/football/story/_/page/FFWeeklyPlayerRank25main-46028352/fantasy-football-rankings-2025-nfl-week-qb-rb-wr-te-dst)
- [Vegas Insider Week 13 Odds](https://www.vegasinsider.com/nfl/nfl-week-13-odds-2025/)
- [SI.com D/ST Rankings](https://www.si.com/fantasy/week-13-fantasy-football-defense-rankings-seahawks-dst-leads-the-position-01kaxy2faadj)
- [Pro Football Network Week 13 Rankings](https://www.profootballnetwork.com/fantasy-football/early-fantasy-football-ppr-rankings-week-13-2025/)
- [CBS Sports Week 13 Analysis](https://www.cbssports.com/nfl/news/week-13-nfl-odds-picks-lines-best-bets-predictions/)
