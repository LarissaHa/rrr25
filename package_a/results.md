## **📣 Rule Testing Recap: What We Learned from Package A in the Open Division**

### **🚨 Disclaimer**

The following analysis is based on **Open Division matches only**. While Package A was also tested in the Women’s and Coed divisions, only the Open Division had enough consistent data to support meaningful conclusions. Future updates (for the upcoming packages) will include those divisions as more data becomes available.

### **🧪 Summary: What Changed with Package A?**

We tested **Package A** to explore ways of improving game flow, reducing serve dominance, and encouraging longer rallies. The results in the table show the findings of our baseline tests compared to package A. And the results are promising:

| **Metric** | **Baseline** | **Package A** | **Change** |
| --- | --- | --- | --- |
| **Double Faults** | 27.77% | 22.78% | 🔽 *Significantly lower* |
| **Rallies (per point)** | 8.84% | 14.00% | 🔼 *Significantly higher* |
| **Sideouts** | 24.62% | 18.88% | 🔽 *Significantly lower* |
| **Sideouts w/ Defensive Touch** | 14.29% | 12.79% | ❗ *No significant change* |
| **Aces** | 20.05% | 21.02% | ❗ *No significant change* |
| **Non-Ace Points on Serve** | 4.84% | 10.52% | 🔼 *Significantly higher* |

When we say a change is **"statistically significant,"** we mean it’s **very unlikely to be due to random chance**. We conducted t-tests for every category and the result of the t-test was below 0.05 p-value, which is considered as “significant” in scientific experiments (e.g. social sciences).

![Screenshot 2025-06-06 at 14.20.35.png](https://github.com/LarissaHa/rrr25/blob/main/package_a/Screenshot%202025-06-06%20at%2014.20.35.png)

### **🔍 Deep Dive: What’s Behind the Numbers?**

To better understand how Package A influenced gameplay, we looked at more detailed performance indicators:

- **Touches per Point:**
    
    Increased from **3.2 to 3.5**, meaning more defensive opportunities.
    
- **Playable Points Rally Percentage:**
    
    Jumped from **18.6% to 30%**—a major shift indicating that nearly one-third of the points continuing after the serve involved a rally under Package A.
    
- **Average Changes of Possession During Rallies:**
    
    Increased from **3.2 to 3.6**, meaning not only are there more rallies, but the rallies themselves are longer.
    
- **First Serve Percentage:**
    
    Remained consistent—no major shift, which suggests that players still are prioritizing going after aces on their first serve.
    
- **Double Faults Percentage: Dropped significantly which suggests that players are being more cautious because they see defense as a more viable option if they didn’t ace the first serve.**
- **Non Ace Points on Serve: Went up significantly - one possible explanation is that with the outer boundary in play, receiving teams attempted more technical hits that resulted in more errors.**

📌 **Takeaway:** These quantitative changes point to a more balanced version of the game — longer points, more defensive play, and fewer double faults.

### **📊 The Game Quality Score: Measuring Overall RRR Goals in One Metric**

To summarize all these elements, we created a single **Game Quality Score** metric where **100 = ideal game quality** (i.e. it meets all the RRR goal metrics). Negative values and values beyond 100 are possible.

### **🧮 How Is the Game Quality Score set up?**

As a reminder, here’s what the RRR goals are:

| **Metric** | **Ideal Value** | **Why It Matters** |
| --- | --- | --- |
| **Rally %** | 25% or more | More rallies = more exciting points ✅ |
| **Double Faults** | Less than 20% | Fewer service errors = better flow 🚫 |
| **Aces** | Less than 15% and less than rally % | Aces are fine, but not too dominant 💥 |

And here’s how we calculate the Game Quality Score:

The score starts at 100

- The greatest weight is given to rally % (±2.5 per % above/below 25%)
- Double faults are the second biggest factor (+.25 per % below 20, -2 per % above 20).
- Aces greater than 15% only hurt the quality score if the ace % is greater than the rally %
- A bonus is given if the first serve percentage exceeds 70% (half a point for every % over 70)
- A bonus is given for longer rallies (Rally % x (3- Average change of possession per rally))

### **📊 How Did the Game Score Change?**

- **Baseline Open Division Games:**
    
    Average game score was **32** — far below the target, suggesting serve-dominated games with fewer rallies and too many double faults.
    
- **Under Package A:**
    
    The average game score **nearly doubled to 62**, a big jump toward the ideal of 100.
    

📌 **What this tells us:**

The rule changes in Package A **substantially improved game quality**—more rallies, fewer double faults, and a better balance between serving and playmaking.

### **🧑‍🤝‍🧑 Community Feedback: Mixed, but Hopeful**

Beyond the data, player feedback gives us deeper insight into how Package A *felt* on the court.

### **😃 Enjoyment Scores (Tournament Respondents)**

- **Median Enjoyment:** Increased from **7 → 8**
- **Mean Enjoyment:** Rose from **7.19 → 7.79**

Most players also spent time **training for Package A**, which may have helped with adaptation. Future rule packages (like bigger balls or NHZs) may test adaptability even further.

### **✅ What Players Liked Most**

| **Advantage** | **Mentions** |
| --- | --- |
| **More Rallies** | 64 |
| Easier Defense (with boundary changes) | 39 |
| Better Positioning (freer movement) | 22 |
| Skill Development (hitting/setting) | 24 |
| Reduced Double Faults (due to put-on serve) | 13 |

### **⚠️ What Raised Concerns**

| **Disadvantage** | **Mentions** |
| --- | --- |
| **Serve Still Too Strong** | 27 |
| Boundary Too Small | 25 |
| Reduced Rally Quality (fewer rundowns) | 14 |
| Same-Hand Toss – Mixed Reactions | 15 |

### **🌟 Final Thoughts: A Step in the Right Direction?**

Despite some valid concerns, **72.6% of respondents** believe the changes are moving the sport in a **better direction**.

The most appreciated shifts:

- More rallies
- More effective defense
- Greater focus on technique and teamwork

**Package A may not be perfect—but it’s a strong signal that we can evolve the game in a way that balances excitement with skill.**

### **🧾 Final Remarks**

Package A has sparked meaningful change—both in how the game is played and how it’s perceived. The data clearly shows a shift toward longer, more interactive points, and the community feedback—while mixed—leans strongly positive.

This test marks an important milestone:

**✅ Serve dominance is still present, so we need continue our work here**

**✅ Rallies are more common and engaging**

**✅ Game balance is moving closer to our target**

Of course, challenges remain. Serving dynamics, court boundaries, and rally quality are areas that players still feel strongly about. And with more ambitious changes on the horizon (like a bigger ball or no-hit zones), the next stages of testing will need to balance innovation with identity.

For now, Package A has shown that meaningful improvement is possible—and worth building on.

Thanks to all players, organizers, and community members who contributed time, feedback, and energy to this test. Let’s keep moving the sport forward—together.