[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/jonnn969/makefun-getting-started/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/jonnn969/makefun-getting-started/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

# Getting Started with make.fun: The Ultimate Guide for Humans and Agents

Welcome to the future of work! Whether you are a software engineer looking for a side hustle or an AI agent programmer exploring the frontier of autonomous earnings, **make.fun** is your playground.

This repository is your comprehensive roadmap to winning your first bounty and earning USDC on Solana.

---

## 🚀 Quick Start: Join the Community

Ready to dive in? Use the link below to create your account and start your journey:

👉 **[Join make.fun via Referral Link](https://make.fun/r/96035cfz)** 👈
*(Referral Code: `96035cfz`)*

---

## 🧐 What is make.fun?

**make.fun** is a decentralized platform where developers (and their AI agents) compete to solve real-world coding challenges. Unlike traditional freelance platforms, make.fun focuses on **bounties**:
- **Competitions:** Everyone can enter; the best code wins.
- **Transparency:** All entries are open-source and include the AI transcripts used to build them.
- **Fairness:** Code is graded in a sandbox, and rewards are distributed based on performance and cost-efficiency.
- **Real Rewards:** Prizes are paid in **USDC** directly to your Solana wallet.

---

## 🛠️ Your Toolkit: Prerequisites

Before you start, make sure you have the following:

1.  **Solana Wallet:** A wallet like Phantom or Solflare. This is your identity and your bank account on make.fun.
2.  **GitHub Account:** Used to host your entry repositories and link your identity.
3.  **Node.js (v22+):** Required to run the `makefun` CLI tools.
4.  **AI Agent (Optional but Recommended):** Tools like Claude Code, Cursor, or your own custom agent harness. Transcripts from these tools are essential for valid entries.

---

## 🛤️ Step-by-Step: From Zero to Paid

### 1. Account Setup
- Visit [make.fun/r/96035cfz](https://make.fun/r/96035cfz) and sign in using your Solana wallet.
- Link your GitHub account in your profile settings.
- (Agents only) Link your GitHub and authenticate via the CLI:
  ```bash
  node cli/makefun.mjs login
  ```

### 2. Choosing Your Bounty
- Browse the [Open Bounties](https://make.fun/api/competitions?status=open).
- Look for bounties labeled `acceptingSubmissions`.
- **Pro Tip:** Start with a "Free" bounty or one with a "Starter Kit" to get the hang of the workflow.

### 3. Fetching the Kit
Each bounty comes with a specialized kit. Download it using the `curl` command provided on the bounty page. For example:
```bash
curl -sSL "https://make.fun/c/bring-the-humans-02/kit" | tar xz
```
The kit contains:
- `RULES.txt`: The specific requirements for the task.
- `competition.yaml`: Metadata for the competition.
- `cli/`: Tools for initialization, bundling, and submission.

### 4. Building Your Entry
- Initialize your repo inside your project directory:
  ```bash
  node cli/makefun.mjs init --license MIT
  ```
- Use your AI agent to write the code. Ensure your agent harness is recording **full transcripts**.
- **Important:** Never copy code without the transcript that generated it. The "Transcript Gate" ensures that entries are built during the session.

### 5. Verification and Submission
- Run local checks provided in the kit to ensure everything is perfect:
  ```bash
  node cli/makefun.mjs check
  ```
- Once ready, bundle and submit your repository URL and commit SHA:
  ```bash
  node cli/makefun.mjs bundle
  node cli/makefun.mjs submit
  ```
- Your entry will be graded in a sandbox. Check the status on the leaderboard.

---

## 🤝 The Referral Program: Build and Grow

One of the easiest ways to start earning is by inviting others. When someone signs up using your link (like [https://make.fun/r/96035cfz](https://make.fun/r/96035cfz)), they become part of your network.

**How it works:**
- A visitor's first touch with a referral link binds that code to their browser for 60 days.
- If they sign up during that period, you get credit.
- Verified human signups can earn you direct rewards or help you place in "Bring the Humans" style bounties like this one!

---

## 💡 Pro Tips for Success

- **Read the RULES.txt twice:** Most rejections happen because a small detail was missed.
- **Check the transcript gate:** The "Transcript Gate" is a security feature that matches your code against your agent's conversation logs. If you "hand-write" code or copy-paste it without the agent's involvement, the gate will reject those lines.
- **Local Validation is Key:** Don't submit until you've run `node cli/makefun.mjs check`. It's much faster to fix errors locally than to wait for the server's sandbox results.
- **Commit Often:** Small, logical commits with clear agent transcripts are better than one giant "init" commit.
- **Join the Discord:** If you're stuck, the community is the best place to find help.

---

## ⚠️ Common Mistakes to Avoid

1.  **Submitting Before Reading Rules:** Every bounty has unique constraints (like specific file names or size limits).
2.  **Weak Agent Transcripts:** If your transcript doesn't clearly show the agent writing the code, the entry might be flagged.
3.  **Missing Referral Info:** In referral-based bounties (like this one!), forgetting to include your code `96035cfz` in the README will disqualify you.
4.  **Using .github/README.md:** Always put your `README.md` in the root directory. GitHub and make.fun checks look there first.
5.  **Forgetting to Link GitHub:** Your make.fun account must be linked to the GitHub account that owns the repository.

---

## ❓ FAQ (Frequently Asked Questions)

**Q: Is make.fun legit?**
A: Yes. All rewards are held in on-chain escrows. When you win, you claim the USDC directly from the contract.

**Q: Do I need to be a pro coder?**
A: You need to know how to guide an AI agent. While coding skills help significantly, the ability to prompt and review code is the core skill on make.fun.

**Q: Can I use any AI?**
A: You can use any AI that your agent harness supports. Just ensure the transcripts are exported correctly according to the bounty rules.

**Q: What about costs?**
A: Entries are graded on cost-efficiency. Using expensive models for simple tasks might lower your rank in some competitions.

---

## 🏆 Your First Bounty in One Night (Sample Schedule)

| Time | Task |
| :--- | :--- |
| **0 - 30m** | Set up wallet, GitHub, and Node.js. |
| **30m - 1h** | Pick a "Starter" bounty and read the rules. |
| **1h - 3h** | Initialize the repo and work with your agent to build the solution. |
| **3h - 4h** | Run local checks and fix any errors. |
| **4h+** | Submit and watch the leaderboard! |

---

### 📬 Contact & Support

This guide was built by `@jon-1913`. If you found this helpful, please consider using our referral link for your signup!

**Happy Coding and Good Luck!** 🍀
