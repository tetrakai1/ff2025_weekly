# Week 13 Lineup Suggestions - Valued Customers
**Generated:** November 27, 2025 (Thanksgiving Day - Updated)
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
- **Thanksgiving Thursday:** GB @ DET (Jordan Love, Emanuel Wilson, Jameson Williams), KC @ DAL (Rashee Rice)
- **Sunday:** ARI @ TB (Brissett, Bucky Irving), SEA vs MIN (JSN, Myers), CAR @ LAR (McMillan, Rams D/ST)
- **Sunday:** NO @ MIA (Juwan Johnson), LAC vs LV (Hampton, Keenan Allen), TEN @ JAX (Spears)

---

## Matchup Overview

**Opponent:** 4th and pinches (8-4, #2 in league)
**Your Projected Total:** 112.3 (ESPN) / 128.1 (LLM)
**Opponent's Projected Total:** 123.2 (ESPN) / 116.3 (LLM)
**Monte Carlo Win Probability:** 69.0%
**Expected Margin:** +14.9 pts

**Opponent's Top Threats:**
- Jahmyr Gibbs (RB): Elite RB1 in high-powered Lions offense
- Trey McBride (TE): Top-tier TE with heavy target volume
- DK Metcalf (WR): QUESTIONABLE - potential bench substitution

**Key Opponent Injuries:**
- Baker Mayfield (QB): QUESTIONABLE - shoulder injury (backup: Shedeur Sanders)
- DK Metcalf (WR): QUESTIONABLE

**Analysis:** Monte Carlo simulation gives us 69.0% win probability. The key advantage is our LLM projections account for real-time context that ESPN (IBM watsonx) misses.

---

## CRITICAL INJURY ALERTS

**BREAKING: Josh Jacobs (GB) OFF Injury Report** - Confirmed to play Thursday vs Lions. Emanuel Wilson returns to BACKUP role (was RB1 last week when Jacobs sat). Wilson's projection reduced from 7.4 to 4.5 pts.

**OUT - Marvin Harrison Jr. (ARI):** Appendicitis surgery (Nov 10). **Returned to practice Wednesday** - QUESTIONABLE for Week 13. ESPN still projecting 13.7 pts (BUG) - LLM projection 9.4 pts if active, 0.0 if out.

**RETURNING - Bucky Irving (TB):** Full practice Wednesday. Expected to play Week 13 vs ARI on a **pitch count**. Coach Bowles says he'll be "eased back" (~36% snaps).

**RETURNING - Omarion Hampton (LAC):** 21-day practice window opened Tuesday (Nov 25). **LIMITED practice Wednesday** (ankle). Expected to be activated Saturday afternoon for Sunday's game vs Raiders. OC Greg Roman plans "1-2 punch" committee with Kimani Vidal. Hampton says he feels "amazing." **LLM Projection: 9.0 pts** (committee reduces ceiling).

---

## Recommended Starting Lineup

| Position | Player | Team | Opponent | Time | ESPN Proj | LLM Proj | Conf | Decision |
|----------|--------|------|----------|------|-----------|----------|------|----------|
| **QB** | Jacoby Brissett | ARI | @ TB | Sun 1:00 PM | 17.3 | 17.9 | HIGH | **START** |
| **RB** | Bucky Irving | TB | vs ARI | Sun 1:00 PM | 11.8 | 18.0 | MED | **START** |
| **RB** | Emanuel Wilson | GB | @ DET | Thu 12:30 PM | 5.3 | 4.5 | LOW | **START*** |
| **WR** | Jaxon Smith-Njigba | SEA | vs MIN | Sun 4:05 PM | 21.9 | 23.2 | HIGH | **START** |
| **WR** | Rashee Rice | KC | @ DAL | Thu 4:30 PM | 18.1 | 20.2 | HIGH | **START** |
| **TE** | Juwan Johnson | NO | @ MIA | Sun 1:00 PM | 8.7 | 10.8 | MED | **START** |
| **FLEX** | Tetairoa McMillan | CAR | @ LAR | Sun 4:25 PM | 13.2 | 13.7 | MED | **START** |
| **K** | Jason Myers | SEA | vs MIN | Sun 4:05 PM | 8.5 | 10.9 | MED | **START** |
| **D/ST** | Rams D/ST | LAR | vs CAR | Sun 4:25 PM | 7.5 | 8.8 | HIGH | **START** |

**Total Projected Points:** 128.1 (LLM) vs 112.3 (ESPN)

***Wilson START with caveat** - User preference to commit Thursday. See "RB2 Decision Analysis" below for Wilson vs Wait for Hampton analysis. LLM recommends waiting for Hampton (higher ceiling).

---

## Full Bench Listing

| Position | Player | Team | Status | ESPN Proj | LLM Proj | Conf | Notes |
|----------|--------|------|--------|-----------|----------|------|-------|
| QB | Jordan Love | GB | BENCH | 15.7 | 15.7 | MED | Tough matchup vs DET - struggled to 7.1 pts in Week 12 |
| RB | Omarion Hampton | LAC | QUEST | 12.3 | 9.0 | MED | Expected activation Saturday - committee with Vidal |
| RB | Tyjae Spears | TEN | BENCH | 9.9 | 8.4 | LOW | Committee with Pollard - backup RB2 if waiting on Hampton |
| WR | Marvin Harrison Jr. | ARI | QUEST | 13.7 | 9.4 | LOW | ESPN BUG - still projecting. First practice since surgery |
| WR | Keenan Allen | LAC | BENCH | 12.0 | 12.7 | MED | WR36 - declining target share, borderline flex |
| WR | Jameson Williams | DET | BENCH | 11.8 | 10.8 | LOW | BUST ALERT - 0.0 pts Week 12, tough GB matchup |
| TE | Evan Engram | DEN | BENCH | 8.1 | 6.5 | LOW | Declining role - Johnson clearly better |

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
- **Historical bias:** QBs systematically under-projected by ESPN by -2.00 pts (R²=0.169)

**Data Sources Used:** vegas, defense, recent_performance, experts, bias_analysis

---

#### Jordan Love (GB @ DET, AWAY, Thursday 12:30 PM)
- **ESPN Projection (IBM watsonx):** 15.7 pts
- **LLM Projection (Claude Sonnet 4.5):** 15.7 pts (MEDIUM confidence)
- **Recommendation:** **BENCH** - Worst fantasy finish of the year last week (7.1 pts)

**LLM Reasoning:**
- **Recent disaster:** 7.1 fantasy pts vs Vikings (Week 12) - worst performance of season
- **Passing struggles:** Hasn't surpassed 200 passing yards in last 3 games
- **Defensive matchup:** Lions rank 15th vs pass (210.5 yards allowed) - middle of pack

**Data Sources Used:** vegas, defense, recent_performance, experts

**DECISION: START JACOBY BRISSETT** - Consistent floor (18+ in all 6 starts) vs Love's bust potential.

---

### RUNNING BACK #1: Bucky Irving (TB vs ARI, HOME, Sunday 1:00 PM)
- **ESPN Projection (IBM watsonx):** 11.8 pts
- **LLM Projection (Claude Sonnet 4.5):** 18.0 pts (MEDIUM confidence)
- **Recommendation:** **START** - Returning from injury with favorable matchup

**LLM Reasoning:**
- **Injury status:** Full practice Wednesday - cleared to play. Coach Bowles expects pitch count (~36% snaps)
- **Matchup:** Cardinals rank 17th vs run (114.2 YPG allowed), 22nd in fantasy PPG to RBs
- **Upside:** High ceiling (boom-or-bust) but even limited snaps could produce vs weak run D

**Data Sources Used:** injury_reports, defense, recent_performance, experts, vegas

---

### RUNNING BACK #2: Emanuel Wilson (GB @ DET, AWAY, Thursday 12:30 PM)
- **ESPN Projection (IBM watsonx):** 5.3 pts
- **LLM Projection (Claude Sonnet 4.5):** 4.5 pts (LOW confidence)
- **Recommendation:** **START** (user preference) - See detailed RB2 analysis below

**CRITICAL UPDATE:** Josh Jacobs confirmed to play Thursday. Wilson returns to BACKUP role.

**LLM Reasoning:**
- **Role change:** Wilson was RB1 last week (Jacobs OUT) - now BACKUP (Jacobs playing)
- **Week 12 context:** 26.5 pts was with Jacobs OUT - that role no longer exists
- **Matchup:** Lions have strong run defense, haven't allowed 100-yard rusher in 2025
- **Ceiling:** Reduced from 15+ pts to 6-8 pts max in backup role

**Data Sources Used:** vegas, defense, injury_reports, bias_analysis

---

### RB2 DECISION ANALYSIS: Wilson (Thursday) vs Wait for Hampton (Saturday News)

**The Question:** Should you start Emanuel Wilson on Thursday, or wait until Saturday to see if Omarion Hampton is activated for Sunday?

**CRITICAL CONTEXT:** Josh Jacobs is now **CONFIRMED TO PLAY** Thursday, which reduces Wilson's role from RB1 to backup.

---

#### Option 1: Start Wilson Thursday (User's Choice)

| Factor | Previous | **Updated** |
|--------|----------|-------------|
| **Projection** | ESPN: 5.3 / LLM: 7.4 | ESPN: 5.3 / **LLM: 4.5** |
| **Role** | RB1 (Jacobs OUT) | **Backup (Jacobs playing)** |
| **Week 12** | 26.5 pts (RB1 role) | **Not repeatable** |
| **Ceiling** | 15+ pts | **6-8 pts max** |

**PROS:**
- Game script could favor RBs in close divisional game (Packers +3)
- Wilson showed explosiveness last week - could vulture goal-line work
- Thanksgiving games historically feature heavy RB usage
- No risk of Hampton being limited in first game back

**CONS:**
- **Jacobs is BACK** and will be lead back - Wilson backup role
- **26.5 pts Week 12 was RB1 role** - unsustainable with Jacobs back
- Lions have legitimately good run defense
- Low ceiling (~6-8 pts max) in backup role

---

#### Option 2: Wait for Hampton News (Spears as Backup)

| Factor | Hampton (if activated) | Spears (if not activated) |
|--------|------------------------|---------------------------|
| **Game Time** | Sunday 4:25 PM | Sunday 1:00 PM |
| **Projection** | ESPN: 12.3 / LLM: 9.0 | ESPN: 9.9 / LLM: 8.4 |
| **Role** | Committee with Vidal | Committee with Pollard |
| **Ceiling** | 15+ pts (RB1 talent) | 12 pts (PPR catches) |

**PROS:**
- Hampton expected to be activated Saturday - likely to play
- Even in committee, Hampton has RB1 talent on good offense
- Spears available as backup option if Hampton doesn't activate
- Higher ceiling potential (9.0 Hampton vs 4.5 Wilson)

**CONS:**
- Hampton's first game back = unknown workload
- "1-2 punch" with Vidal = 50/50 split concern
- Risk of both backups producing poorly

---

#### Hampton Activation Update

- **21-day window opened Tuesday (Nov 25)** - Hampton practicing
- **LIMITED practice Wednesday** - progressing
- **Activation deadline: Saturday afternoon**
- **OC Greg Roman:** Plans "1-2 punch" committee with Kimani Vidal
- **Hampton quote:** "Feel amazing, hope to be full go once activated"
- **Outlook:** **LIKELY TO PLAY** Week 13 vs Raiders (Sunday 4:25 PM)

---

#### VERDICT: LLM Recommends Wait for Hampton

| Category | Wilson (Thursday) | Wait for Hampton | Winner |
|----------|-------------------|------------------|--------|
| Ceiling | 6-8 pts (backup) | 15+ pts (if activated) | **Hampton** |
| Floor | 2-4 pts | 5-8 pts (Spears backup) | **Hampton** |
| Role Clarity | Backup to Jacobs | Committee (either option) | Tie |
| Information | Commit now | Wait until Saturday | **Wait** |

**LLM RECOMMENDATION: WAIT FOR HAMPTON**

**Reasoning:**
1. **Jacobs return fundamentally changes Wilson's value** - 26.5 pt Week 12 was RB1 role that no longer exists
2. **Hampton has more upside** - rookie RB on good offense with RB1 talent
3. **Risk profile** - Wilson's ceiling is ~6-8 pts; Hampton's ceiling is 15+
4. **Spears is reasonable backup** - 8.4 LLM projection, PPR floor with catches

**USER PREFERENCE: START WILSON**

The user has indicated preference to start Wilson Thursday. This is a defensible choice:
- Eliminates uncertainty about Hampton's activation/workload
- Wilson could still produce 5-8 pts in favorable game script
- Avoids risk of Hampton being a "decoy" first game back

**Bottom Line:** Both options reasonable. LLM leans higher ceiling (wait), user prefers certainty (Wilson).

---

### WIDE RECEIVER #1: Jaxon Smith-Njigba (SEA vs MIN, HOME, Sunday 4:05 PM)
- **ESPN Projection (IBM watsonx):** 21.9 pts
- **LLM Projection (Claude Sonnet 4.5):** 23.2 pts (HIGH confidence)
- **Recommendation:** **START** - Must-start WR1, NFL's leading receiver

**LLM Reasoning:**
- **Historic season:** 1,313 receiving yards in 11 games - BROKE DK Metcalf's Seahawks single-season record
- **Week 12 explosion:** 8-167-2 (37.1 fantasy pts) vs Titans
- **Consistency:** 100+ yards in 8 of 11 games, 90+ in 10 of 11 games - ELITE floor

**Data Sources Used:** vegas, weather, defense, recent_performance, experts

---

### WIDE RECEIVER #2: Rashee Rice (KC @ DAL, AWAY, Thursday 4:30 PM)
- **ESPN Projection (IBM watsonx):** 18.1 pts
- **LLM Projection (Claude Sonnet 4.5):** 20.2 pts (HIGH confidence)
- **Recommendation:** **START** - Elite matchup vs Cowboys' struggling secondary

**LLM Reasoning:**
- **Injury status:** OFF injury report - full practice Tuesday/Wednesday after limited Monday (hamstring)
- **Matchup:** Cowboys allow MOST fantasy PPG to WRs this season - ELITE opportunity
- **Recent form:** 8-141 vs Colts (Week 11), 4 TDs in 5 games since return from suspension
- **Vegas odds:** O/U 52 points - high-scoring Thanksgiving game expected

**Data Sources Used:** injury_reports, vegas, defense, recent_performance, experts

---

### TIGHT END: Juwan Johnson (NO @ MIA, AWAY, Sunday 1:00 PM)
- **ESPN Projection (IBM watsonx):** 8.7 pts
- **LLM Projection (Claude Sonnet 4.5):** 10.8 pts (MEDIUM confidence)
- **Recommendation:** **START** - Strong streaming option with Tyler Shough chemistry

**LLM Reasoning:**
- **Matchup:** Dolphins allow 4th-most fantasy PPG to TEs, 10+ pts to 7 TEs this season
- **Recent form:** Double-digit fantasy pts in 5 straight games (averaging 13 PPG with Shough)
- **Role:** Clear #2 passing option behind Chris Olave

**Data Sources Used:** defense, recent_performance, experts, injury_reports

---

### FLEX: Tetairoa McMillan (CAR @ LAR, AWAY, Sunday 4:25 PM)
- **ESPN Projection (IBM watsonx):** 13.2 pts
- **LLM Projection (Claude Sonnet 4.5):** 13.7 pts (MEDIUM confidence)
- **Recommendation:** **START** - Target volume + late game = FLEX positioning

**LLM Reasoning:**
- **Week 11 explosion:** 8-130-2 (33.0 fantasy pts) vs Falcons - showed elite upside
- **Role:** Leads Carolina in catches (54), receiving yards (748), TDs (4)
- **Game time:** 4:25 PM - LATEST Sunday game on roster (put in FLEX for flexibility)

**Data Sources Used:** defense, recent_performance, experts, game_script

---

### KICKER: Jason Myers (SEA vs MIN, HOME, Sunday 4:05 PM)
- **ESPN Projection (IBM watsonx):** 8.5 pts
- **LLM Projection (Claude Sonnet 4.5):** 10.9 pts (MEDIUM confidence)
- **Recommendation:** **START** - Seahawks high-scoring offense = FG opportunities

**LLM Reasoning:**
- **Recent form:** 9, 15, 14, 13 pts over last 4 weeks - averaging 12.8 PPG
- **Historical bias:** ESPN K projections RANDOM (R²=0.039) - ignore ESPN projection entirely

**Data Sources Used:** vegas, weather, recent_performance, bias_analysis

---

### DEFENSE: Rams D/ST (LAR vs CAR, HOME, Sunday 4:25 PM)
- **ESPN Projection (IBM watsonx):** 7.5 pts
- **LLM Projection (Claude Sonnet 4.5):** 8.8 pts (HIGH confidence)
- **Recommendation:** **START** - Elite defense vs struggling offense

**LLM Reasoning:**
- **Elite defense:** #1 in points allowed per game (16.3), top-3 D/ST play this week
- **Recent form:** 20 pts in Week 12 vs TB - dominating recent opponents
- **Matchup:** Panthers held under 17 pts in 5 of last 6 games

**Data Sources Used:** defense, recent_performance, experts, bias_analysis

---

## Alternative Lineup Considerations

### Bench Player Rankings (If Injuries Force Changes)

| Priority | Player | Position | LLM Proj | When to Start |
|----------|--------|----------|----------|---------------|
| 1 | Omarion Hampton | RB | 9.0 | If activated and you didn't start Wilson |
| 2 | Keenan Allen | WR | 12.7 | If McMillan out or flex upgrade needed |
| 3 | Jordan Love | QB | 15.7 | If Brissett injured pregame |
| 4 | Tyjae Spears | RB | 8.4 | If waiting on Hampton and he's not activated |
| 5 | Jameson Williams | WR | 10.8 | AVOID - 0.0 pts Week 12, boom/bust |
| 6 | Marvin Harrison Jr. | WR | 9.4 | Only if cleared and full practice |
| 7 | Evan Engram | TE | 6.5 | Only if Johnson injured |

---

## Waiver Wire Recommendations

### Priority Adds (Verified Availability from `free-agents` output)

#### 1. **Isiah Pacheco (RB, KC)** - Rank #44 RB, 9.7 ESPN proj
- **Availability:** AVAILABLE (#4 free agent)
- **Analysis:** Chiefs RB1 returning from injury - immediate RB2/FLEX value
- **Thanksgiving impact:** Plays Thursday @ DAL, could dominate touches vs weak run D

#### 2. **Chuba Hubbard (RB, CAR)** - Rank #35 RB, 6.0 ESPN proj
- **Availability:** AVAILABLE (#5 free agent)
- **Analysis:** Lead back in Carolina - volume play

#### 3. **Cooper Kupp (WR, SEA)** - Rank #56 WR, 8.4 ESPN proj
- **Availability:** AVAILABLE (#7 free agent)
- **Analysis:** Veteran WR in elite offense - WR3/FLEX upside

#### 4. **Browns D/ST (CLE)** - Rank #8 D/ST, 5.2 ESPN proj
- **Availability:** AVAILABLE (#3 free agent)
- **Analysis:** Potential Week 14+ streaming option

---

## Critical Reminders

### Bye Week Check
**NO BYE WEEKS IN WEEK 13** - All 32 teams play

### Thanksgiving Day Strategy
**CRITICAL:** Two of your players play Thursday (Thanksgiving):
- **Rashee Rice (KC)** - 4:30 PM vs DAL - **LOCKED IN as WR2**
- **Emanuel Wilson (GB)** - 12:30 PM vs DET - **LOCKED IN as RB2** (user choice)

Monitor injury reports Thursday morning for any last-minute scratches.

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
| LAC vs LV | LAC -3 | Unk | ~23 (RB Hampton) |

---

## APPENDIX: ESPN Projection Accuracy Analysis

**Analysis Date:** November 27, 2025
**Weeks Analyzed:** 1-12 (197 player-week records)

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

**Implication:** Opponent's players may underperform ESPN projections.

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

**My Team Total EV:** 128.1 pts (with Wilson at 4.5)
**Opponent Total EV (base):** 116.3 pts
**Win Probability:** 69.0%
**Expected Margin:** +14.9 pts

**Opponent Bench Substitution Analysis:**
- If DK Metcalf (QUESTIONABLE) sits: Quentin Johnston (12.2 pts) fills in
- If Baker Mayfield (QUESTIONABLE) sits: Shedeur Sanders (5.9 pts) fills in

**Monte Carlo Report:** [View Full Report](output/mc_reports/week13_mc_report.html)

---

## Conclusion

**Week 13 Strategy Summary:**
1. **START Jacoby Brissett over Jordan Love** - consistent floor vs bust risk
2. **START Bucky Irving** despite pitch count - favorable matchup vs Cardinals D
3. **Emanuel Wilson RB2** (user choice) - note Jacobs is back, Wilson is backup now
4. **JSN + Rashee Rice = locked-in WR1/WR2** - elite projections confirmed
5. **Juwan Johnson TE1** - strong streaming option with Shough chemistry
6. **McMillan in FLEX** - latest game time (4:25 PM) for flexibility
7. **Rams D/ST** - elite matchup vs struggling Panthers
8. **Trust Myers** based on Seahawks scoring environment

**Critical Actions:**
- **Thursday Morning:** Final injury check for Rice (hamstring) and Wilson (role)
- **Saturday Afternoon:** Hampton activation decision - adjust if needed
- **Sunday Morning:** Monitor Bucky Irving snap allocation reports

**Projected Outcome:** 128.1 total points (LLM) vs 116.3 opponent = **+11.8 point WIN**

**69.0% win probability per Monte Carlo simulation. Happy Thanksgiving!**

---

*Analysis generated using ESPN Fantasy API, multi-source web research (Vegas odds, weather, expert consensus, defensive rankings), Monte Carlo simulation (10,000 iterations), and historical projection accuracy data (Weeks 1-12, 197 player-week records).*

**Sources:**
- [NFL.com - Jacobs cleared for Thursday](https://www.nfl.com/news/packers-rb-josh-jacobs-knee-off-injury-report-good-to-go-thursday-vs-lions)
- [Chargers.com - Hampton Injury Report](https://www.chargers.com/news/omarion-hampton-injury-report-raiders-week-13-2025)
- [SI.com - Hampton activation outlook](https://www.si.com/onsi/fantasy/injuries/fantasy-football-impact-omarion-hampton-practice-window-opens)
- [ESPN Week 13 Fantasy Rankings](https://www.espn.com/fantasy/football/)
