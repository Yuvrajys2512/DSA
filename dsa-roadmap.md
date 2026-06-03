# DSA Roadmap — 16 Weeks to Interview-Ready

**Goal:** clear DSA rounds at product companies / strong startups (the kind paying 30–50 LPA).
**Language:** Python. **Spine:** NeetCode roadmap (free, curated, video per pattern). **Runway:** ~4 months, ~1–1.5 hrs/day.
**Total problems:** ~230 curated. Quality over count.

---

## Rules of Engagement (read these every time you feel like quitting)

1. **Daily floor: 2 problems. Non-negotiable.** Bad day? Sick? Lazy? Still do 2. The floor is what builds the streak; the streak is what builds the skill. Never let the floor break.
2. **The 40-minute rule.** Stuck for 40 min with zero progress → read the editorial, understand it fully, then close it and re-solve from a blank file. Looking at the solution is *learning*, not failure. Spinning for 3 hours on one problem is the failure.
3. **Solve, don't binge-watch.** Max **one** concept video per topic. After that, it's problems. Watching NeetCode explain 30 solutions feels productive and teaches you almost nothing.
4. **Track one number: problems closed today.** Not hours, not "studied." A problem is "closed" only when you've solved it from a blank file without looking.
5. **Spaced repetition.** Any problem you needed the editorial for → re-solve it 7 days later, cold. If you still can't, it's not learned. Keep a "redo" list.
6. **DO NOT EXPAND SCOPE.** No competitive programming, no "let me also do system design," no switching sheets. One spine. Finish it. You can add things *after* you've closed ~200 problems — not before.

---

## Phase 0 — Setup (2–3 days, do it once)

- LeetCode account + open the **NeetCode roadmap** (neetcode.io/roadmap) — this is your map for the whole journey.
- Learn **Big-O** properly — it's the only pure theory you need upfront. Know how to state time/space for any solution you write. Interviewers ask every time.
- Set up a single repo: `dsa/` with one file per problem (`p0001_two_sum.py`). Pushing to GitHub doubles as a public consistency record.
- **Milestone:** solve 3 easy array problems (Two Sum, Contains Duplicate, Valid Anagram) and push them.

---

## Phase 1 — Arrays, Hashing, Two Pointers, Sliding Window, Stacks (Weeks 1–3, ~35 problems)

The highest-ROI block. ~40% of easy/medium interview questions live here.

**Patterns to internalize:**
- Frequency maps / hash sets for O(n) lookups
- Two pointers (opposite ends + same direction)
- Sliding window — fixed size AND variable size (the variable one is the money pattern)
- Prefix sums
- Monotonic stack

**Milestone:** solve a medium variable-sliding-window problem (e.g. *Longest Substring Without Repeating Characters*) cold in under 30 minutes.

---

## Phase 2 — Binary Search + Linked Lists (Weeks 4–5, ~25 problems)

**Patterns:**
- Classic binary search + **binary search on the answer space** (this one trips everyone — master it)
- Fast/slow pointers (Floyd's cycle detection)
- Reversal, merging, dummy-node technique

**Milestone:** write *Reverse Linked List* and *Linked List Cycle* from memory, and solve *Koko Eating Bananas* (binary search on answer) cold.

---

## Phase 3 — Recursion, Backtracking, Trees (Weeks 6–7, ~35 problems)

The conceptual gate. If recursion clicks here, graphs and DP get much easier.

**Patterns:**
- A clean recursion template you trust
- Backtracking: subsets, permutations, combinations (learn the one template that does all three)
- Tree DFS (pre/in/post) and BFS (level order)
- BST properties (inorder = sorted)

**Milestone:** write a generic backtracking template and solve *Subsets* + *Permutations* cold. Solve *Lowest Common Ancestor* and *Validate BST*.

---

## Phase 4 — Heaps, Greedy, Intervals (Weeks 8–9, ~25 problems)

**Patterns:**
- Heaps / priority queues: top-K, k-way merge
- Interval merging + sorting tricks
- Greedy (and recognizing when greedy is *wrong*)

**Milestone:** *Top K Frequent Elements* and *Merge Intervals* cold.

---

## Phase 5 — Graphs (Weeks 10–12, ~35 problems)

Heavily tested at strong companies. Don't rush it.

**Patterns:**
- Build adjacency lists from edge lists
- BFS / DFS on grids and graphs
- Connected components / flood fill
- Topological sort (Kahn's + DFS)
- Dijkstra (shortest path)
- Union-Find (DSU)

**Milestone:** *Number of Islands*, *Course Schedule* (topo sort), and *Network Delay Time* (Dijkstra) cold.

---

## Phase 6 — Dynamic Programming (Weeks 13–15, ~40 problems)

The "senior signal." Doing DP well separates strong candidates. Approach it as **recursion + memo first, then convert to tabulation.** Don't start with tabulation — you'll just memorize and panic when the problem shifts.

**Patterns:**
- 1D DP (house robber, climbing stairs, decode ways)
- Unbounded/0-1 knapsack (coin change, partition)
- LIS (longest increasing subsequence)
- 2D grid DP (unique paths, min path sum)
- String DP (LCS, edit distance) — extremely common
- DP on intervals

**Milestone:** *House Robber*, *Coin Change*, *Longest Common Subsequence*, and *Edit Distance* cold. If you can do these four, your DP is interview-grade.

---

## Phase 7 — Tries, Cleanup, Mocks (Week 16+)

- Tries (a small but occasionally tested topic — ~5 problems)
- Re-solve everything on your "redo" list
- **Start timed mock interviews:** 1–2/week. Talk out loud while solving — communication is graded as much as correctness. Use a friend, Pramp, or just record yourself.

---

## After the Sheet (ongoing, until interviews)

- **LeetCode weekly contests** — best way to build speed under pressure. Even just attempting builds resilience.
- Before any specific company interview, grind that company's **tagged problems** on LeetCode (last 6 months).
- Keep the daily floor alive even at 1 problem/day so the skill doesn't decay.

---

## Reality Check

DSA is **necessary but not sufficient** for the roles you want. It gets you *past the filter*. Your projects (agentic AI, the hackathon wins) are what make you *memorable* once you're past it. So: don't let DSA eat your project time entirely, and don't let it become a perfectionism rabbit hole where you "master" arrays for 6 weeks. The goal is **competent and consistent**, finished in ~4 months — not perfect.

Close 2 problems today. That's the whole job today.
