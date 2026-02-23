# My First Excel Project: What I Built, What I Learned, and What Still Has Me Scratching My Head

Just finished a guided Excel project by Luke Barousse and honestly? It really stretched me in ways I didn't expect. If you're into data and haven't checked him out, you're missing out.

The project was a **Salary Dashboard** — basically an interactive tool that helps job seekers figure out what salaries look like across different data-related jobs, countries, and work types.

---

## What the Dashboard Actually Does

You just pick a job title, a country, and a job type and the dashboard tells you the median salary for that combination. It also shows a bar chart ranking jobs by salary and a map showing salary differences across the world.

---

## A Real Example From the Dashboard

I filtered for a **Data Analyst** role in the **United States** on a **Full-time** basis and here's what came up instantly:

- 💰 Median Salary: **$90,000**
- 🏆 Top Platform: **Indeed**
- 📋 Job Count: **6,480**

The dashboard shows exactly which data jobs pay the most and which ones don't — one look at the chart and it's immediately clear.
<img width="1366" height="715" alt="Screenshot (1276)" src="https://github.com/user-attachments/assets/25998f85-7f26-4ee1-b02a-6d935ed17274" />

---

## The Skills I Got to Practice

**Charts** — A horizontal bar chart for comparing salaries across job titles and a map chart that color-codes countries by salary level. Small design choices like sorting jobs from highest to lowest salary make a big difference.

**Formulas** — The main formula combines MEDIAN() and IF() to filter salaries based on multiple conditions at once — job title, country, job type, and whether a salary was even entered. There's also a FILTER() formula that pulls a clean list of job schedule types.

**Data Validation** — This restricts what a user can select so only valid options are available. It's what makes the whole thing feel like a real tool rather than just a spreadsheet.

---

## The Parts That Still Have Me Thinking

The nested formulas are still new to me. Writing a MEDIAN() that wraps around an IF() that checks four conditions at the same time is a lot to take in. But I'm not rushing it. Every time I go back and look at it, something new clicks.

Some parts had me confused but I showed up anyway — and somehow, it all came together.

---

