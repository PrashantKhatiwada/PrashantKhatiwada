# Prashant Khatiwada

**Building software that has to work outside the demo — and testing models that have to work outside the training set.**

CS + Business Analytics @ Caldwell University, New Jersey · from Nepal · expected 2028

---

### `whoami`

I work in two directions at once.

One is product — backend and full-stack systems, mostly for small businesses and public problems in Nepal. The kind of software where someone notices immediately if it breaks.

The other is research — how machine learning models are validated, starting with financial data, where a clean cross-validation score can quietly be an artifact of letting the future leak into the past.

Both come from the same habit: wanting to know how a thing actually works, not just that it ran.

---

### `now`

```
building     · Nayaro Technologies — business software and SaaS for small businesses in Nepal
researching  · random vs. time-based validation in financial ML
learning     · scalable backend architecture, LLM fine-tuning, AI agents
studying     · CS + Business Analytics, Caldwell University
```

---

### `selected_work`

<!-- Add repo / live links to each project title below once the repos are public. -->

#### 01 / Ghushtalika

A civic-tech platform for Nepal where citizens can report bribery and corruption anonymously. Reports surface through a public feed and an interactive corruption map, categorized by government department and reported severity. It also includes **Janamat**, a public-opinion feature where people vote on ongoing national issues and see the collective result.

The design problem here is trust: anonymity, moderation, and presenting sensitive reports without turning them into noise.

`domain` civic tech · `status` in production at https://ghushtalika.com

#### 02 / DocsNepal

A document-generation platform for common Nepali paperwork. Guided forms produce properly structured leave applications, CVs, affidavits, rent agreements, RTI applications, and other personal, employment, education, and legal documents — in Nepali and English, exported as PDF or editable files.

Most of the difficulty is not the code. It is encoding what a "correct" document looks like for people who have never had to write one.

`domain` docs / automation · `status` in production at https://docs-nepal.vercel.app

#### 03 / TaxCurb

Business software in the tax and accounting space. A practical tool rather than an experiment — built around real workflows and the constraints that come with them.

`domain` business software · `status` mvp at https://taxcurb.net

#### 04 / Fake News Classification

Text classification with TF-IDF features and logistic regression. Deliberately small: a supervised baseline, not research.

Worth listing because it is where the validation question started — a good test score and a model that generalizes are not the same claim.

`domain` ML · `status` in progress

---

### `research.log`

**Evaluating the Impact of Random vs. Time-Based Validation on Financial Machine Learning Model Performance**

> To what extent does random cross-validation overstate the predictive accuracy of financial models compared with time-based or walk-forward validation?

Random train-test shuffles time. On a financial series that means a model can train on Thursday and be tested on Tuesday — scoring well on a future it would never have had access to. The project measures how wide that gap gets across standard models under random splits versus walk-forward validation.

```
models      · Linear regression, decision tree, random forest, XGBoost, MLP, LSTM
approach    · temporal splits, walk-forward validation, leakage-aware features
measuring   · the distance between reported accuracy and honest accuracy
status      · active
```

---

### `stack`

|  |  |
|---|---|
| **Languages** | Python · TypeScript · JavaScript · C · SQL · HTML/CSS |
| **Backend** | Node.js · Express · NestJS · Django · REST APIs · Socket.IO |
| **Frontend** | React · Next.js · Tailwind CSS |
| **Data / ML** | NumPy · Pandas · scikit-learn · TensorFlow · OpenCV · Matplotlib · Seaborn |
| **Data / Infra** | PostgreSQL · SQL Server · Redis · Prisma · Docker · Git |
| **Design** | Figma · Canva · WordPress |

I am fluent in most of the first three rows and still building real depth in the rest — production infrastructure, system design, and the machine learning that sits past scikit-learn.

---

### `open_questions`

What I am currently learning, framed as the things I cannot answer well yet.

- How much of a fine-tuned model's improvement is the data, and how much is a generous evaluation?
- Where does temporal leakage hide in a feature pipeline that looks clean?
- What actually breaks first when a backend goes from ten requests to ten thousand — and is it ever the part you expected?
- When is Redis the right answer, and when is it a cache placed in front of a bad query?
- What does an AI agent need to be trusted with a real business workflow, rather than a demo of one?
- What separates a research result from a result you got lucky on once?

---

### `nayaro_tech`

I am building [**Nayaro Technologies**](https://nayaro.tech) — a technology and product lab working on software for businesses in Nepal: digital credit ledgers, restaurant and billing systems, internal management tools, and AI automation. Small-business software, built for the constraints those businesses actually operate under.

Most of what I know about shipping, I learned here rather than in a course.

---

### `elsewhere`

Before this, I worked as an IT & Media Communications Officer at my university — technical and event operations, digital communication, design, and livestream/AV support — and earlier in a frontend and technology role in Nepal, where I also helped organize local tech meetups.

| | |
|---|---|
| Portfolio | [prashantkhatiwada.com.np](https://www.prashantkhatiwada.com.np) |
| LinkedIn | [in/prashantkhatiwada10](https://www.linkedin.com/in/prashantkhatiwada10/) |
| Nayaro Labs | [nayaro.tech](https://nayaro.tech) |
| Email | [pkhatiwada58@gmail.com](mailto:pkhatiwada58@gmail.com) |

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="[https://github-readme-stats.vercel.app/api?username=PrashantKhatiwada&show_icons=true&hide_border=true&hide_title=true&hide=issues&theme=transparent&text_color=c9d1d9&icon_color=8b949e&title_color=c9d1d9](https://github-stats-extended.vercel.app/api?username=PrashantKhatiwada&rank_icon=github&custom_title=My%20Github%20Stats&show_icons=true&include_all_commits=true&theme=swift)">
  <img src="[https://github-readme-stats.vercel.app/api?username=PrashantKhatiwada&show_icons=true&hide_border=true&hide_title=true&hide=issues&theme=transparent&text_color=24292f&icon_color=57606a&title_color=24292f" alt="GitHub statistics for PrashantKhatiwada](https://github-stats-extended.vercel.app/api?username=PrashantKhatiwada&rank_icon=github&custom_title=My%20Github%20Stats&show_icons=true&include_all_commits=true&theme=swift)" width="450">
</picture>

---

*The number that says it works is not the same as it working.*
