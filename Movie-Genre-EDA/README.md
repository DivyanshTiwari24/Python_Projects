## Key Findings

### Research Questions

**1. Which genres are the most common?**
- **Drama** is by far the most common genre, followed by **Comedy**, **Thriller**,
  **Action**, and **Romance**.
- These top 4 genres alone account for roughly **~51%** of all movies in the dataset.
- Least common genres: Western, TV Movie, Foreign, War, History, Music.

**2. Which genres have the highest average budget and revenue?**
- **Highest average budget:** Adventure, Fantasy, Action, Science Fiction, Family
- **Highest average revenue:** Adventure, Fantasy, Animation, Action, Family
- Foreign and TV Movie genres show the lowest revenue by a wide margin.

**3. Which genres have the highest average profit?**
- **Adventure, Fantasy, Animation, Family, and Science Fiction** lead in average profit.
- These genres cost proportionally less to make while earning the most.
- Documentary has a very small budget but performs well proportionally.

**4. Which genres have the highest average popularity?**
- **Adventure** ranks highest in average popularity.
- Overall popularity scores are quite low (mostly between 0 and ~1.2), with
  Adventure topping out around 1.1–1.2.

**5. Which genres have the most movies with a voting average >= 8?**
- **With vote_count >= 50 filter (more reliable):** Documentary, Drama, Crime, War
- **Without the filter (vote_count = 0):** Documentary, Music, Drama, Comedy,
  Crime, Animation, Thriller
- The filtered result is considered more accurate, since a high vote average
  from very few votes is unreliable.

### Hypotheses

| # | Hypothesis | Result |
|---|-----------|--------|
| 1 | Best movies by **vote average** return higher profit & revenue | ❌ **Weak** — only a very slight positive correlation (~0.11) |
| 2 | Best movies by **popularity** return higher profit & revenue | ✅ **Strong** — clear positive correlation |
| 3 | Highly **budgeted** movies return high revenue & profit | ✅ **Confirmed** — budget rises with profit |
| 4 | Highly **budgeted** movies have high popularity | ✅ **Mostly true** — positive trend, with some large outliers |

### Bonus Insight — Profit per Genre per Year
- A heatmap of **profit per genre per year** (1960–2015) revealed:
  - **Adventure** and **Fantasy** profits surged dramatically from the early 2000s onward.
  - **Animation** shows notable profit spikes as far back as the 1960s.
  - Some genres have gaps in certain years simply because no movies of that genre
    exist in the dataset for that period.
